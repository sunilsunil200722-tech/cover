# Ex.06 Book Front Cover Page Design
## Date: 23/12/2025

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover - SUNIL KUMAR R</title>
    <style>
        /* CSS stays inside the style tag */
        body {
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #f0f0f0;
            font-family: 'serif', 'Times New Roman', Times, serif;
        }

        .book-cover {
            width: 45px;
            height: 65px;
            /* Matches the orange-to-yellow gradient in your image */
            background: linear-gradient(180deg, #FF7A00 0%, #FFB800 40%, #FFCC00 100%);
            padding: 50px;
            box-sizing: border-box;
            display: flex;
            flex-direction: column;
            color: white;
            box-shadow: 0 20px 40px rgba(0,0,0,0.2);
            position: relative;
        }

        .brand {
            font-size: 18px;
            font-weight: bold;
            margin: 0;
        }

        .main-title h1 {
            font-size: 38px;
            line-height: 1.1;
            margin-top: 50px;
            margin-bottom: 30px;
            font-weight: 800;
            text-transform: uppercase;
        }

        .subtitle {
            font-size: 18px;
            line-height: 1.4;
            margin-bottom: 20px;
        }

        .footer {
            margin-top: auto;
            display: flex;
            justify-content: space-between;
            align-items: flex-end;
            border-top: 1px solid rgba(255, 255, 255, 0.2);
            padding-top: 20px;
        }

        .special-edition {
            font-size: 16px;
            font-weight: bold;
            margin-bottom: 8px;
            text-transform: uppercase;
        }

        .author-name {
            font-size: 20px;
            font-weight: bold;
            margin: 0;
            text-transform: uppercase;
        }

        .author-photo {
            width: 100px;
            height: 120px;
            border: 3px solid white;
            background-color: #eee;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }

        .author-photo img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
    </style>
</head>
<body>

    <div class="book-cover">
        <div class="header">
            <p class="brand">SEC Insights</p>
        </div>
        
        <div class="main-title">
            <h1>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</h1>
        </div>

        <div class="subtitle">
            <p>Deep Dive in HTML, CSS & JS Basics<br>
            Top seller of 2025</p>
        </div>

        <div class="footer">
            <div class="footer-text">
                <p class="special-edition">SPECIAL EDITION</p>
                <p class="author-name">Mr. SUNIL KUMAR R</p>
            </div>
            <div class="author-photo">
                <img src="PM.jpeg" alt="SUNIL KUMAR R">
            </div>
        </div>
    </div>

</body>
</html>

## OUTPUT:
![WhatsApp Image 2025-12-26 at 6 40 59 PM](https://github.com/user-attachments/assets/89ce59a7-b0e6-4165-9a20-5cc0265eedee)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
