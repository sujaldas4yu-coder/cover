# Ex.06 Book Front Cover Page Design
## Date:07.10.2025

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
COVER.HTML

<html>
    <head>
        <title>BOOK COVER PAGE
        </title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="page">
            
            <div class="insights">
                SEC Insights
            </div>
            <div class="hr">
                <hr>
            </div>
            <div class="title">
                UNTOLD TRUTHS ABOUT<br>MANIFESTATION
                
            </div>
            <div class="subtitle">
              
              <i align="center">U BECOME WHAT U THINK</i>
              
            </div>
            <div class="edit">
             LIMITED EDITION<br>BEST SELLER
             </div>
             <br><hr>
              <div class="name">
                SUJAL DAS
                </div>
                <div class="bottom">
                    SEC
                </div>
            <div class="pic">
            </div> 
        </div>
    </body>
</html>

STYLE.CSS

style.css
body{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}
.page{
    width: 400px;
    height: 600px;
    background-image:url(manifestation.jpg) ;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    border: 10px solid black ;
    padding:20px;
    box-sizing:border-box;
    background-clip: padding-box;
    position: relative;
}

.insights{
    font-size: 18px;
   font-weight: bold;
   margin-bottom: 20px;
   color:white;
}
.hr{
    color: white;
    width: 120px;
    right: 200%;
    

}
.title{
    font-size: 40px;
    margin: 13px 0 15px 0;
    font-weight: bold;
    text-align: center;
    color:white;
}
.subtitle{
    font-size: 18px;
    margin-bottom: 40px;
    color:white;
    text-align: center;
}
.edit{
    font-size: 19px;
    font-weight: bold;
    margin-top: 205px;
    color:white;
}
.name{
    font-size: 17px;
    font-weight: bold;
    margin-top: 10px;
    color:white;
   
}
.bottom{
    position: absolute;
    bottom: 20px;
    right: 20px;
    font-weight: bold;
    color:white;
}
.pic{
    position: absolute;
    bottom:80;
    left: 73%;
    width:80px;
    height:85px;
    background: url(PROFFESIONAL_IMG.jpg)  no-repeat;
    background-size: 80px;

}

```


## OUTPUT:
![alt text](<Screenshot 2025-10-07 111342.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
