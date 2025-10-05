# Ex.06 Book Front Cover Page Design
# Date:05/10/2025
# Ref no:25018064
# Name:TAMIZHAN B
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
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Environmental Awareness — Title Page</title>

  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">

  <style>
    :root{
      --page-width: 500px;   /* page width */
      --card-pad: 24px;      /* padding */
    }

    *{box-sizing:border-box;margin:0;padding:0}

    html,body{
      height:100%;
      font-family: "Inter", sans-serif;
      background: #000;
      color:#fff;
    }

    .wrap {
      min-height:100%;
      display:flex;
      align-items:center;
      justify-content:center;
      padding:20px;
    }

    .card {
      width: min(90vw, var(--page-width));
      aspect-ratio: 3 / 4;   /* book-like ratio */
      position:relative;
      border-radius: 10px;
      box-shadow: 0 15px 30px rgba(0,0,0,0.8);
      overflow:hidden;

      /* Gold border */
      border: 2px solid gold;

      /* Black edges + white flower background */
      background:
        radial-gradient(circle at center, rgba(15,15,15,0.9) 70%, rgba(0,0,0,1) 100%),
        url('https://images.unsplash.com/photo-1501004318641-b39e6451bec6?q=80&w=1200&auto=format&fit=crop') center/cover no-repeat;
    }

    .title-wrap{
      z-index:2;
      position:relative;
      text-align:center;
      padding:40px 16px;
    }

    h1.title{
      font-family:"Playfair Display", serif;
      font-size: clamp(22px, 5vw, 36px);
      margin-bottom: 10px;
      color:#fff;
      text-shadow:0 3px 10px rgba(0,0,0,0.7);
    }

    p.subtitle{
      font-size: clamp(11px, 2vw, 14px);
      color:#f0f0f0;
      opacity:0.9;
      margin-bottom:14px;
    }

    .divider{
      width:50%;
      height:1px;
      background: rgba(255,255,255,0.3);
      margin:14px auto;
    }

    .points {
      position:absolute;
      left: var(--card-pad);
      bottom: 50px;
      z-index:2;
      background: rgba(0,0,0,0.35);
      padding:6px 10px;
      border-radius:6px;
      font-size:10px;
      line-height:1.3;
      max-width:70%;
      opacity:0.95;
    }

    .points ul {
      margin:0;
      padding-left:14px;
    }

    .points li {
      margin-bottom:3px;
    }

    .author {
      position:absolute;
      right: var(--card-pad);
      bottom: var(--card-pad);
      font-weight:600;
      font-size:11px;
      color:#fff;
      background: rgba(0,0,0,0.4);
      padding:6px 10px;
      border-radius:6px;
    }
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card">
      <div class="title-wrap">
        <h1 class="title">Environmental Awareness</h1>
        <p class="subtitle">Understanding our environment and protecting nature</p>
        <div class="divider"></div>
        <p class="subtitle">Book Title Page</p>
      </div>

      <!-- Points section -->
      <div class="points">
        <ul>
          <li>Protect natural resources</li>
          <li>Reduce pollution and waste</li>
          <li>Conserve biodiversity</li>
          <li>Promote sustainable living</li>
        </ul>
      </div>

      <div class="author">B.TAMIZHAN </div>
    </div>
  </div>
</body>
</html>



# OUTPUT:
<img width="400" height="620" alt="Screenshot 2025-10-05 144405" src="https://github.com/user-attachments/assets/8e6d99c2-69a7-4fff-bfc1-6d1acb848066" />

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
