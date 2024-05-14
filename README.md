# Ex09 Event Registration Web Application
## Date:10-05-2024

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
Home.html:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css"> <!-- Linking to an external CSS file -->
</head>
<body>
    <div class="container" style="width: 360px; height: 640px; position: relative ">
        <img src="mobile2.jpg" style="height: 650px; width: 370px; border-radius: 50px; position: absolute;" alt=""> <br> <br><br>
        <img src="logo.jpg"  style="position: absolute; left: 20%;">
        <h1>ADMISSIONS</h1>
        <br><br><br><br><br><br><br>
        <form action="" method="post">
            <a href="admission.html">ADD ADMISSION</a>
            <a href="login.html">LOGIN</a>
            <a href="https://www.saveetha.ac.in/">ABOUT US</a>
        </form>
    </div>
</body>
</html>

Admission.html:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css"> <!-- Linking to an external CSS file -->
</head>
<body>
    <div class="container" style="width: 360px; height: 640px; position: relative ">
        <img src="mobile2.jpg" style="height: 630px; width: 370px; border-radius: 50px; position: absolute;" alt=""> <br> <br><br>
        <img src="logo.jpg"  style="position: absolute; left: 20%;"> <br> <br>
        <form action="" method="post">
            
            <input type="text" name="" id="name" style="height: 30px;" placeholder="Name">
            <br>
            <br>
            <input type="text" name="" id="name" style="height: 30px;" placeholder="Dept">
            <br><br>
            <input type="text" name="" id="name" style="height: 30px;" placeholder="Mobile Number">
            <br>
            <br>
            <input type="text" name="" id="name" style="height: 30px;" placeholder="gender">
            <br><br>
            <input type="text" name="" id="name" style="height: 30px;" placeholder="Email">
            <br>
            <br>
            <a href="thank.html">LOGIN</a>
        </form>
        </form>
    </div>
</body>
</html>

Login.html:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css"> <!-- Linking to an external CSS file -->
</head>
<body>
    <div class="container" style="width: 360px; height: 640px; position: relative ">
        <img src="mobile2.jpg" style="height: 630px; width: 370px; border-radius: 50px; position: absolute;" alt=""> <br> <br><br>
        <img src="logo.jpg"  style="position: absolute; left: 20%;"> <br> <br> <br> <br>
        <form action="" method="post">
            <input type="text" name="" id="name" style="height: 30px;" placeholder="Register Number">
            <br>
            <br>
            <input type="text" name="" id="name" style="height: 30px;" placeholder="Password">

            <a href="thank.html">LOGIN</a>
        </form>
    </div>
</body>
</html>

Thanks.html:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css"> <!-- Linking to an external CSS file -->
</head>
<body>
    <div class="container" style="width: 360px; height: 640px; position: relative ">
        <img src="mobile2.jpg" style="height: 630px; width: 370px; border-radius: 50px; position: absolute;" alt=""> <br> <br><br>
        <img src="logo.jpg"  style="position: absolute; left: 20%; right: 20px;"> <br> <br> <br> <br>
        
        <h1 >THANK FOR REGISTERING AND LOGIN TO SAVEETHA COLLEGE</h1>

    </div>
</body>
</html>

style.css:

h1 {
    font-size: 32px; /* Decreased font size for mobile view */
    color: blue;
    font-family: Georgia, 'Times New Roman', Times, serif;
    position: absolute;
    top: 130px;
    left: 90px;
    right: 20px;
    margin-top: 20px; /* Adjusted margin for better spacing */
}

a{
    border-radius: 8px; /* Reduced border radius for a more subtle effect */
    color: rgb(246, 20, 174);
    padding: 10px 20px; /* Increased padding for better touch interaction */
    font-size: 18px; /* Adjusted font size for mobile view */
    padding: 30px;
}

/* Styled the outer box to resemble a mobile */
body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: #06d8ef;
}

.container {
    width: 80vw; /* Adjusted width for better visibility */
    max-width: 360px; /* Limited maximum width for mobile devices */
    height: auto;
    padding: 20px;
    background-color: #f1e8f1;
    border-radius: 13px;
    color: blueviolet;
}

/* Centered the content */
form {
    display: flex;
    flex-direction: column;
    align-items: center;
    position: relative;
    padding: 30px;
}

img {
    height: 50px; /* Adjusted image height for better fit */
    margin-bottom: 20px; /* Added margin for better spacing */
}

a:hover{
    text-decoration: none;
}


## OUTPUT:

![Screenshot 2024-05-14 165554](https://github.com/BharathJayachandran/Figma/assets/122089525/83f65e05-4b24-4cb8-945b-e1c43b661c56)
![Screenshot 2024-05-14 165603](https://github.com/BharathJayachandran/Figma/assets/122089525/345f5976-55dd-4d4d-b135-1a076669526d)
![Screenshot 2024-05-14 165612](https://github.com/BharathJayachandran/Figma/assets/122089525/f7365740-e0cb-4d96-9287-bd11295888ee)
![Screenshot 2024-05-14 165621](https://github.com/BharathJayachandran/Figma/assets/122089525/962fbeb4-b800-47fb-83d0-e88fe13e0a5d)



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
