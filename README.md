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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MAP</title>
</head>
<script>
    function coordinate(event)
    {
        let x=event.clientX;
        let y=event.clientY;
        document.getElementById("text1").value=x;
        document.getElementById("text2").value=y;
    }
</script>
<body>
    <img src="HHH.jpg" width="1000px" usemap="#MyMap" onmousemove="coordinate(event)"><br>
    <map name="MyMap">
        <area shape="rect" coords="678,204,764,251" href="https://en.wikipedia.org/wiki/Russia" title="RUSSIA">
        <area shape="rect" coords="655,350,691,408" href="https://en.wikipedia.org/wiki/India" title="INDIA">
        <area shape="rect" coords="675,296,787,365" href="https://en.wikipedia.org/wiki/China" title="CHINA">     
    </map>
    X coordinate <input type="text" name="" id="text1">
    Y coordinate <input type="text" name="" id="text2">
</body>
</html>
```


## OUTPUT
![Screenshot 2024-05-15 093221](https://github.com/anandsandy4623/NearMe/assets/135193077/39f13065-41c5-4302-a9fc-ee836f4e3b64)
![Screenshot 2024-05-15 093247](https://github.com/anandsandy4623/NearMe/assets/135193077/0b35a259-fb19-4577-8dbd-9293fb25e2fe)
![Screenshot 2024-05-15 093305](https://github.com/anandsandy4623/NearMe/assets/135193077/f178bbcc-a496-4876-865f-24beda2ee3e2)
![Screenshot 2024-05-15 093329](https://github.com/anandsandy4623/NearMe/assets/135193077/e846c5b1-ea93-4d4f-b03b-63cf2a9edf92)










## RESULT
The program for implementing image maps using HTML is executed successfully.
