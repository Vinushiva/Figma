# Ex09 Event Registration Web Application
## Date:25.10.2025

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
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Thank You</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    .container {
      position: relative;
      height: 100vh;
      background: linear-gradient(to bottom, #bae6fd, #fef9c3, #ffedd5);
      border: 8px solid black;
      border-radius: 25px;
      overflow: hidden;
      display: flex;
      flex-direction: column;
    }

    .bg-img {
      position: absolute;
      inset: 0;
      background-size: cover;
      background-position: center;
      opacity: 0.15;
      z-index: 0;
    }

    .header {
      position: relative;
      background: rgba(37, 99, 235, 0.93);
      color: white;
      padding: 12px;
      text-align: center;
      z-index: 2;
    }

    .header img {
      height: 40px;
      object-fit: contain;
    }

    .content {
      z-index: 2;
      flex: 1;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 30px;
      text-align: center;
      position: relative;
    }

    h1 {
      font-size: 34px;
      margin: 0 0 10px;
      color: #0f766e;
      font-weight: bold;
    }

    p {
      color: #495057;
      font-size: 16px;
      max-width: 260px;
      margin-bottom: 25px;
    }

    .success-icon svg {
      width: 90px;
      height: 90px;
      fill: #22c55e;
    }

    .btn {
      background: #14b8a6;
      padding: 14px 35px;
      color: white;
      border-radius: 14px;
      border: none;
      cursor: pointer;
      font-size: 18px;
      box-shadow: 0px 4px 8px rgba(0,0,0,0.25);
      transition: 0.3s;
    }

    .btn:hover {
      background: #0d9488;
    }

    .footer {
      position: relative;
      height: 160px;
      z-index: 2;
    }

    .footer-bg {
      position: absolute;
      bottom: 0;
      left: 0;
      right: 0;
      height: 130px;
      background: linear-gradient(to top, #fb923c, #fdba74, transparent);
      opacity: 0.8;
    }

    .footer-text {
      position: absolute;
      bottom: 10px;
      width: 100%;
      text-align: center;
      color: #0f766e;
      font-size: 12px;
    }
  </style>
</head>

<body>
<div class="container">

  <div class="bg-img" style="background-image: url('https://images.unsplash.com/photo-1699134710640-c2b282ba8e11?auto=format&fit=crop&w=1080');"></div>

  <div class="header">
    <img src="logo.png" alt="Saveetha Engineering College">
  </div>

  <div class="content">

    <div class="success-icon">
      <!-- Check Circle Icon -->
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="#22c55e" stroke-width="2" viewBox="0 0 24 24">
        <circle cx="12" cy="12" r="9"/>
        <path d="M9 12l2 2 4-4"/>
      </svg>
    </div>

    <h1>THANK YOU</h1>

    <p>We are all eagerly waiting for your participation in the sports events</p>

    <button class="btn" onclick="goHome()">Back to Home</button>
  </div>

  <div class="footer">
    <div class="footer-bg"></div>

    <div class="footer-text">
      Contact us:<br>
      sports@saveetha.ac.in
    </div>
  </div>

</div>

<script>
  function goHome() {
    // Replace with your homepage URL
    window.location.href = "/";
  }
</script>

</body>
</html>

```
## OUTPUT:
![alt text](<Screenshot 2025-11-09 165204.png>)
![alt text](<Screenshot 2025-11-09 172251.png>)

![alt text](<Screenshot 2025-11-09 165339.png>)
![alt text](<Screenshot 2025-11-09 165357.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
