# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Clone the github repository into Theia IDE.

### Step 2:
Create a new Django project

### Step 3:
Write the required HTML code

### Step 4:
Run the Django server and execute the HTML files.
## Code:
### index.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>My City</title>
    </head>
    <body>
    <h1 align="center">
        <font color="red"><b>SAKET MAP</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Click Any Location To View Details About it</b></font>
    </h3>
    <centre>
    <img id="Image-Maps-Com-image-maps-2023-06-08-193008" src="saket.png" border="0" width="1078" height="648" orgWidth="1078" orgHeight="648" usemap="#image-maps-2023-06-08-193008" alt="" />
<map name="image-maps-2023-06-08-193008" id="ImageMapsCom-image-maps-2023-06-08-193008">
<area  alt="" title="PVR Saket Delhi" href="pvr.html" shape="rect" coords="589,249,754,299" style="outline:none;" target="_self"     />
<area  alt="" title="Saket Metro" href="metro.html" shape="rect" coords="483,349,601,399" style="outline:none;" target="_self"     />
<area  alt="" title="Gyan School" href="school.html" shape="rect" coords="588,113,769,215" style="outline:none;" target="_self"     />
<area  alt="" title="Qutub Minar" href="minar.html" shape="rect" coords="56,189,176,306" style="outline:none;" target="_self"     />
<area  alt="" title="Hospital" href="hospital.html" shape="rect" coords="742,40,916,113" style="outline:none;" target="_self"     />
<area shape="rect" coords="1076,646,1078,648" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
</map>

        </centre>
    </body>
</html>
```
### hospital
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Hospital</title>
    </head>
    <body bgcolor="#C3FDB8">
        <h1 align="center">
            <font color="red"><b>SAKET</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Hospital</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
                Hospital, an institution that is built, staffed, and equipped for the diagnosis of disease;
                 for the treatment, both medical and surgical, of the sick and the injured; and for their 
                 housing during this process. The modern hospital also often serves as a centre for 
                 investigation and for teaching. hospital.
            </font>
        </p>
    </body>
</html>
```
### metro
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Saket Matro</title>
    </head>
    <body bgcolor="#C3FDB8">
        <h1 align="center">
            <font color="red"><b>SAKET</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Metro Train</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
                The SAKET Metro Station is an underground station located on yellow line of the Delhi Metro.
                The adjoining stations are Malviya Nagar (Towards Samai Pur Badli) & Qutub Minar Station (
                    Towards Huda City Centre), it is situated at Mehrauli Badarpur Road (M.B. Road).
            </font>
        </p>
    </body>
</html>
```
### minar
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Qutub Minar</title>
    </head>
    <body bgcolor="#C3FDB8">
        <h1 align="center">
            <font color="red"><b>SAKET</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Qutub Minar</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
                Built in the early 13th century a few kilometres south of Delhi,
                the red sandstone tower of Qutb Minar is 72.5 m high, tapering 
                from 2.75 m in diameter at its peak to 14.32 m at its base,
                and alternating angular and rounded flutings. The surrounding 
                archaeological area contains funerary buildings, notably the 
                magnificent Alai-Darwaza Gate, the masterpiece of Indo-Muslim art 
                (built in 1311), and two mosques, including the Quwwatu'l-Islam, 
                the oldest in northern India, built of materials reused from some 
                20 Brahman temples.
            </font>
        </p>
    </body>
</html>
```
### pvr
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>PVR Cinemas</title>
    </head>
    <body bgcolor="#C3FDB8">
        <h1 align="center">
            <font color="red"><b>SAKET</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>PVR Cinemas</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
            PVR Cinemas has its origin as Priya Cinema in Vasant Vihar, Delhi,
            the Cinema was named after Priya Jaisinghani and was bought by 
            Ajay Bijli's father in 1978, who also owned a trucking business,
            Amritsar Transport Co. In 1988, Bijli took over the running of 
            the cinema hall, which was revamped in 1990, and its success led 
            to the founding PVR Cinemas.
            </font>
        </p>
    </body>
</html>
```
### school
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Saket School</title>
    </head>
    <body bgcolor="#C3FDB8">
        <h1 align="center">
            <font color="red"><b>SAKET</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Gyan Bharathi School</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
             Gyan Bharati School is an English medium co-educational school, established in 1980. It is located in Saket next to PVR, New Delhi, India, and has classes from Nursery to the 12th standard. The school has 8 houses: Abhimanyu (Light Blue), Bharat (Violet), Dhruv (Indigo), Kasturba (Green), Prahlad (Yellow), Shravan (Orange), Lakshmibai (Red) & Siddharth (Maroon).
             The founding Principal of this school was M. N. Kapur. It is owned by the Ansal Group.
            </font>
        </p>
    </body>
</html>
```
## Output:
![Screenshot 2023-06-09 082539](https://github.com/ksagar007/places-around-me/assets/121165786/c04cc339-90a4-40cf-82b9-9df02fb8e2fa)

![Screenshot 2023-06-09 082646](https://github.com/ksagar007/places-around-me/assets/121165786/963ae54a-122c-43d6-a989-bdafea8bf9bd)
![Screenshot 2023-06-09 082739](https://github.com/ksagar007/places-around-me/assets/121165786/90467000-6438-4226-b86c-983b67bbceb6)
![Screenshot 2023-06-09 082833](https://github.com/ksagar007/places-around-me/assets/121165786/655f96d6-54db-46fd-84c7-0b3d1fb6d894)
![Screenshot 2023-06-09 082926](https://github.com/ksagar007/places-around-me/assets/121165786/ffe76c04-22bd-4afb-984f-b971b0bc0082)
![Screenshot 2023-06-09 083002](https://github.com/ksagar007/places-around-me/assets/121165786/88046762-a716-417f-ac33-734d18a4e090)


## Result:
The program for implementing image map is executed successsfully.
