# Ex.05 Design a Website for Server Side Processing
## Date:08/04/2024

## AIM:
To design a website to find surface area of a Right Cylinder in server side.

## FORMULA:
Surface Area = 2Πrh + 2Πr<sup>2</sup>
<br>r --> Radius of Right Cylinder
<br>h --> Height of Right Cylinder

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<html>
<head>
<meta charset='utf-8'>
<meta http-equiv='X-UA-Compatible' content='IE=edge'>
<title>Area of prism</title>
<meta name='viewport' content='width=device-width, initial-scale=1'>
<style type="text/css">
body 
{
background-color:#030312;
}
.edge {
width: 1440px;
margin-left: auto;
margin-right: auto;
padding-top: 250px;
padding-left: 300px;
}
.box {
display:block;
border: Thick dashed rgb(208, 225, 225);
width: 500px;
min-height: 300px;
font-size: 20px;
background-color:#bf1736;
}
.formelt{
color:#020705;
text-align: center;
margin-top: 7px;
margin-bottom: 6px;
}
h1
{
color:#020705;
text-align: center;
padding-top: 20px;
}
</style>
</head>
<body>
<div class="edge">
<div class="box">
<h2 align="center"> <font color="yellow"> Surface Area of Right Cylinder </font> </h2>
<center><font color="orange">THIRUMALAI V<font></center>
<center>(212223040229) </center>
<form method="POST">
{% csrf_token %}
<div class="formelt">
Radius : <input type="text" name="radius" value="{{r}}"></input>(in m)<br/>
</div>
<div class="formelt">
Height : <input type="text" name="height" value="{{h}}"></input>(in m)<br/>
</div>
<div class="formelt">
<input type="submit" value="Calculate"></input><br/>
</div>
<div class="formelt">
Area : <input type="text" name="surf_area" value="{{surf_area}}"></input>m<sup>2</sup><br/>
</div>
</form>
</div>
</div>
</body>
</html>
```
## SERVER SIDE PROCESSING:
![Screenshot 2024-04-08 135220](https://github.com/Thirumalai23013035/MathServer/assets/153185249/36065609-59ce-4517-b973-e55fc8981a6d)


## HOMEPAGE:

![Screenshot 2024-04-08 135204](https://github.com/Thirumalai23013035/MathServer/assets/153185249/ef48a834-41aa-4d77-98eb-82aeeba2e305)


## RESULT:
The program for performing server side processing is completed successfully.
