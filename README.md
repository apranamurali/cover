# Ex.06 Book Front Cover Page Design
## Date:

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
<html>
 <head>
       <meta name="viewport"
          content="width=device-width, initial-scale=1.0">
          <style>

         .bookpage{
              width: 400px;
              height: 600px;
              color:rgba(243, 195, 195, 0.938)00, 17, 17;
              margin-left : auto;
              margin-right : auto;
              padding: 20px;

              font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
              background-image: url("BOOKBG.jpg");
              background-size: cover;
              }
             .insight{
                color:rgb(36, 133, 197);
              }

             .hrstyle{
             width:100px;
             }
             .author{
             display: inline;
             position: relative;
             color:rgba(220, 159, 16, 0.767);
             top:240px;

             font-family:Georgia;
             font-size: medium;
             }
             .booktitle{
             font-family: 'Courier New',Courier,monospace;
             font-size: larger;
             text-align: center;
             position: relative;
             top: 30px;
              color:rgb(255, 255, 255);
             
             }
             .id {
             width:400px;
             position: relative;
             top:250px;
             }
             .pub{
             font-size: medium;
             position: relative;
             top:204px;
             left:350px;
              color:rgb(36, 133, 197);
             }
             .ed{
              color:rgb(36, 133, 197);
             font-size: medium;
             font-family: Verdana;
             position:relative;
             top:150px;
             }
             .subtitle{
             font-family:Tahoma;
             font-size: large;
             position:relative;
             top:40px;
             color:rgb(255, 255, 255);
             }
             .mypic{
             position:relative;
             top:200px;
             left: 275px;
             width: 100px;
             height: 100px;
             background-size:cover;
             }
             </style>
             <title>Book Cover Page</title>
             </head>
             <body>
             <div class="bookpage">
             <div class="insight">
               DV PUBLICATION
             </div>
             <div class="hrstyle">
                <hr style="color: rgb(159, 223, 217);">
             </div>
             <div class="booktitle">
                <h1><b>DEVELOPMENT OF MASK </b></h1>
            </div>
             <div class="subtitle">
               EASY WAY TO LEARN WEB DEVELOPMENT
             </div>
             <div class ="mypic">
               <img src="aparna.jpg" width="130" height="145" alt="">
             </div>
             <div class="id">
             <hr style="color: rgb(252, 0, 0);">
             </div>
             <div class="author">
             <p><b>APARNA</b></p>
            </div>
             <div class="pub">
             SEC
             </div>
             <div class="ed">
             <b>FULL EDITION</b>
          </div>
    </body>
</html>
```

## OUTPUT:

<img width="1290" height="1083" alt="Screenshot 2025-11-19 162241" src="https://github.com/user-attachments/assets/2fbf8dd2-daeb-4f1c-a18f-b95af1aace65" />

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
