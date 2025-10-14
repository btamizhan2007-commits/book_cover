# Ex.06 Book Front Cover Page Design
# Date:05/10/2025
# Ref no:25018064
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:<!doctype html>
<html>
<head>
    <title>Book Cover</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="cover">
        <div class="border">
            <h3 class="top">SEC Insights</h3>
            <h1>SPECIFIC AND TECHNOLOGIES</h1>
            <p class="sub"> shaping a smarter world, one byte at a time</p>

            <div class="left">
                <h4>FIVTH EDITION</h4>
                <div class="name">
                    <P>Tamizhan b (25018064)</p>
                </div>
            </div>

            <div class="right">
                <img src="AUTHOR.JPG" alt="Author Photo">
                <hr class="line">
                <div>
                    <p>SEC</p>
                </div>
            </div>

        </div>
        
    </div>
</body>
</html>
 
 style.css
 body {
    background-color: #9b26ad;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.cover {
    width: 400px;
    height: 550px;
    background:url(background.jpg);
    background-size: cover;
    background-position: center;
    position: relative;
    text-align: center;
    color: rgb(20, 20, 20);
    font-family: 'Times New Roman', sans-serif;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
}

.border {
    border: 4px solid rgb(15, 15, 16);
    margin: -7px;
    height: 95%;
    padding: 15px;
    position: relative;
}

.top {
    position: relative;
    bottom: 20px;
    right: 120px;
    margin: 0;
    padding: 6px 8px 6px 0;
    display: inline-block;
    font-size: 16px;
    border-bottom: 1px solid rgb(26, 166, 225);
    color: solid #9122ac; /* Note: This should likely be 'color: red;' for the text color */
}

h1 {
    font-size: 24px;
    margin-top: 30px;
    font-weight: bold;
}

.sub {
    font-style: italic;
    font-size: 15px;
    margin-top: 20px;
}

.left h4 {
    position: relative;
    top: 200px;
    right: 90px;
    font-size: 20px;
    font-style: unset;
    font-weight: bold;
    margin: 0;
}

.left p {
    position: relative;
    top: 240px;
    right: 100px;
    font-size: 20px;
    margin-top: 5px;
}

.right img {
    position: relative;
    top: 5px;
    left: 90px;
    width: 130px;
    height: 150px;
    border: 2px solid rgb(9, 134, 176);
}

.line {
    height: 2px;
    width: 100%;
    background-color: rgb(23, 23, 23);
}

.right p {
    font-style: initial;
    font-size: larger;
    top: 20px;
    left: 100px;
    margin-top: 5px;
    font-weight: bold;
    position: relative;
}



# OUTPUT:
   <img width="394" height="633" alt="Screenshot 2025-10-05 204700" src="https://github.com/user-attachments/assets/d1fa1062-42e1-40b2-b449-e2a60b05dfe6" />



# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
