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

<!DOCTYPE html>
<html>
  <head>
    <title>BOOK COVER PAGE</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <div class="page">
      <div class="insights">SEC Insights</div>

      <hr class="hr">

      <div class="title">
        LOGICS FOR<br>PROGRAMMING
      </div>

      <div class="subtitle">
        <i>BUILD LOGICS SO THAT IT FEELS<br>FUN TO CODE</i>
      </div>

      <div class="edit">
        LIMITED EDITION<br>BEST SELLER
      </div>

      <hr>

      <div class="name">SUJAL DAS</div>

      <div class="bottom">SEC</div>

      <div class="pic"></div>
    </div>
  </body>
</html>

STYLE.CSS


body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
 
}

.page {
  width: 400px;
  height: 600px;
  background-image: url("manifestation.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  border: 10px solid black;
  padding: 20px;
  box-sizing: border-box;
  background-clip: padding-box;
  position: relative;
  color: white;
  text-align: center;
}

.insights {
  font-size: 18px;
  font-weight: bold;
  margin-bottom: 20px;
}

.hr {
  width: 120px;
  margin: 0 auto 20px auto;
}

.title {
  font-size: 40px;
  font-weight: bold;
  margin: 13px 0 15px 0;
}

.subtitle {
  font-size: 18px;
  margin-bottom: 40px;
}

.edit {
  font-size: 19px;
  font-weight: bold;
  margin-top: 205px;
}

.name {
  font-size: 17px;
  font-weight: bold;
  margin-top: 10px;
}

.bottom {
  position: absolute;
  bottom: 20px;
  right: 20px;
  font-weight: bold;
}

.pic {
  position: absolute;
  bottom: 80px;
  left: 73%;
  width: 80px;
  height: 85px;
  background: url("PROFFESIONAL_IMG.jpg") no-repeat center/cover;
}


```


## OUTPUT:
![alt text](<sujal/bookapp/static/Screenshot 2025-10-15 140124.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
