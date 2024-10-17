# Ex04 Places Around Me
### NAME :V RAKSHA DHARANIKA
### REF NO:212223230167

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
### map code:
```html
<!DOCTYPE html>
    <html>
        <head>
            <title>MY CITY</title>
        </head>
        <body>
            <h1 align = "center">
              <font color="black "<b>velachery</b></font>
            </h1>
            <h3 align="center" style="font-family: Helvetica, sans-serif; color: lightcoral;">V RAKSHA DHARANIKA - 212223230167</h3>

            <center> 
                <img src="C:\Users\A.sathish\Downloads\WhatsApp Image 2024-10-17 at 10.56.21 AM.jpeg" usemap="#mycity" height ="613" width ="1300" >
            <map name = "mycity">
                <area shape="rect" coords="766,402,777,397"  href="my house"  title="my house in velachery">
                <area shape="rect" coords="771,248,819,247" href="mall" title="pheonix marketcity">
                <area shape="rect" coords="1478,43,1309,722" href="sea side" title="Coromandel Coast ">
                <area shape="rect" coords="1020,108,924,116" href="national park" title="guingy national park">
                <area shape="rect" coords="524,310,512,315" href="temple " title="Nanganallur Anjaneya Temple">
            </map>
        </center>
        </body>
    </html>

```
### MY house code:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>My house</title>
        <style>
            * {
                background-color: seashell;
            }
            h1 {
                text-align: center;
                color: firebrick;
            }
            h2 {
                text-align: center;
                color: forestgreen;
            }
            p {
                font-size: 16px;
                line-height: 1.5;
                color: midnightblue;
            }
        </style>
    </head>
    <body>
        <h1>Velachery</h1>
        <h2>my house in velachery</h2>
        <hr color="indianred">
        <h3>Description</h3>
        <p>
            I recently moved to Velachery, and my new house here feels like a perfect blend of city convenience and peaceful living. The area is bustling with activity, yet my home offers a quiet retreat from the noise. With everything from shopping malls like Phoenix Marketcity to green spaces like Guindy National Park nearby, I’ve quickly settled into the neighborhood. The connectivity is great, making it easy to get around Chennai. Though I've just shifted, Velachery already feels like home with its welcoming vibe and all the amenities I need just a stone’s throw away.
        </p>
    </body>
</html>


```
### mall code:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Mall</title>
        <style>
            * {
                background-color: beige;
            }
            h1 {
                text-align: center;
                color: coral;
            }
            h2 {
                text-align: center;
                color: darkgoldenrod;
            }
            p {
                font-size: 16px;
                line-height: 1.5;
            }
        </style>
    </head>
    <body>
        <h1>Velachery</h1>
        <h2>Phoenix Marketcity</h2>
        <hr color="crimson">
        <h3>Description</h3>
        <p>
            Phoenix Marketcity Chennai is located in Velachery, a bustling neighborhood known for its residential and commercial developments. The mall covers over 1.4 million square feet, making it one of the largest malls in the country.
            Phoenix Marketcity is a large, premium shopping mall chain in major India. It offers a variety of international and local brands, dining options, and entertainment, including cinemas and gaming zones. Known for its spacious design, it hosts events and live performances. It’s a popular destination for shopping, dining, and leisure activities.
        </p>
    </body>
</html>



```

### sea side code:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Sea Side</title>
        <style>
            * {
                background-color: lavenderblush;
            }
            h1 {
                text-align: center;
                color: darkcyan;
            }
            h2 {
                text-align: center;
                color: goldenrod;
            }
            p {
                font-size: 16px;
                line-height: 1.5;
                color: darkslategray;
            }
        </style>
    </head>
    <body>
        <h1>Velachery</h1>
        <h2>Coromandel Coast</h2>
        <hr color="tomato">
        <h3>Description</h3>
        <p>
            The Coromandel Coast, located along the southeastern coast of India, is renowned for its stunning beaches, rich cultural heritage, and vibrant ecosystems. Near Velachery, the coast offers picturesque seaside destinations such as Mahabalipuram, known for its ancient rock-cut temples and UNESCO World Heritage Sites. The region features serene beaches like ECR Beach and Marina Beach, where visitors can enjoy beautiful sunsets and recreational activities. Additionally, the coastal area is dotted with charming fishing villages, delicious seafood restaurants, and opportunities for water sports, making it a popular retreat for locals and tourists alike. With its proximity to Chennai, the Coromandel Coast is an ideal destination for day trips and weekend getaways, blending natural beauty with historical significance.
        </p>
    </body>
</html>


```
### National park code:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Park</title>
        <style>
            * {
                background-color: honeydew;
            }
            h1 {
                text-align: center;
                color: darkorange;
            }
            h2 {
                text-align: center;
                color: mediumseagreen;
            }
            p {
                font-size: 16px;
                line-height: 1.5;
                color: darkslateblue;
            }
        </style>
    </head>
    <body>
        <h1>Velachery</h1>
        <h2>Guindy National Park</h2>
        <hr color="orangered">
        <h3>Description</h3>
        <p>
            Guindy National Park, located near Velachery in Chennai, is one of the few national parks situated within a city in India. Covering around 2.7 square kilometers, this urban green space is home to a variety of flora and fauna, including spotted deer, blackbucks, jackals, and numerous bird species. The park is a haven for nature lovers and offers a peaceful escape from the bustling city. It also houses a children's park and a snake park, making it an educational and recreational spot for families. With its close proximity to Velachery, Guindy National Park provides a convenient retreat into nature for locals and tourists alike.
        </p>
    </body>
</html>


```
### Temple code:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Temple</title>
        <style>
            * {
                background-color: lavender;
            }
            h1 {
                text-align: center;
                color: teal;
            }
            h2 {
                text-align: center;
                color: lightgreen;
            }
            p {
                font-size: 16px;
                line-height: 1.5;
                color: darkslategray;
            }
        </style>
    </head>
    <body>
        <h1>Velachery</h1>
        <h2>Nanganallur Anjaneya Temple</h2>
        <hr color="darkmagenta">
        <h3>Description</h3>
        <p>
            The Nanganallur Anjaneya Temple in Chennai is renowned for its towering 32-feet tall idol of Lord Hanuman, making it one of the tallest Hanuman statues in India. Established in 1989, the temple has become a significant spiritual center, drawing devotees who seek blessings for strength, courage, and prosperity. The temple is known for its serene and peaceful ambiance, with regular religious rituals and celebrations, especially during festivals like Hanuman Jayanti. Located in the vibrant neighborhood of Nanganallur, the temple is easily accessible and is a cherished destination for both locals and visitors.
        </p>
    </body>
</html>

```


## OUTPUT
### My house output:
![image](https://github.com/user-attachments/assets/90eb5557-92f7-450c-a2a0-97bef6edfec1)

### Mall output:

![image](https://github.com/user-attachments/assets/4f9e5306-2c21-4838-a248-efa130fbb78d)

### sea side output:
![image](https://github.com/user-attachments/assets/c5c63cc6-87f9-436a-8ec5-86c4c6bddc93)
### park output:
![image](https://github.com/user-attachments/assets/373897fb-3ab5-4498-9392-aa6751ff16b5)

### Temple output:
![image](https://github.com/user-attachments/assets/2d14821d-9f5a-47fa-a80b-7f592f97c243)





## RESULT
The program for implementing image maps using HTML is executed successfully.
