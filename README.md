# Travel-and-Tourism
Problem Statement No. : 32
Problem Title : Travel and Tourism
Basic simple website for travel booking.
Flight Booking -> Hotel Booking -> Tour Packages 

HTML CODE:
<!DOCTYPE html>
<html>
<head>
 <title>Travel and Tourism</title>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="Travel.css">
<header>
 <div class="logo">
  <a href="#">Travel and Tourism</a>
 </div>
 <nav>
  <ul>
   <li><a href="#">Home</a></li>
   <li><a href="#">About</a></li>
   <li><a href="#">Destinations</a></li>
   <li><a href="#">Contact</a></li>
  </ul>
 </nav>
</header>
</head>
<body>
<section class="banner" >
 <div class="slider">
  <img src="C:\Users\Avantika Roy\Downloads\TRAVEL AND TOURISM\Screenshot 2024-03-08 234713.png" alt="Banner 1" width="200" height="200">
  <img src="C:\Users\Avantika Roy\Downloads\TRAVEL AND TOURISM\BANNER 2.jpg" alt="Banner 2" width="200" height="200">
  <img src="C:\Users\Avantika Roy\Downloads\TRAVEL AND TOURISM\BANNER 3.jpg" alt="Banner 3" width="200" height="200">
 </div>
</section>
<section class="services">
 <h2>Our Services</h2>
 <div class="service">
  <img src="C:\Users\Avantika Roy\Downloads\TRAVEL AND TOURISM\pngkey.com-flight-png-3368227.png" alt="Service 1" width="300" height="300">
  <h3>Flight Booking</h3>
  <p>It is important to take care of the patient, to be followed by the patient, but it will happen at such a time that there is a lot of work and pain.</p>
 </div>
 <div class="service">
  <img src="C:\Users\Avantika Roy\Downloads\TRAVEL AND TOURISM\Screenshot 2024-03-09 002314.png" alt="Service 2" width="300" height="300">
  <h3>Hotel Booking</h3>
  <p>It is important to take care of the patient, to be followed by the patient, but it will happen at such a time that there is a lot of work and pain.</p>
 </div>
 <div class="service">
  <img src="C:\Users\Avantika Roy\Downloads\TRAVEL AND TOURISM\images.png" alt="Service 3" width="300" height="300">
  <h3>Tour Packages</h3>
  <p>It is important to take care of the patient, to be followed by the patient, but it will happen at such a time that there is a lot of work and pain.</p>
 </div>
</section>
<section class="destinations">
 <h2>Popular Destinations</h2>
 <div class="destination">
  <img src="C:\Users\Avantika Roy\Downloads\TRAVEL AND TOURISM\NEW YORK CITY.jpg" alt="Destination 1" width="500" height="600">
  <h3>New York</h3>
 </div>
 <div class="destination">
  <img src="C:\Users\Avantika Roy\Downloads\TRAVEL AND TOURISM\pexels-marcin-gierbisz-1125212.jpg" alt="Destination 2" width="500" height="600">
  <h3>Paris</h3>
 </div>
 <div class="destination">
  <img src="C:\Users\Avantika Roy\Downloads\TRAVEL AND TOURISM\pexels-nick-kwan-2614818.jpg" alt="Destination 3" width="500" height="600">
  <h3>Tokyo</h3>
 </div>
</section>
<footer>
 <div class="contact">
  <h4>Contact Us</h4>
  <p>Email: info@mytravelagency.com</p>
  <p>Phone: 1-800-123-4567</p>
 </div>
 <div class="social-media">
  <h4>Follow Us</h4>
  <a href="#"><i class="fab fa-facebook-f"></i></a>
  <a href="#"><i class="fab fa-twitter"></i></a>
  <a href="#"><i class="fab fa-instagram"></i></a>
  <a href="#"><i class="fab fa-linkedin-in"></i></a>
 </div>
</footer>
</body>
</html>

CSS code:
/* Global styles */
body {
font-family: Arial, sans-serif;
margin: 0;
padding: 0;
}

h1, h2, h3, h4, h5, h6 {
margin-top: 0;
}

a {
color: #0077c0;
text-decoration: none;
}

a:hover {
text-decoration: underline;
}

/* Header styles */
header {
background-color: #0077c0;
color: #fff;
display: flex;
flex-wrap: wrap;
justify-content: space-between;
padding: 20px;
}

.logo {
font-size: 32px;
font-weight: bold;
}

nav {
display: flex;
flex-wrap: wrap;
justify-content: center;
}

nav a {
color: #fff;
margin: 0 10px;
}

nav a:hover {
color: #ffd700;
}

/* Banner styles */
.banner {
background-image: url('img/banner.jpg');
background-position: center;
background-repeat: no-repeat;
background-size: cover;
height: 400px;
}

.banner h1 {
color: #fff;
font-size: 48px;
margin-top: 150px;
text-align: center;
text-shadow: 2px 2px #000;
}

/* Services styles */
.services {
display: flex;
flex-wrap: wrap;
justify-content: center;
margin:
50px 0;
}

.services article {
background-color: #fff;
box-shadow: 2px 2px 5px #ccc;
margin: 20px;
padding: 20px;
width: 300px;
}

.services article h3 {
font-size: 24px;
margin-top: 0;
}

.services article p {
margin-bottom: 0;
}

/* About styles */
.about {
display: flex;
flex-wrap: wrap;
justify-content: space-between;
margin: 50px auto;
max-width: 960px;
padding: 0 20px;
}

.about img {
border-radius: 50%;
height: 200px;
margin: auto;
}

.about p {
margin-top: 20px;
text-align: justify;
}

/* Contact styles */
form {
display: flex;
flex-wrap: wrap;
justify-content: space-between;
margin: 50px auto;
max-width: 960px;
padding: 0 20px;
}

form input[type="text"], form input[type="email"], form textarea {
border: none;
border-radius: 5px;
box-shadow: 2px 2px 5px #ccc;
padding: 10px;
width: 100%;
}

form input[type="submit"] {
background-color: #0077c0;
border: none;
border-radius: 5px;
color: #fff;
cursor: pointer;
margin-top: 20px;
padding: 10px 20px;
}

form input[type="submit"]:hover {
background-color: #ffd700;
}

.contact {
display: flex;
flex-wrap: wrap;
justify-content: space-between;
margin: 50px auto;
max-width: 960px;
padding: 0 20px;
}

.contact h4 {
margin-top: 0;
}

.contact p {
margin-bottom: 0;
}

.social-media {
display: flex;
flex-wrap: wrap;
justify-content: center;
margin-top: 20px;
}

.social-media a {
color: #0077c0;
font-size: 24px;
margin: 0 10px;
}

.social-media a:hover {
color: #ffd700;
}
