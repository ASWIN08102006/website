# Ex.07 Restaurant Website
# Date: 06/12/2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
<html>
    <head>
        <title>Aswitha Restaurant</title>
    </head>
    <style>
        body {
            background-color: lightyellow; /* Set your desired background color here */
        }
        h1, ul {
            display: inline;
            padding: 20px;
        }
        h1 {
            margin-left: 10px;
        }
        nav {
            padding: 20px;
            background-color: gray; /* Missing semicolon fixed */
            color: white; /* Example text color */
        }
        li {
            display: inline;
            color: black;
            transition: 0.5s;
        }
        li:hover {
            color: orchid;
            cursor: pointer;
        }
        ul {
            margin-left: 80px;
        }
        .box {
            background-color: yellow;
            color: blueviolet;
            display: inline;
            margin-left: 35px;
            font-size: large;
        }
        input {
            padding: 20px;
            width: 50%;
            box-sizing: border-box; /* Include padding in width calculation */
        }
        .searchbar {
            display: flex;
            justify-content: center; /* Center the search bar */
            padding: 15px;
            margin-top: 20px; /* Add some space above the search bar */
        }
        h2 {
            text-align: center;
            font-size: 40px;
        }
        .img {
            display: inline-block;
            width: 420px;
            border-width: 2px;
            border-color: yellow;
            border-style: solid;
            margin-left: 30px;
        }
        .img:hover {
            background-color: yellow;
            color: black;
        }
        .info {
            margin-left: 35%;
            margin-right: 45%;
            border-width: 2px;
            border-style: double;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
    <body>
        <nav>
            <h3>Opening time 🕥: 11.00 am - 11.00 pm</h3>
            <h1 style="font-size: 80px;">Aswitha Restaurant</h1>
            <h5 style="display: inline;">&lpar;NONVEG&rpar;</h5>
            <img src="C:\Users\admin\Documents\WhatsApp Image 2024-10-17 at 10.06.30_b221dd09.jpg" width="200px" height="170px" style="margin-left: 85px;">
            <ul>
                <li>MENU |</li>
                <li>RATINGS |</li>
                <li>BLOG |</li>
                <li>COUPON |</li>
            </ul>
            <a class="box" href="C:\Users\admin\Desktop\HTML\Sub Codes\ordernow code.html">ORDER NOW!!!</a>
        </nav><br>

        <hr><br>
        <div class="searchbar">
            <input placeholder="Search"> 
        </div>
        
        <div>
            <h2>FOOD MENU</h2>
        </div>
        <div class="img">
            <img src="C:\Users\admin\Documents\WhatsApp Image 2024-10-17 at 09.49.27_5cc41b54.jpg" width="420px" height="300px"><br>
            <ol>
                <li style="word-spacing: 210px;">DISH                         PRICES</li><br>
                <li style="word-spacing: 145px;">Chicken_biryani                       200/-</li><br>
                <li style="word-spacing: 152px;">Mutton_biryani                       250/-</li><br>
                <li style="word-spacing: 126px;">Chicken_Fried_rice                     150/-</li><br>
                <li style="word-spacing: 145px;">Egg_Fried_rice                        120/-</li><br>
                <li style="word-spacing: 170px;">Egg_biryani                           180/- </li><br>
                <li style="word-spacing: 133px;">Chicken_Noodles                       150/-</li><br>
                <li style="word-spacing: 160px;">Egg_Noodles                           120/-</li><br>
                <li style="word-spacing: 120px;">Schezwan_Noodles                      130/-</li><br>
                <li style="word-spacing: 157px;">Mutton_curry                          100/-</li><br>
                <li style="word-spacing: 157px;">Chicken_curry                         90/-</li><br>
                <li style="word-spacing: 183px;">Egg_curry                             70/-</li>
            </ol> 
        </div>
        <div class="img">
            <img src="c:\Users\admin\Documents\WhatsApp Image 2024-10-17 at 10.39.33_14bf73a9.jpg" width="420px" height="300px"><br>
            <ol>
                <li style="word-spacing: 200px;">STARTER                     PRICES</li><br>
                <li style="word-spacing: 150px;">Chicken_spring_roll                 100/-</li><br>
                <li style="word-spacing: 195px;">Chilli_prawns                    130/-</li><br>
                <li style="word-spacing: 140px;">Chicken_manuchurian                     110/-</li><br>
                <li style="word-spacing: 222px;">Meatballs                     170/-</li><br>
                <li style="word-spacing: 188px;">Mutton_keema                         180/- </li><br>
                <li style="word-spacing: 215px;">Chicken_65                       80/-</li><br>
                <li style="word-spacing: 212px;">Mutton_85                           180/-</li><br>
                <li style="word-spacing: 211px;">sheek_kebab                      90/-</li><br>
                <li style="word-spacing: 198px;">cheese_omelete                          70/-</li><br>
                <li style="word-spacing: 139px;">Crispy_chicken_nuglets                        90/-</li><br>
                <li style="word-spacing: 245px;">Egg_65                             60/-</li>
            </ol>
        </div>
        <div class="img">
            <img src="c:\Users\admin\Documents\WhatsApp Image 2024-10-17 at 10.39.33_8467d48d.jpg" width="420px" height="300px"><br>
            <ol>
                <li style="word-spacing: 150px;">BEVERAGES                    PRICES</li><br>
                <li style="word-spacing: 175px;">Milkshakes                 100/-</li><br>
                <li style="word-spacing: 225px;">Tea                  130/-</li><br>
                <li style="word-spacing: 171px;">Cappuccino                     110/-</li><br>
                <li style="word-spacing: 204px;">Mojito                     170/-</li><br>
                <li style="word-spacing: 180px;">Lemonade                        180/- </li><br>
                <li style="word-spacing: 188px;">Ice_cream                       80/-</li><br>
                <li style="word-spacing: 172px;">Soft_drinks                           180/-</li><br>
                <li style="word-spacing: 185px;">Rose_milk                     90/-</li><br>
                <li style="word-spacing: 183px;">Fresh_juice                         70/-</li><br>
                <li style="word-spacing: 193px;">Mocktails                        90/-</li><br>
                <li style="word-spacing: 202px;">Desserts                            60/-</li>
            </ol>
        </div>
        <br><br>
        <hr><br>
        <footer>
            <nav>
                <div style="margin-left: 37%;">
                    Contact us: More information<br>  
                </div>
                <div class="info">   
                     +91 9939959945<br>
                     www.AswithaRestaurant.com<br>
                     123,anna nagar,chennai
                </div>
                <p><center>
                   Thank You Visit Again</center> 
                </p>
            </nav>
        </footer>
    </body>
</html>

```
# OUTPUT:
![image](https://github.com/user-attachments/assets/e4162e68-c005-494d-b168-6d1b869bf95a)
![image](https://github.com/user-attachments/assets/f84b5d96-99d0-43af-9a9c-c8ee76c466fc)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
