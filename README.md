# Ex04 Places Around Me
## Date: 22/04/2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html
    <html>
    <center>
    <h1 style="background-color: aquamarine; font-size:xx-large;">VANDAVASI </h1>

<img src="vadhavasi.web.jpg" usemap="#image-map">
</center>
<map name="image-map">
    <area target="" alt="mambadu" title="mambadu" href="mambadu.html" coords="176,167,243,211" shape="rect">
    <area target="" alt="temple" title="temple" href="temple.html" coords="225,71,84" shape="circle">
    <area target="" alt="sembur" title="sembur" href="sembur.html" coords="281,229,345,281" shape="rect">
    <area target="" alt="ponnur hill" title="ponnur hill" href="ponnur hill.html" coords="60,171,115,178,94,108,15,120,16,145" shape="poly">
    <area target="" alt="kodanallur" title="kodanallur" href="kodanallur.html" coords="429,348,64" shape="circle">
</map>
</html>
mambadu.html
     <!DOCTYPE html>
<html>
    <head>
        <center><h1 style="background-color: rgb(105, 255, 205);">FAMOUS<br>TEMPLES IN VANDAVASI</h1><HR></center>
    </head>
    <center>
        <table style="background-color: blanchedalmond;">
            <tr>
                <th><h2>sri abirami amman temple</h2><img src="tem 1.webp" width="250px" height="250px"></th>
                <th><h2>sri panduranga temple </h2><img src="tem 2.webp"  width="250px" height="250px"></th>
                <th><h2>anjaneyar temple</h2><img src="tem 3.jpg"  width="250px" height="250px"></th>
                <th><h2>thavalagiriswarar temple</h2><img src="tem 4.jpg"  width="250px" height="250px"></th>
            </tr>
        </table>
    </center>
</html>
ponnur hill.html
          <!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Restaurant</title>
</head>
<style>
    body {background-image: url(html.png);
        background-size: cover;
        background-repeat: 1;
        
        
    }
</style>
<body>
   
   <h1 style="text-align: center;background-color: bisque;">GOURMET<br>HAVEN</br></h1>
   <h2 style="text-align: center;">&mdash; menu &mdash;</h2>
   <center>
<table>
    <tr>
        <td><img src="food 1.jpg" style="height: 250px;width: 200px;"><br></br></td>
        <td><img src="food 3.jpg" style="height: 250px;width: 200px;"><br></br></td>
        <td><img src="food 2.jpg" style="height: 250px;width: 200px;"><br></br></td>
        <td><img src="food 4.jpg" style="height: 250px;width: 200px;"><br></br></td>
        <td><img src="food 5.jpeg" style="height: 250px;width: 200px;"><br></br></td>
    </tr>
</center>
<tr>
    <td><h3><center>CHICKEN BRIYANI<br>perfectly spiced,tender chicken layered with fragrant</center></h3></td>
    <td><h3><center>TANDOORI CHICKEN<br>serve with refreshinng raita, tangy lemon wedges</center></h3></td> 
    <td><h3 ><center>CHICKEN NOODLES<BR>hoisin noodles-chicken breast and vegetables with egg</center></h3></td>
    <td><h3 ><center>CHICKEN BURGER<br>cheeseburger with chicken cutlet,added "zing" for extra heat</center></h3></td> 
    <td><h3><center>LEMON PEPPERCHICKEN<BR>from family classics to gourmet masterpieces our 'tasty treats'</center></h3></td>  
</tr>
</table>
<hr>
<h1>CONTACT</h1>
<h2>+918940031086 | gourmethaven@gmail.com |www.gourmethaven.com</h2>
</body>
</html>
sembur.html
       <!DOCTYPE html>
<html>
    <head>
    <body>
        <center>
            <h1 style="background-color: rgb(226, 122, 160);">TEXTILE SHOPS</h1>
           
        </center>
    <center>
    </head>

        <table style="background-color: antiquewhite;">
        <tr>
        <th><h2>RAJA RANI</h2><img src="dress 1.webp" height="250px" width="250px"> <h3>Address: GJ43+G9P, Vandavasi, Tamil Nadu 604408
            Hours: 
            Open ⋅ Closes 9 pm
            Phone: 04183 227 786</h3></th>
        <th><h2>ANNAMALAI</h2><img src="dress 2.jpg" height="250px" width="250px"><h3>Address: FHXR+7XH, Tiruvannamalai - Kanchipuram Rd, Vandavasi, Tamil Nadu 604408
            Hours: 
            Open ⋅ Closes 8 pm
            </h3></th>
        <th><h2>CHAKKARAVARTHY</h2><img src="dress 3.webp" height="250px" width="250px"><h3>Address: 11A, Bazaar Street Near Old Bus Stop, Vandavasi, Tamil Nadu 604408
            Hours: 
            Open ⋅ Closes 10:30 pm
            </h3></th>
        <th><H2>MAMTHA</H2><img src="dress 4.jpg" height="250px" width="250px"><h3>Service options: Offers same-day delivery
            Address: Vandavasi, Tamil Nadu 604408
            Hours: 
            Open ⋅ Closes 9:30 pm</h3>
            </th> 
        </tr>
        </table>
    </center>
</html>
temple.html
       <!DOCTYPE html>
<html>
    <head>
        <center>
    
        <h1 style="background-color: rgb(118, 104, 85);"> ZANA COSMETICS</h1>
        
        </center>
        

    
    <body>
    
    <h2>People use cosmetics to keep clean and enhance their beauty. These products range from lipstick and nail polish to deodorant, perfume, hairspray, shampoo, shower gel, tattoos, hair adhesives, hair removal products, hair dyes, most soaps, some tooth whiteners, and some cleansing wipes.</h2>
    <center>
    <table style="background-color: bisque;">

    
    <tr>
        <td><img src="cos 1.webp" style="height: 250px;width: 200px;"></td>
        <td><img src="cos 4.webp" style="height: 250px;width: 200px;"></td>
        <td><img src="cos 2.avif" style="height: 250px;width: 200px;"></td>
        <td><img src="cos 3.webp" style="height: 250px;width: 200px;"></td>
        <td><img src="cos 5.avif" style="height: 250px;width:200px;"></td>

    </tr>
</center>

    <tr>
     <td>ILIA True Skin Serum Foundation
        A hybrid beauty product that combines makeup and skincare </td>  
        <td>100% PURE
            A brand that creates all-natural cosmetics, skincare, and beauty products that are formulated with antioxidants, vitamins, and essential oils </td>
            <td>100% PURE
                A brand that creates all-natural cosmetics, skincare, and beauty products that are formulated with antioxidants, vitamins, and essential oils </td> 
                <td>Giorgio Armani Luminous Silk Foundation
                    A 100% natural foundation that contains at least 71% organic ingredients</td>
                    <td>Maybelline Fit Me Matte + Poreless Liquid Foundation
                        A lightweight liquid foundation that provides a matte finish and is suitable for normal and oily skin </td>
    </tr>
    </table> 
   <hr>
   <h1>contacts</h1>
   <br>
   5.0
(12) · Cosmetics store
3/33, Perumal Koil Street
Closed ⋅ Opens 7:30 am Mon
In-store shopping<br>
ph:8838512605/email:zanacosmetics@gmail.com
     
    </body>
    </head>
</html>

```

## OUTPUT
![alt text](<Screenshot (52).png>)
![alt text](<Screenshot (56).png>)
![alt text](<Screenshot (53).png>)

![alt text](<Screenshot (55).png>)
![alt text](<Screenshot (54).png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
