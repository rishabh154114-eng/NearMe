# Ex03 Places Around Me

## Date:

28-05-2026

---

# AIM

To develop a website to display details about the places around my house.

---

# DESIGN STEPS

### STEP 1

Create a Django admin interface.

### STEP 2

Download your city map from Google as an image.

### STEP 3

Insert the image using `<img>` tag and link it to the map.

### STEP 4

Using `<map>` tag name the map.

### STEP 5

Create clickable regions in the image using `<area>` tag.

### STEP 6

Write HTML programs for all the regions identified.

### STEP 7

Execute the programs and publish them.

---

# CODE

## index.html

```html
<html>
<head>
    <title>VILLUPURAM MAP</title>
</head>

<body bgcolor="cyan">

    <h1 align="center">VILLUPURAM MAP</h1>

    <h2 align="center">
        T. Rishabh Srivastav - 21224113001
    </h2>

    <center>

        <img src="map.png"
             usemap="#image-map"
             width="1200"
             height="700">

    </center>

    <map name="image-map">

        <area alt="MGR GOVT COLLEGE"
              title="MGR GOVT COLLEGE"
              href="clg.html"
              coords="592,685,901,803"
              shape="rect">

        <area alt="VILLUPURAM RAILWAY STATION"
              title="VILLUPURAM RAILWAY STATION"
              href="rs.html"
              coords="922,323,1084,377"
              shape="rect">

        <area alt="PANAMPET LAKE"
              title="PANAMPET LAKE"
              href="lake.html"
              coords="1059,738,147"
              shape="circle">

        <area alt="VALEESHWARAR TEMPLE"
              title="VALEESHWARAR TEMPLE"
              href="temple.html"
              coords="1603,474,1907,565"
              shape="rect">

        <area alt="THENDRAL PARK"
              title="THENDRAL PARK"
              href="park.html"
              coords="765,229,958,308"
              shape="rect">

    </map>

</body>
</html>
```

---

## clg.html

```html
<html>
<head>
    <title>MGR GOVT COLLEGE</title>
</head>

<body bgcolor="lightyellow">

    <h1 align="center">MGR GOVT COLLEGE</h1>

    <h2 align="center">
        T. Rishabh Srivastav
    </h2>

    <h3 align="center">
        Register Number : 21224113001
    </h3>

    <p>
        Dr. M.G.R. Government Arts and Science College for Women,
        Villupuram was established in the year 2017.
    </p>

</body>
</html>
```

---

## lake.html

```html
<html>
<head>
    <title>PANAMPET LAKE</title>
</head>

<body bgcolor="lightblue">

    <h1 align="center">PANAMPET LAKE</h1>

    <h2 align="center">
        T. Rishabh Srivastav
    </h2>

    <h3 align="center">
        Register Number : 21224113001
    </h3>

    <p>
        Panampet Lake is located in Villupuram, Tamil Nadu.
        It is famous for bird watching and natural beauty.
    </p>

</body>
</html>
```

---

## park.html

```html
<html>
<head>
    <title>THENDRAL PARK</title>
</head>

<body bgcolor="lightgreen">

    <h1 align="center">THENDRAL PARK</h1>

    <h2 align="center">
        T. Rishabh Srivastav
    </h2>

    <h3 align="center">
        Register Number : 21224113001
    </h3>

    <p>
        Thendral Park is a popular place in Villupuram.
    </p>

</body>
</html>
```

---

## rs.html

```html
<html>
<head>
    <title>VILLUPURAM RAILWAY STATION</title>
</head>

<body bgcolor="lightgray">

    <h1 align="center">
        VILLUPURAM RAILWAY STATION
    </h1>

    <h2 align="center">
        T. Rishabh Srivastav
    </h2>

    <h3 align="center">
        Register Number : 21224113001
    </h3>

    <p>
        Villupuram Junction is an important railway station
        in Tamil Nadu connecting many cities.
    </p>

</body>
</html>
```

---

## temple.html

```html
<html>
<head>
    <title>VALEESHWARAR TEMPLE</title>
</head>

<body bgcolor="pink">

    <h1 align="center">
        VALEESHWARAR TEMPLE
    </h1>

    <h2 align="center">
        T. Rishabh Srivastav
    </h2>

    <h3 align="center">
        Register Number : 21224113001
    </h3>

    <p>
        Aadhi Valeeswarar Temple is a famous Shiva temple
        located in Villupuram.
    </p>

</body>
</html>
```

---

# OUTPUT

<img width="1900" height="1029" alt="Screenshot 2026-05-28 185534" src="https://github.com/user-attachments/assets/833c7288-b52e-48f6-8d1c-ac3816ed8350" />
<img width="1294" height="690" alt="Screenshot 2026-05-28 191401" src="https://github.com/user-attachments/assets/0e956ab4-ac63-4033-83cd-056ec04d1d63" />
<img width="1291" height="693" alt="Screenshot 2026-05-28 191440" src="https://github.com/user-attachments/assets/fafe2758-047a-4147-ae01-d200d14bfc7b" />
<img width="1303" height="665" alt="Screenshot 2026-05-28 191513" src="https://github.com/user-attachments/assets/9a734536-6af6-4345-a807-1ddc0a03824f" />
<img width="1299" height="687" alt="Screenshot 2026-05-28 191540" src="https://github.com/user-attachments/assets/bf135546-1587-4ff7-94e7-3bf5a6845006" />





---

# RESULT

The program for implementing image maps using HTML was executed successfully.
