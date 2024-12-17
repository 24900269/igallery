# Ex.08 Design of Interactive Image Gallery
## Date:17/12/2024

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
<html>
    <title>
        Interactive Image Gallery
    </title>
    <style>
        body 
        {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 0;
            background-size: cover;
            background-image: url("https://png.pngtree.com/thumb_back/fh260/background/20220705/pngtree-fire-flame-and-blue-background-hd-image_1416594.jpg");
        }

        h6 
        {
            margin-top: 20px;
            color: red;
            font-size: xx-large;
            font-style: bold;
        }

        .Gallery
         {
            display: flex;
            gap: 15px;
            max-width: 800px;
            margin-top: 20px;
            justify-content: center;
        }
    </style>

    <body>
        <h6>MY WINGS</h6>
        <div class="Gallery">

            <img src="https://w0.peakpx.com/wallpaper/880/47/HD-wallpaper-mt-15-motorcycle-motor-sport-bike-thumbnail.jpg" width="400" height="400" onclick="openImage(this.src)">
            <img src="https://pbs.twimg.com/media/Fs9gApIXoAI7paW?format=jpg&name=4096x4096" width="300" height="300" onclick="openImage(this.src)">
            <img src="https://i.pinimg.com/736x/93/68/d7/9368d79cfe11b28e38060b2aecb8968d.jpg" width="500" height="500" onclick="openImage(this.src)">
            <img src="https://krazyhorse.co.uk/cdn/shop/products/mv-brutale-21-1000-nurburgring-racing-kit-front-right-3q_2000x.jpg?v=1633945360" width="300" height="300" onclick="openImage(this.src)">
            <img src="https://kickstart.bikeexif.com/wp-content/uploads/2023/07/ducati-st3-cafe-racer-jerem-motorcycles-4.jpg" width="400" height="400" onclick="openImage(this.src)">
            
        </div>

        <script>
            function openImage(src) {
                window.open(src, "_blank");
            }
        </script>
    </body>
</html>



```
## OUTPUT:
![alt text](<Screenshot (19).png>)
![alt text](<Screenshot (20).png>)
## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
