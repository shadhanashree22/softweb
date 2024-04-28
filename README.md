# Ex.07 Software Product Company Website
## Date: 28.04.2024

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:

```
home.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> SOFTWARE DEVELOPMENT COMPANY</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100%;
                background-image: url("SOFT.png");
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 80%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:#141ff0;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: black;
            }
            ::placeholder {
                color: black;
            }
            form button {
                border: 2px solid#0f91e2;
                outline: none;
                padding: 5px 20px;
                color: black;
                border-radius: 10px;
                background:#75a7f7;
                cursor: pointer;
            }
            form button:hover {
                border: 2px solid#75a3f7;
                color:#c1f775;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            }
            
            .home {
                margin: -5px -5px;
                border: 2px solid #2c5bd3;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: #7580f7;
                border-radius: 30px;
                background-color:rgb(236, 231, 231);
                text-decoration: none;
                
                
            }
            .home:hover {
                border: 2px solid#75dff7;
                color:#f775db;
                background-color: rgb(223, 75, 12);
                transition: 0.5s;
                cursor: pointer;
            } 
            
            .people {
                margin: -5px -5px;
                border: 2px solid #2c5bd3;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: #7580f7;
                border-radius: 30px;
                background-color:rgb(236, 231, 231);
                text-decoration: none;
            }
            .people:hover {
                border: 2px solid#75dff7;
                color:#f775db;
                background-color: rgb(223, 75, 12);
                transition: 0.5s;
                cursor: pointer;
            } 
            .product {
                margin: -5px -5px;
                border: 2px solid #2c5bd3;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: #7580f7;
                border-radius: 30px;
                background-color:rgb(236, 231, 231);
                text-decoration: none;
            }
            .product:hover {
                border: 2px solid#75dff7;
                color:#f775db;
                background-color: rgb(223, 75, 12);
                transition: 0.5s;
                cursor: pointer;
            } 

            .contact {
                margin: -5px -5px;
                border: 2px solid #2c5bd3;
                padding: 15px 35px;
                letter-spacing: 1px;
                color: #7580f7;
                border-radius: 30px;
                background-color:rgb(236, 231, 231);
                text-decoration: none;
            }
            .contact:hover {
                border: 2px solid#75dff7;
                color:#f775db;
                background-color: rgb(223, 75, 12);
                transition: 0.5s;
                cursor: pointer;
            } 
            .content {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
            .text h2 {
                color: white;
                font-weight: 800;
                font-size: 40px;
                letter-spacing: 3px;
            }
            .text h4 {
                color: white;
                text-transform: capitalize;
                font-size: 15px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
            }
            .login {
                margin: 0px 10px;
                border: 2px solid#9875f7;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: rgb(242, 240, 240);
                border-radius: 30px;
                background-color:#837fa1;
                text-decoration: none;
            }
            .login:hover {
                border: 2px solid#759af7;
                color:#43434b;
                background-color: rgb(126, 114, 205);
                transition: 0.5s;
                cursor: pointer;
            } 
            .signup {
                margin: 0px 10px;
                border: 2px solid#9875f7;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: rgb(242, 240, 240);
                border-radius: 30px;
                background-color:#837fa1;
                text-decoration: none;
            }
            .signup:hover {
                border: 2px solid#759af7;
                color:#43434b;
                background-color: rgb(126, 114, 205);
                transition: 0.5s;
                cursor: pointer;
            }
            footer {
                background-color:#f2f2f5;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">SS PRODUCT</h1>
            <ul>
                <button type="submit"> <li><a href="http://127.0.0.1:8000/static/home.html" class="home" id="bg-"home"> Home </a></li></button>
                <button type="submit"> <li><a href="http://127.0.0.1:8000/static/product.html" class="product"> Products </a></li></button>
                <button type="submit"> <li><a href="http://127.0.0.1:8000/static/people.html" class="people"> People </a></li></button>
                <button type="submit"> <li><a href="http://127.0.0.1:8000/static/contact.html" class="contact"> About us</a></li></button>
            </ul>
            
        </div>
        <div class="content">
            <div class="text">
                <h2> SOFTWARE DEVELOPMENT COMPANY</h2>
                <br>
                <p><h4><b>WELCOME TO THE WORLD OF SOFTWARE DEVELOPMENT AND PRODUCT CREATION.EXPLORE THE WORLD OF PRODUCT DEVELOPMENT FIND YOURSELVES IN THE ADMIRST OF WONDERFUL EXPERIENCE</b></h4> </p>
                <br>
                <div>
                    <a href="#" class="login"> Log In </a>
                    <a href="#" class="signup"> Sign Up </a>
                </div>
            </div>
        </div>  
    </div>
    <footer>
        <center> Developed by S V SHADHANASHREE (212223230202) </center>
    </footer>
</body>
</html>

product.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> SOFTWARE DEVELOPMENT COMPANY </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: url("SOFT.png");
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 80%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:#141ff0;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: black;
            }
            ::placeholder {
                color: black;
            }

            .home {
                margin: -5px -5px;
                border: 2px solid #2c5bd3;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: #7580f7;
                border-radius: 30px;
                background-color:rgb(236, 231, 231);
                text-decoration: none;
                
                
            }
            .home:hover {
                border: 2px solid#75dff7;
                color:#f775db;
                background-color: rgb(223, 75, 12);
                transition: 0.5s;
                cursor: pointer;
            } 
            
            .people {
                margin: -5px -5px;
                border: 2px solid #2c5bd3;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: #7580f7;
                border-radius: 30px;
                background-color:rgb(236, 231, 231);
                text-decoration: none;
            }
            .people:hover {
                border: 2px solid#75dff7;
                color:#f775db;
                background-color: rgb(223, 75, 12);
                transition: 0.5s;
                cursor: pointer;
            } 
            .product {
                margin: -5px -5px;
                border: 2px solid #2c5bd3;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: #7580f7;
                border-radius: 30px;
                background-color:rgb(236, 231, 231);
                text-decoration: none;
            }
            .product:hover {
                border: 2px solid#75dff7;
                color:#f775db;
                background-color: rgb(223, 75, 12);
                transition: 0.5s;
                cursor: pointer;
            } 

            .contact {
                margin: -5px -5px;
                border: 2px solid #2c5bd3;
                padding: 15px 35px;
                letter-spacing: 1px;
                color: #7580f7;
                border-radius: 30px;
                background-color:rgb(236, 231, 231);
                text-decoration: none;
            }
            .contact:hover {
                border: 2px solid#75dff7;
                color:#f775db;
                background-color: rgb(223, 75, 12);
                transition: 0.5s;
                cursor: pointer;
            } 
            .container {
                background: transparent;
                padding: 200px 5%;
                padding-bottom: 120px;
            }
            .container .box-container {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
                gap: 100px;
            }
            .container .box-container .box {
                color: white;
                box-shadow: 0 5px 10px rgba(0,0,0,.2);
                border-radius: 30px;
                background: transparent;
                border: 1px solid gray;
                padding: 40px 30px;
            }
            .container .box-container .box img {
                height: 50px;
                border-radius: 20px;
            }
            .container .box-container .box h3 {
                color:rgb(177, 252, 14);
                font-size: large;
                padding: 10px 0;
            }
            .container .box-container .box p {
                color: rgb(249, 245, 245);
                font-size: 15px;
                line-height: 1.5;
            }
            footer {
                background-color:#e6dce4;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">SS PRODUCT</h1>
            <ul>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/home.html" class="home"> Home </a></li></button>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/product.html" class="product"> Product </a></li></button>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/people.html" class="people"> People </a></li></button>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/contact.html" class="contact"> About us </a></li></button>
            </ul>
            
        </div>
        <div class="container">
            <div class="box-container">
              
                
                <div class="box">
                    <h3> GitHub </h3>
                    <p> GitHub is a web-based hosting service that provides hosting for software development and version control. </p>
                </div>
                <div class="box">
                    <h3> LeanKit </h3>
                    <p> LeanKit is a cloud-based visual management system. It’s famous for enabling instant project visibility across all levels of the organization.  </p>
                </div>
                <div class="box">
                    <h3>  ProofHub</h3>
                    <p> ProofHub is a project planning software and it has almost every tool that a team might need to achieve timely deliverables on a project. </p>
                </div>
                <div class="box">
                    <h3> Code Climate</h3>
                    <p> Code Climate is an open-source platform meant to enable automated code review. It provides three kinds of GitHub pull requests. </p>
                </div>
                <div class="box">
                    <h3> Bitbucket</h3>
                    <p> Bitbucket is a web-based repository hosting service with version control. With this tool, you can work together on code with pull requests and inline comments. </p>
                </div>
                <div class="box">
                    <h3> Codenvy</h3>
                    <p> Codenvy is built on Eclipse Che, an open-sourced, cloud-based IDE (Integrated Development Environment). </p>
                </div>
                
                
                

            </div>
              
            </div>
        </div>
    </div>
    <footer>
        <center> Developed by S V SHADHANASHREE (212223230202) </center>
    </footer>
</body>
</html>

people.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Coding Platform </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: url("SOFT.png");
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 80%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:#141ff0;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: black;
            }
        

    
            ::placeholder {
                color: black;
            }
            
            .home {
                margin: -5px -5px;
                border: 2px solid #2c5bd3;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: #7580f7;
                border-radius: 30px;
                background-color:rgb(236, 231, 231);
                text-decoration: none;
                
                
            }
            .home:hover {
                border: 2px solid#75dff7;
                color:#f775db;
                background-color: rgb(223, 75, 12);
                transition: 0.5s;
                cursor: pointer;
            } 
            
            .people {
                margin: -5px -5px;
                border: 2px solid #2c5bd3;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: #7580f7;
                border-radius: 30px;
                background-color:rgb(236, 231, 231);
                text-decoration: none;
            }
            .people:hover {
                border: 2px solid#75dff7;
                color:#f775db;
                background-color: rgb(223, 75, 12);
                transition: 0.5s;
                cursor: pointer;
            } 
            .product {
                margin: -5px -5px;
                border: 2px solid #2c5bd3;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: #7580f7;
                border-radius: 30px;
                background-color:rgb(236, 231, 231);
                text-decoration: none;
            }
            .product:hover {
                border: 2px solid#75dff7;
                color:#f775db;
                background-color: rgb(223, 75, 12);
                transition: 0.5s;
                cursor: pointer;
            } 

            .contact {
                margin: -5px -5px;
                border: 2px solid #2c5bd3;
                padding: 15px 35px;
                letter-spacing: 1px;
                color: #7580f7;
                border-radius: 30px;
                background-color:rgb(236, 231, 231);
                text-decoration: none;
            }
            .contact:hover {
                border: 2px solid#75dff7;
                color:#f775db;
                background-color: rgb(223, 75, 12);
                transition: 0.5s;
                cursor: pointer;
    
            }
            .image {
                position: relative;
                border: 0;
                top: 70px;
                background: transparent;
            }
            .image table {
                border: 0;
                color: gray;
                position: relative;
                left: 150px;
            }
            .image table img {
                height: 140px;
                width: 140px;
                border: 2px solid gray;
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color:#8975f7;
            }
            footer {
                background-color:#efe3ec;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">SS PRODUCT</h1>
            <ul>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/home.html" class="home"> Home </a></li></button>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/product.html" class="product"> Product </a></li></button>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/people.html" class="people"> People</a></li></button>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/contact.html" class="contact"> About us </a></li></button>
            </ul>
            
        </div>
        <div class="image">
            <table cellspacing="100"> 
                <tr align="center">
                    <td> <img src="my pic.jpg"> </td>
                    <td> <img src="sundhar.pichai.jpeg"> </td>
                    <td> <img src="tata.jpeg"> </td>
                    <td> <img src="jeff.jpeg"> </td>
                    <td> <img src="mark.jpeg"> </td>
                </tr>
                <tr align="center">
                    <th> S V SHADHANASHREE</th>
                    <th> SUNDAR PICHAI</th>
                    <th> RATAN TATA </th>
                    <th> JEFF BEZOS</th>
                    <th> MARK ZUCKERBURG</th>
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> CEO, Co-Founder </td>
                    <td> Senior Developer</td>
                    <td> Director </td>
                    <td> Designer</td>
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center> DEVELOPED BY S V SHADHANASHREE (212223230202) </center>
    </footer>
</body>
</html>

contact.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Coding Platform </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: url("SOFT.png");
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 80%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:#3a0fe7;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: white;
            }
            ::placeholder {
                color: white;
            }
            
            .home {
                margin: -5px -5px;
                border: 2px solid #2c5bd3;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: #7580f7;
                border-radius: 30px;
                background-color:rgb(236, 231, 231);
                text-decoration: none;
                
                
            }
            .home:hover {
                border: 2px solid#75dff7;
                color:#f775db;
                background-color: rgb(223, 75, 12);
                transition: 0.5s;
                cursor: pointer;
            } 
            
            .people {
                margin: -5px -5px;
                border: 2px solid #2c5bd3;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: #7580f7;
                border-radius: 30px;
                background-color:rgb(236, 231, 231);
                text-decoration: none;
            }
            .people:hover {
                border: 2px solid#75dff7;
                color:#f775db;
                background-color: rgb(223, 75, 12);
                transition: 0.5s;
                cursor: pointer;
            } 
            .product {
                margin: -5px -5px;
                border: 2px solid #2c5bd3;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: #7580f7;
                border-radius: 30px;
                background-color:rgb(236, 231, 231);
                text-decoration: none;
            }
            .product:hover {
                border: 2px solid#75dff7;
                color:#f775db;
                background-color: rgb(223, 75, 12);
                transition: 0.5s;
                cursor: pointer;
            } 

            .contact {
                margin: -5px -10px;
                border: 2px solid #2c5bd3;
                padding: 15px 35px;
                letter-spacing: 1px;
                color: #7580f7;
                border-radius: 30px;
                background-color:rgb(236, 231, 231);
                text-decoration: none;
            }
            .contact:hover {
                border: 2px solid#75dff7;
                color:#f775db;
                background-color: rgb(223, 75, 12);
                transition: 0.5s;
                cursor: pointer;
            }
            .box {
                display: flex;
                column-gap: 40px;
                background: transparent;
                position: relative;
                top: 50px;
            }
            .box-1 {
                height: 400px;
                width: 400px;
                border: 3px solid #3b19c2;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 400px;
            }
            .box-2 {
                height: 400px;
                width: 400px;
                border: 3px solid#3b19c2;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 450px;
            }
            .box-1 form {
                display: flex;
                color: white;
                background: transparent;
                padding: 30px;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid #280df3;
                border-radius: 10px;
                padding: 15px 30px;
                font-size: 22px;
                color: white;
                position: relative;
                top: 30px;
            }
            .box-1 form textarea {
                background: transparent;
                color: white;
                padding: 10px 43px;
                position: relative;
                top: 30px;
                font-size: 22px;
                left: 0px;
                border: 1px solid #210ce3;
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 10px 20px;
                color: rgb(245, 239, 239);
                border-radius: 30px;
                background:#3c08e5;
                cursor: pointer;
                position: relative;
                top: 50px;
            }
            .box-1 form button:hover {
                border: 2px solid#7580f7;
                color:#9675f7;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            } 
            .box-2 h2 {
                color: white;
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p {
                font-size: large;
                color: white;
                position: relative;
                top: 50px;
                padding: 10px 80px;
            }
            .box-2 span {
                color:#1130e2;
                font-size: 20px;
            }
            footer {
                background-image:#f1edf0;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">SS PRODUCT</h1>
            <ul>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/home.html" class="home"> Home </a></li></button>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/product.html" class="product"> Product </a></li></button>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/people.html" class="people"> Peoples </a></li></button>
                <button type="submit"><li><a href="http://127.0.0.1:8000/static/contact.html" class="contact"> About us  </a></li></button>
            </ul>
            
        </div>
        <div class="box">
            <div class="box-1">
                <form>
                    <center>
                        <h1>  Contact Us </h1>
                        <input type="text" placeholder="Enter Your Name">
                        <br>
                        <input type="email" placeholder="Enter Your Email">
                        <br>
                        <textarea rows="0" cols="20" placeholder="Your Message"> </textarea>
                        <br>
                        <button type="submit" align="center"> Submit </button>
                    </center>
                </form>
            </div>
            <div class="box-2"> 
                <h2> Contact Information </h2>
                <p> <span>Address</span> : No.10,vaishnavi nagar,Ambattur,Chennai-600062</p>
                <p> <span>Email</span> : shadhzzz@gmail.com </p>
                <p> <span>Phone</span> : 9150992611</p>
            </div>
        </div>
    </div>
    <footer>
        <center> DEVELOPED BY S V SHADHANASHREE (212223230202) </center>
    </footer>
</body>
</html>
```



## OUTPUT:
![alt text](<Screenshot 2024-04-28 230052.png>)
![alt text](<Screenshot 2024-04-28 230117.png>) 
![alt text](<Screenshot 2024-04-28 230133.png>) 
![alt text](<Screenshot 2024-04-28 230146.png>)




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
