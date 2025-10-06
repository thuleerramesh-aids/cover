# Ex.06 Book Front Cover Page Design
# Date:06.10.2025
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

# PROGRAM:
```
cover.html:
<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
	<link rel="stylesheet" href="cover.css">
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,600;1,600&display=swap"
		rel="stylesheet">
</head>

<body>
	<div class="bookcover">
		<div class="top">
			<p><u>SEC Insights</u></p>
		</div>

		<div class="heading">
			<p>FUNDAMENTALS OF WEB APPLICATION</p>
		</div>

		<div class="text">
			<p>Deep Dive in HTML, CSS and JS</p>
			<p>Top seller of 2025</p>
		</div>

		<div class="img">
			<img src="image1.jpg" width="150px" height="130px">
			
		</div>
		
		<div class="bottom">
			<p>Special Edition</p>
			<hr>
			<p>STEVE JOBS</p>
		</div>




	</div>

</body>

</html>

cover.css:

*{
    font-family: "Montserrat", sans-serif;
    font-style: normal;
    
 
}


.bookcover{
    width: 600px;
    height: 675px;
    margin: 0 auto;
    border: solid;
    border-color: rgb(150,150,150);
    background-image: url("image.jpg");
    background-repeat: no-repeat;
    background-size: fill;
    background-position: center;
  

}

.top{
    margin-bottom: 60px;
    padding-left: 20px;
    padding-right: 20px;
}

.heading{
    font-size: 40px;
    text-align: center;

    margin-bottom: 60px;
}

.text{
    line-height: 0.5px;
    padding-left: 20px;
    padding-right: 20px;
   margin-bottom: 190px;
}

.bottom{
    vertical-align: bottom;
    display: inline-block;
    margin-right: 160px;
    padding-left: 20px;
    line-height: 0.5px;
}

.img{
    margin-left:420px;
    border: soild;
    border-color: white;
}

```
# OUTPUT:
<img width="488" height="548" alt="Screenshot 2025-10-06 211947" src="https://github.com/user-attachments/assets/2bbc4052-e313-4435-9cad-352926cc8ce2" />


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
