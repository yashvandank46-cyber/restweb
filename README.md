# Ex.07 Restaurant Website
## Date:08/10/2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home.html
<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="home.css"> 
    </head>
    <body>
        <nav>
            <a  href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </nav>
        <div class="name">
            <h1>"SPARK RESTAURANT</h1>
            <b>"Your journey to flavor starts here"</b>
            
        </div>
        <div class="offer">
            <h2>Special Offers:</h2>
            <h3>"Free desert with Every Meal Above $499!"</h3>
        </div>
        <footer>
            <h6 class="bottom">&copy;YASHVANDAN K(25017523)</h6>

        </footer>
    </body>
</html>

home.css
*{
    margin: 0;
    border: 0;
}

body{
    background-image:url("back.webp");
    background-position: center;
    background-size:cover;
    width: 100%;
    background-color: rgb(252, 93, 24);
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    color: rgb(11, 11, 11);
}

a{
    padding: 15px;
    color:rgb(20, 195, 14);
}
a:hover{
    background-color: rgb(15, 14, 14);
    color:rgb(237, 67, 15);
}
.name{
    text-align: center;
    position: relative;
    left: 500px;
    font-weight: bolder;
    font-family: 'Times New Roman', Times, serif;
    color: rgba(10, 9, 9, 0.855);
    font-size: 40px;
    width: 1000px;
    background-color: rgba(251, 246, 246, 0.94);
}
.offer{
    text-align: right;
    font-size: 40px;
    color: rgb(218, 218, 17);
    position: relative;
    right: 100px;
    top:400px;

}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 550px;
    background-color: rgb(232, 248, 11);
}

.navbar{
    background-color: rgb(0, 0, 0);
    height: 50px;
    width: 100%;
    position: fixed;
    top: 0;
    left: 0;
    opacity: 0.8;
}
menu.html
<html>
    <head>
        <title>Menu</title>
        <link rel="stylesheet" href="menu.css">
    </head>
    <body>
        <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contanct</a>
        </nav>
        <h1>Menu Lists</h1>
        <div class="main">
            
            <div class="food1">
                <img src="fried-rice.jpg"alt="pic">
                <b>FRIED RICE -$20</b>
            </div>
            <div class="food2">
                <img src="Chicken-65 1.jpg" alt="pic">
                <b>CHICKEN 65-$15</b>
            </div>
            <div class="food3">
                <img src="noodles 1.jpg" alt="pic">
                <b>NOODLES-$50</b>
            </div>
            <div class="food4">
                <img src="pasta 1.jpg" alt="pic">
                <b>PASTA -$60</b>
            </div>
            <div class="food5">
                <img src="pizza 1.jpg" alt="pic">
                <b>PIZZA-$30</b>
            </div>
            <div class="food6">
                <img src="shawarma 1.avif" alt="pic">
                <b>SHAWARMA-$40</b>
            </div>
            <div class="food7">
                <img src="Porotta 1.jpg" alt="pic">
                <b>POROTTA-$30</b>
            </div>
            <div class="food8">
                <img src="chappati 1.jpg" alt="pic">
                <b>CHAPATHI-$40</b>
            </div>
            <div class="food9">
                <img src="burger 1.jpg" alt="pic">
                <b>BURGER-$50</b>
            </div>
            <div class="food10">
                <img src="tandoori 1.jpg" alt="pic">
                <b>TANDOORI-$40</b>
            </div>
            <div class="food11">
                <img src="dosa 1.jpg" alt="pic">
                <b>DOSA-$40</b>
            </div>
            <div class="food12">
                <img src="idly 1.jpg" alt="pic">
                <b>IDLY-$40</b>
            </div>
        </div>
        <footer>
            <h6 class="bottom">YASHVANDAN K (25017523)</h6>

        </footer>
    </body>
</html>

menu.css
body{
    
    background:url("back1.jpg");
    background-repeat: no-repeat;
    background-position:center;
    background-size: cover;
    font-size: 20px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    margin: auto;
    overflow: hidden;
}
.main{
    display: grid;
    grid-template-columns: repeat(5,1fr);
}
a{
    color:rgb(229, 243, 38);
    position: relative;
    left: 1200px;
}
.food1{
    padding: 10px;
    background-color: rgba(245, 14, 37, 0.993);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 30px;
    left: 80px;
}
.food2{
    padding: 10px;
    background-color: rgba(243, 9, 9, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 30px;
    left: 80px;
    
}
.food3{
    padding: 10px;
    background-color: rgba(246, 28, 9, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 20px;
    left: 80px;
}


.food4{
    padding: 10px;
    background-color: rgba(245, 16, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 20px;
    left: 80px;
    
}
.food5{
    padding: 10px;
    background-color: rgba(255, 37, 8, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    bottom: 20px;
    
}
.food6{
    padding: 10px;
    background-color: rgba(244, 4, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food7{
    padding: 10px;
    background-color: rgba(247, 57, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food8{
    padding: 10px;
    background-color: rgba(239, 39, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food9{
    padding: 10px;
    background-color: rgba(250, 32, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food10{
    padding: 10px;
    background-color: rgba(252, 25, 9, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food11{
    padding: 10px;
    background-color: rgba(252, 25, 9, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
}

.food12{
    padding: 10px;
    background-color: rgba(252, 25, 9, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
}

img{
    width: 150px;
    height: 100px;
    border: solid rgb(4, 4, 4) 6px;
}
h1{
    text-align: center;
    position: relative;
    bottom: 10px;
    color: rgb(12, 226, 30);

}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 30px;
    background-color: rgb(179, 237, 7);
}
.food11,.food12{
    top:30px;
}

admin.html
<html>
    <head>
        <title>Admin</title>
        <link rel="stylesheet" href="admin.css">
    </head>
    <body>
        <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contanct</a>
        </nav>
        <h1>Administration</h1>
        <div class="admin">
            <div class="a1">
                <img src="batman.webp">
                <br>
                <b>KAV</b><br>
                <b>CEO</b>
            </div>
            <div class="a2">
                <img src="benten.webp">
                <br>
                <b>HARI</b><br>
                <b>Manager</b>
            </div>
            <div class="a3">
                <img src="bheem.jpg">
                <b>SACHIN</b><br>
                <b>Chief</b>
            </div>
            <div class="a4">
                <img src="doraemon.jpg">
                <br>
                <b>SIVA </b><br>
                <b>Assistant Chief</b>
            </div>
            <div class="a5">
                <img src="kaliya.jpg">
                <b>SENTHIL</b>
                <br>    
                <b>Accounts Manager</b>
            </div>
            <div class="a6">
                <img src="raju.png">
                <br>
                <b>GUNA</b>
                <br>
                <b>Assistant Manager</b>
            </div>
        </div>
        <footer>
            <h6 class="bottom">YASHVANDAN K(25017523)</h6>

        </footer>
    </body>
</html>

admin.css
body{
    background-image:url("back2.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
a{
    padding: 15px;
    color:rgb(251, 9, 9);
    position: relative;
    left: 1100px;
    top: 20px;
    font-size: 20px;
    font-size: x-large;
}
.admin{
    display: grid;
    grid-template-columns: repeat(6,1fr);
    font-size: 20px;
    gap:10px;
}
img{
    width: 210px;
    height: 300px;
    border:solid 5px rgb(240, 235, 235);
}
.a1,.a2,.a3,.a4,.a5,.a6{
    padding: 5px;
    background-color: rgb(221, 209, 209);
    text-align: center;
    font-size: 24px;
    
}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 60px;
    width:100%;
    color:white;
}
h1{
    text-align: center;
    color:rgb(250, 21, 21);
    font-size: 40px;
}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 110px;
    background-color: brown;
    width: 2000px;
}

contact.html
<html>
    <head>
        <title>Contact</title>
        <link rel="stylesheet" href="contact.css">
    </head>
    <body>
         <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contanct</a>
        </nav>
        <div class="contanct-container">
            <h1>Contact:</h1>
            <h4>Address:saveetha engneering college,chennai </h4>
            <h2>Phone no: 9876543210</h2>
            <h3>Email:spark@gmail.com</h3>
        </div>
        <footer>
            <h6 class="bottom">YASHVANDAN K(25017523)</h6>

        </footer>
    </body>
</html>

contact.css

body{
    background-image:url("back3.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    font-size: 20px;
}

a{
    padding: 15px;
    color:rgb(246, 66, 11);
    position: relative;
    left: 1100px;
    top: 20px;
    font-size: 20px;
}
.bottom{
    font-size: 30px;
    text-align: center;
    background-color: rgba(37, 0, 0, 0.768);
    position: relative;
    top: 150px;
    color: white;
}
.contanct-container{
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    text-align: center;
    padding: 30px;
    background-color: rgb(251, 246, 246);
    height:400px;
    width:410px;
    display: block;
    gap: 20px;
    font-size: 20px;
    position: relative;
    left: 600px;
    top:20px;
    border-radius: 10%;
}
h2,h3,h4{
    font-size: 27px;
}
```




## OUTPUT:
![alt text](<Screenshot 2025-10-08 223017.png>)
![alt text](<Screenshot 2025-10-08 223031.png>)
![alt text](<Screenshot 2025-10-08 223048.png>)
![alt text](<Screenshot 2025-10-08 223141.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
