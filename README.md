# Ex04 Places Around Me
## Date: 

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
                <area shape="rect" coords="1478,43,1309,722" href="beach" title="Coromandel Coast ">
                <area shape="rect" coords="1020,108,924,116" href="national park" title="guingy national park">
                <area shape="rect" coords="524,310,512,315" href="temple " title="Nanganallur Anjaneya Temple">
            </map>
        </center>
        </body>
    </html>
    ```
### mall code:


## OUTPUT







## RESULT
The program for implementing image maps using HTML is executed successfully.
