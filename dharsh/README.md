# Ex.08 Design of Interactive Image Gallery
## Date: 13.12.2024

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Disney Gallery</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Satisfy&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            background-color: #f9f9f9;
            color: #333;
        }

        h1 {
            font-family: 'Satisfy', cursive;
            font-size: 3em;
            margin: 20px;
            color: #ff6347;
            text-align: center;
        }

        h2 {
            font-family: 'Satisfy', cursive;
            color: #ff6347;
            font-size: 1.5em;
            margin-top: -10px;
        }

        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            max-width: 1200px;
            padding: 10px;
            justify-content: center;
        }

        .gallery-item {
            text-align: center;
            width: 200px;
            margin: 10px;
            border: 2px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            transition: transform 0.3s;
        }

     
        .gallery-item img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-bottom: 1px solid #ddd;
        }

        .gallery-item p {
            font-family: 'Satisfy', cursive;
            font-size: 1.3em;
            color: #555;
            padding: 10px 0;
            margin: 0;
        }

        .gallery-item:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body>
    <h1>Image Gallery</h1>
   
    
    <div class="gallery">
        <div class="gallery-item">
            <img src="cars.png" alt="Image 1">
            <p>Toothless</p>
        </div>
        <div class="gallery-item">
            <img src="monsters.png" alt="Image 2">
            <p>Monsters</p>
        </div>
        <div class="gallery-item">
            <img src="minions.png" alt="Image 3">
            <p>Minions</p>
        </div>
        <div class="gallery-item">
            <img src="ninja turtles.png" alt="Image 4">
            <p>Ninja Turtles</p>
        </div>
        <div class="gallery-item">
            <img src="cindrella.png" alt="Image 5">
            <p>Cinderella</p>
        </div>
        <div class="gallery-item">
            <img src="groot.png" alt="Image 6">
            <p>Groot</p>
        </div>
        <div class="gallery-item">
            <img src="cars.png" alt="Image 7">
            <p>Cars</p>
        </div>
        <div class="gallery-item">
            <img src="mermaid.png" alt="Image 8">
            <p>Little Mermaid</p>
        </div>
        <div class="gallery-item">
            <img src="kunfu panda.png" alt="Image 9">
            <p>Kung Fu Panda</p>
        </div>
        <div class="gallery-item">
            <img src="inside out.png" alt="Image 10">
            <p>Inside Out</p>
        </div>
        <div class="gallery-item">
            <img src="rt.png" alt="Image 11">
            <p>Ratatouille</p>
        </div>
        <div class="gallery-item">
            <img src="wall e.png" alt="Image 12">
            <p>Wall-E</p>
        </div>
    </div>
</body>
</html>
```

## OUTPUT:
![alt text](image.png)
![alt text](image-1.png)
## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.