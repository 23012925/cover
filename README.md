# Ex.06 Book Front Cover Page Design
## Date:28-04-2005

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
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cover</title>
    <style>
        main{
            height: 100vh;
            width: 35%;
            margin: auto;
            background-color: #3e0bc059;
            position: relative;
            
            /* #93c36d */
        }
        section{
            color: rgb(6, 18, 6);
            position: absolute;
            bottom: 10%;
            right: 5%;
        }
        section h1{
            font-family: 'Copperplate Gothic Light';
            font-size: 4rem;
            margin: 12px;
            margin-left: 0%;
            font-weight:lighter;
        }
        section p{
            font-family: sans-serif;
            font-size: 1.25rem;
            margin: 2px;
            margin-left: 0%;
        }
        #auth{
            font-style: italic;
        }
        .rect{
            background-color: #b2dc2b;
            height: 30px;
            margin-top: 20px;
            width: 100%;
        }
        img{
            height: 200px;
            position: absolute;
            top: 8%;
            right: 10%;
        }
    </style>
</head>
<body>
    <main>
        <img style="border-radius: 30%" src="jana.jpg" alt="">

        <section>
            <p id="auth">By Janarthanan K</p>
            <h1>THE</h1>
            <h1>DESIGN</h1>
            <h1>HUSTLE</h1>
            <p>Tips & Tricks For</p>
            <p>Design Enterpreneurs</p>
            <div class="rect"></div>
        </section>
    </main>
</body>
</html
```

## OUTPUT:

![cover_page](https://github.com/23012925/cover/assets/150931013/2b4053c7-a7f8-4212-9fbe-3cf3a9e7ea67)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
