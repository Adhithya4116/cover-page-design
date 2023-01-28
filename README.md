# Book CoverPage Design

## AIM:

To design a static web site for a book cover page.

## DESIGN STEPS:

Step 1:
Clone the github repository and create a django admin interface

Step 2:
Write HTML and CSS for designing book cover page and execute them .

Step 3:
Validate the HTML and CSS code.

Step 4:
Publish the website in the given URL.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
{% load static %}
<html lang="en">

<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>coverpage</title>
   <link rel="stylesheet" href="static/css/cover.css">
   <style>
   main{
   background-color: rgb(58, 54, 54);
   background-image: url('static/images/book.png');
   height: 1000px;
   width:800px;
   margin-left: 500px;
}
   </style>
</head>
<body>
   <main>
       <h4>EXPERT INSIGHT</h4>
       <hr id="start" color="orange">
       <h1>
           Responsive Web <br>
           Design with <br>
           HTML5 and CSS
       </h1>
       <p>Develop future-proof responsive websites <br>
       using the latest HTML5 and CSS techniques</p>

       
       <p id="edision">THIRD EDISION</p>
       <hr id="aj" color="orange">
       <img src="static/images/ben.png" alt="sdfgh">
       
          <p id="author">Ben Frain</p>
           <p id="packt"> <u> Packt> </u></p>
   
   
   </main>
  
</body>
</html>>
```

## OUTPUT:

![212873939-f6e52add-2647-452a-93da-72e0aafcd9f5](https://user-images.githubusercontent.com/118707079/215283784-10451f28-95ee-4590-897a-047ed0f307bc.png)


## Result:
The program for designing book cover page using HTML and CSS is executed successfully

