<!DOCTYPE html>
<html>
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <link rel="stylesheet" href="style.css">



   <title>Personal portfolio</title>
   <style>
      /* Reset default browser styles */
      * {
         margin: 0;
         padding: 0;
         font-family:sans-serif;
      }

      /* Styles for header section */
      .header {
         width: 100%;
         height: 100vh;
         background-color: rgb(133, 3, 150);
      }

      /* Styles for navigation bar */
      nav {
         display: flex;
         margin: auto;
         width: 90%;
         padding: 20px;
         align-items: center;
         justify-content: space-between;
      }

      nav ul li {
         display: inline-block;
         list-style: none;
         margin: 10px;
      }

      nav ul li a {
         text-decoration: none;
         color: black;
         font-weight: bolder;
      }

      nav ul li a:hover {
         background-color:seagreen;
         border-radius: 2px;
         color: white;
      }

      .button-cv, .button-gfc{
         display: inline-block;
         margin-left: 0%;
         border-radius: 5px;
         transition: background-color 0.5s;
         background: black;
         padding: 10px;
         text-decoration: none;
         font-weight: bold;
         color: white;
         border: none;
         cursor: pointer;
      }

      .button-cv:hover {
         background-color: white;
         color: black;
      }

      .button-gfc{
         background: pink;
      }

      .button-gfc:hover {
         background-color: white;
         color: black;
      }

      /* Styles for body section */
      .body {
         margin-left: 100px;
         margin-top: 100px;
      }

      .body h1 {
         font-size: 30px;
         color: black;
         margin-bottom: 20px;
      }

      .demo1 {
         color: orange;
         margin-bottom: 30px;
      }
  
      .demo2 {
         color: black;
         line-height: 20px;
      }

      .button-lrn, .button-hire{
         background: black;
         padding: 10px 12px;
         text-decoration: none;
         font-weight: bold;
         color: seagreen;
         display: inline-block;
         margin: 30px 8px;
         border-radius: 5px;
         transition: background-color 0.3s;
         border: none;
         letter-spacing: 1px;
         cursor: pointer;
      }

      .button-lrn:hover {
         background-color:seagreen;
         color: black;
      }

      .button-hire {
         background: black;
      }

      .button-hire:hover {
         background-color: seagreen;
      }

      span {
         color: seagreen;
       }

      /* Styles for image section */
      .image {
         width: 45%;
         height: 100%;
         position: absolute;
         bottom: 0;
         right: 100px;
      }
      .image img {
         height: 70%;
         position:absolute;
         left: 50%;
         bottom: 10%;
         transform: translate(-60%);
         image-rendering: auto;
         border-radius: 80%;
    
      }
   </style>
</head>
<body>
   <!-- Header section -->
   <div class="header">
      <nav>

         <ul>
            <li><a href="#">HOME</a></li>
            <li><a href="aboutme.html">ABOUT ME</a></li>
            <li><a href="project.html">PROJECTS</a></li>
            <li><a href="contact.html">CONTACT ME</a></li>
         
         </ul>
      </nav>

      <!-- Body section -->
      <div class="body"><br>
         <h1>Hello <br> I'm Mounika Dorasakala </h1>
         <p class="demo2">Junior frontend developer, I bring ideas<br> to life as a frontend developer...</p><br><br>
         <a href="dresume.html" class="button-cv">Resume</a>
      </div>
      
      <!-- Image section -->
      <div class="image">
         <img src="C:\Users\Admin\Desktop\DSC03521.jpg">     
      </div>
   </div>
</body>
</html>
