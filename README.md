# Ex.06 Book Front Cover Page Design
## Date:29.06.2025
## Name:G.Mithik jain
## Ref no:212224240087
## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Cover</title>
  <style>
    body {
      background-color: #f4f4f4;
      font-family: 'Georgia', serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .book-cover {
      width: 300px;
      height: 450px;
      background: linear-gradient(to bottom, #612f8f, #296fb1ef);
      color: white;
      padding: 30px 20px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.3);
      border-radius: 12px;
      text-align: center;
      position: relative;
    }
    .book-title {
      font-size: 28px;
      font-weight: bold;
      margin-top: 60px;
      line-height: 1.4;
    }
    .cover-image {
      margin: 20px auto;
      width: 300px;
      height: auto;
    }
    .book-subtitle {
      font-size: 16px;
      color: #ddd;
      margin: 20px 0;
    }
    .author {
      position: absolute;
      bottom: 30px;
      left: 0;
      width: 100%;
      font-size: 16px;
      font-style: italic;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div class="book-title">WEB DEVELOPMENT</div>
    <div class="book-subtitle">with django and Bootstrap Insights</div>
    <img src="django.jpg" alt="Cover Image" class="cover-image">
    <div class="author">by Mithik jain</div>
  </div>
</body>
</html>

```

## OUTPUT:

![alt text](<Screenshot 2025-04-29 211106.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
