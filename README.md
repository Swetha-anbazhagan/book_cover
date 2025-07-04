# Ex.06 Book Front Cover Page Design
# Date:20/04/25
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

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Book cover</title>
  <style>
   .bookpage {
      width: 480px;
      height:700px;
      margin-left: auto;
      margin-right: auto;
      font-family: Arial, sans-serif;
      padding: 30px;
      background-color:#000000;
      color: white;
      background-size: cover;
    }
    .text-above{
      font-size: 20px;
      font-weight: bold;

    }
    .header {
      margin-top: 10px;
      border-top: 1px solid #ff6f3c;
      padding-top: 20px;
    }
    .title {
      font-size: 48px;
      font-weight: bold;
      color: white;
      margin-bottom: 20px;
    }
    .subtitle {
      font-size: 20px;
      color: white;
      margin-bottom: 5px;
    }
    
    .author {
      margin-top: 10px;
      font-size: 22px;
      font-weight: bold;
      margin-bottom: 20px;
    }
    .wave {
      margin-top: 10px;
    }
    .footer {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-top:20px;
      border-top: 1px solid #ff6f3c;
      padding-top: 10px;
    }
    .logo {
      color: #ff6f3c;
      font-weight: bold;
      font-size: 24px;
    }
    .author-img img {
      width: 70px;
     
    }
  </style>
</head>
<body>
  <div class="bookpage">
    <div class="text-above">EXPERT INSIGHT</div>
    <div class="header"></div>
    <div class="title">Mastering Node.js<br>Web Development</div>
    <div class="subtitle">Go on a comprehensive learning from fundamentals tro advance web development with node.js</div>
    <div class="wave">
      <img src="WhatsApp Image 2025-04-21 at 21.47.57_354c6f93.jpg" alt="Wave Art" style="width: 500px" object_fit:"cover">
    </div>
    <div class="author-img">
      <img src="author.jpg" alt="Author Image">
    </div>
  

    <div class="footer">
      <div class="author">Adam Freeman</div>
      <div class="logo">&lt;packt&gt;</div>
    </div>
  </div>
</body>
</html>

```
# OUTPUT:
![alt text](<Screenshot 2025-04-21 223930.png>)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
