# Ex.07 Restaurant Website
## Date:08-10-2025

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
homepage.html
<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="homepage.css"> 
    </head>
    <body>
        <nav>
            <a  href="homepage.html">HOME</a>
            <a href="restmenu.html">MENU</a>
            <a href="restadmin.html">ADMIN</a>
            <a href="restcontact.html">CONTACT</a>
        </nav>
        <div class="name">
            <h1>KERALA CLASSIC RESTURANT</h1>
            <b>"From Field To Fork -Fresh Sea Food and Fresh vegetable from farm On Every Day"</b>
            
        </div>
        <div class="offer">
            <h2>Limited Offers</h2>
            <h3>Win the Game and get a 50% off Discount Coupon</h3>
        </div>
        <footer>
            <h6 class="bottom">Harikrishna.M (25013589)</h6>

        </footer>
    </body>
</html>

homepage.css

*{
    margin: 0;
    border: 0;
}

body{
    background-image:url(page1.jpg);
    background-position: center;
    background-size:cover;
    width: 100%;
    background-color: rgba(255, 106, 0, 0.767);
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    color: rgb(11, 87, 249);
}

a{
    padding: 15px;
    color:rgb(154, 4, 255);
}
a:hover{
    background-color: rgb(235, 172, 12);
    color:rgba(255, 5, 114, 0.727);
}
.name{
    text-align: center;
    position: relative;
    left: 290px;
    font-weight: bolder;
    font-family: 'Times New Roman', Times, serif;
    color: rgba(1, 144, 240, 0.855);
    font-size: 30px;
    width: 1000px;
    background-color: rgba(152, 250, 151, 0.94);
}
.offer{
    text-align: right;
    font-size: 40px;
    color: rgb(18, 18, 17);
    position: relative;
    right: 100px;
    top:200px;

}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 462px;
    background-color: rgb(232, 248, 11);
}
restadmin.html

<html>
    <head>
        <title>Admin</title>
        <link rel="stylesheet" href="restadmin.css">
    </head>
    <body>
        <nav>
            <a  href="pagehome.html">Home</a>
            <a href="restmenu.html">Menu</a>
            <a href="restadmin.html">Admin</a>
            <a href="restcontact.html">Contanct</a>
        </nav>
        <h1>Administration</h1>
        <div class="admin">
            <div class="a1">
                <img src="CEO.jpg">
                <b>Vijay Sathupathi
                </b>
                <b>CEO</b>
            </div>
            <div class="a2">
                <img src="mmanager.jpg">
                <b>Vijay</b>
                <b>MANAGER</b>
            </div>
            <div class="a3">
                <img src="1234.jpg">
                <b>Cillian Murphy</b>
                <b>Service Manager</b>
            </div>
            <div class="a4">
                <img src="manager.jpg">
                <b>Surya</b><br>
                <b>One of the Partmer</b>
            </div>
            <div class="a5">
                <img src="12345.jpg">
                <b>Dwayne Johnson</b>
                <b>Accounts Manager</b>
            </div>
            <div class="a6">
                <img src="Screenshot 2025-10-05 072210.png">
                <b>Harikrishna</b>
                <b>Maintenance Manager</b>
            </div>
        </div>
        <div class="foot">
            <h6 class="bottom">Harikrishna.M (25013589)</h6>

        </div>
    </body>
</html>
restadmin.css


body{
    background-image:url(image.jpg);
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
    background-color: rgb(165, 232, 8);
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

restmenu.html

<html>
    <head>
        <title>Menu</title>
        <link rel="stylesheet" href="restmenu.css">
    </head>
    <body>
        <nav>
            <a  href="homepage.html">Home</a>
            <a href="restmenu.html">Menu</a>
            <a href="restadmin.html">Admin</a>
            <a href="restcontact.html">Contanct</a>
        </nav>
        <h1>Menu Lists</h1>
        <div class="main">
            
            <div class="food1">
                <img src="food1.jpg"alt="pic">
                <b>Puttu and kadala curry</b>
            </div>
            <div class="food2">
                <img src="food2.jpg" alt="pic">
                <b>Appam and stew</b>
            </div>
            <div class="food3">
                <img src="food3.avif" alt="pic">
                <b>Palada payasam</b>
            </div>
            <div class="food4">
                <img src="food4.jpg" alt="pic">
                <b>Thalassery biryani</b>
            </div>
            <div class="food5">
                <img src="food5.jpg" alt="pic">
                <b>Meen Pollichathu</b>
            </div>
            <div class="food6">
                <img src="food6.jpg" alt="pic">
                <b>Pathiri</b>
            </div>
            <div class="food7">
                <img src="food7.jpg" alt="pic">
                <b>Banana fritters</b>
            </div>
            <div class="food8">
                <img src="food8.avif" alt="pic">
                <b>Idiyappam</b>
            </div>
            <div class="food9">
                <img src="food9.jpg" alt="pic">
                <b>Kappa and fish curry</b>
            </div>
            <div class="food10">
                <img src="FOOD10.jpg" alt="pic">
                <b>PRON BRIYANI</b>
            </div>
        </div>
        <footer>
            <h6 class="bottom">Harikrishna.M (25013589)</h6>

        </footer>
    </body>
</html> 
restmenu.css

body{
    
    background:url(page2.jpg);
    background-repeat: no-repeat;
    background-position:center;
    background-size: cover;
    font-size: 20px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    margin: auto;
}
.main{
    display: grid;
    grid-template-columns: repeat(5,1fr);
}
a{
    color:rgba(108, 222, 155, 0.994);
    position: relative;
    left: 1200px;
}
.food1{
    padding: 10px;
    background-color: rgba(14, 14, 245, 0.993);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 30px;
    left: 80px;
}
.food2{
    padding: 10px;
    background-color: rgba(98, 108, 244, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 30px;
    left: 80px;
    
}
.food3{
    padding: 10px;
    background-color: rgba(245, 61, 153, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 20px;
    left: 80px;
}
.food4{
    padding: 10px;
    background-color: rgba(16, 246, 70, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 20px;
    left: 80px;
    
}
.food5{
    padding: 10px;
    background-color: rgba(8, 255, 210, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    bottom: 20px;
    
}
.food6{
    padding: 10px;
    background-color: rgba(36, 244, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food7{
    padding: 10px;
    background-color: rgba(4, 247, 28, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food8{
    padding: 10px;
    background-color: rgba(4, 223, 239, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food9{
    padding: 10px;
    background-color: rgba(4, 221, 250, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food10{
    padding: 10px;
    background-color: rgba(70, 252, 9, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}


img{
    width: 150px;
    height: 100px;
    border: solid rgb(173, 226, 26) 6px;
}
h1{
    text-align: center;
    position: relative;
    bottom: 10px;
   
    color: rgb(46, 36, 220);

}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 50px;
    background-color: rgb(237, 212, 212);
}

restcontact.html

<html>
    <head>
        <title>Contact</title>
        <link rel="stylesheet" href="restcontact.css">
    </head>
    <body>
         <nav>
            <a href="homepage.html">Home</a>
            <a href="restmenu.html">Menu</a>
            <a href="restadmin.html">Admin</a>
            <a href="restcontact.html">Contanct</a>
        </nav>
        <div class="contanct-container">
            <h1>Contact Us:</h1>
            <h4>Address: Idukki 32/2,KERALA</h4>
            <h2>Phone no: 9442823567</h2>
            <h3>EMAIL: harikrishna.m180607@gmail.com</h3>
        </div>
        <footer>
            <h6 class="bottom">Harikrishna.M (25013589)</h6>

        </footer>
    </body>
</html>

restcontact.css


body{
    background-image:url(image.jpg);
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
    background-color: rgb(165, 232, 8);
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
![alt text](<static/Screenshot 2025-10-08 201050.png>)
![alt text](<static/Screenshot 2025-10-08 201103.png>)
![alt text](<static/Screenshot 2025-10-08 201256.png>)
![alt text](<static/Screenshot 2025-10-08 201313.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
