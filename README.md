<html>

<head>
<style> 
.About {
  
    margin: 20px;
    
}

.fotter{
    text-align:center;
    padding: 50px 0 20px;
}
.footer a:hover{
  
  text-color: Grey;
}

p {
    color: white;
}

table {
    width: 100%;
    border-collapse: collapse;
   
}
.fotter a{
 
    color:white;
    margin: 100px 20px;
    text-decoration: none;
    font-family:'Montserrat',sans-serif ;
}

td {
    padding: 10px;
    vertical-align: top;
}

.Education, .Experience, .Skills {
     /* Dark grey background color */
    color: white; /* White text color */
    padding: 20px;
    margin-bottom: 20px;
}

h2 {
    color: white; /* Gold color */
}

ul {
    list-style-type: none;
}

li {
    margin-bottom: 10px;
}



.About{
background-color:black;
color:white;

}



.div1{
 background-image: url("E:/6th Semester/Internet & Web enginerring/Portfolio site/i1.jpg");
  background-color: #cccccc;
  height: 800px;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;

}

.bar{
overflow: hidden;

padding:10px;	
border:10px;

}
.bar a{
text-align: center;
padding: 14px 16px;
font-size:17px;
float: left;
color: Black;
 text-decoration: none;

}
.bar a:hover {
  color: #EAF6F6;
  text-color: white;
}
.Contact{

background-color:White;
}

.Contact-1 {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 60vh; /* This centers vertically as well */
        }

input {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  box-sizing: border-box;
}
         input[type="submit"] {
            width: 15%; /* Adjust the width of the submit button */
            padding: 12px 20px;
            margin: 8px 0;
            box-sizing: border-box;
            position: absolute; /* Position the submit button absolutely */
            right: 300; /* Align to the right of the form container */
           color:white;
           background-color:black;
        }	



</style>

</head>

<body  style="background-color:black" >

<div  class="div1" >

<div class="bar" >
<a href=""><h4>HOME</h4></a>
<a href="#About"><h4>ABOUT</h4></a>
<a href="#Contact"><h4>CONTACT</h4></a>

</div>
<h1 align="center" style="padding-top:80px;font-weight: bold; font-size: 50px;";>I'm</h1>
<h1 align="center" style="font-weight: bold; font-size: 50px;"; ;>Muhammad Hamza</h1>
</br>
</br>
</div>




<div class="About" id="About" >
<h1 align="center" style="padding-top:100px;font-weight: bold; font-size: 50px; padding-bottom:100px;" >About</h1>
<h1 align="center" >Muhammad Hamza Qurashi<h1>
<h4 align="center">Student at Institute of Southern Punjab Multan<h4>
<p  align="center"style="color:"BLue">Multan, Punjab, Pakistan</p>


<table >

<tr>

<td>
<div class="Education" style="color:white">
<h2 >Education</h2>
<ul>
<li>Bachelors in Computer Sciences
<br>(October 2021 - October
2025)</li>
<li>Fs.c Enginerring</li>
<li>Matric</li>
</ul>

</div>
</td>

<td>
<div class="Experience" style="color:white">
<h2>Experience</h2>
<ul>
<li>Data Entry(SSS Groups)</li>
<li>Game Devolpment</li>
<li>Computer Next(Workshop)<li>

</ul>



</div>
</td>

<td>
<div class="Skills" style="color:white">
<h2>Skills</h2>

<ul>
<li>Data Structuer</li>
<li>Web & Software Dev.</li>
<li>ALgorithms</li>
</ul>
</div>
<td>

<tr>

</table>

</div>

<div class="Contact" id="Contact"> 
<h1 align="center" style=" padding-top:100px;font-weight: bold; font-size: 50px; padding-bottom:30px;">Contact<h1>
<p align="Center"  style="Color:black"><b>Leave your messege</b></p>

<div class ="Contact-1">

<form action="mailto:hamzaqurashi9mm@gmail.com" method="post" enctype="text/plain">
<table>
<tr>
<td width="30%">Name</td>
<td width="70%"><input type="name"></td>
</tr>
<tr>
<td width="30%">Email</td>
<td width="70%"><input type="email"></td>
</tr>
<tr>
<td width="30%">Messege</td>
<td width="70%"><textarea rows="5" cols="37"></textarea>	</td>

</tr>


</table>
<td style="float-right"><input type="submit" value="send" id=""></td>
 </form>


</div>
</div>



    <div class="fotter">
   
     
     <a class="footer-link" href="https://www.linkedin.com/">LinkedIn</a>
     <a class="footer-link" href="https://twitter.com/">Twitter</a>
     <a class="footer-link" href="https://www.appbrewery.co/">Website</a>
     <br>
     <p class="footer_C">© Muhammad Hamza .</p>
    </div>
    
