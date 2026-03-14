<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SmileCare Dental Clinic</title>
<style>
body{
    margin:0;
    font-family:Arial, Helvetica, sans-serif;
    background:#f4f9ff;
}

header{
    background:#2c7be5;
    color:white;
    padding:20px;
    text-align:center;
}

nav{
    display:flex;
    justify-content:center;
    gap:25px;
    background:#1f5fbf;
    padding:10px;
}

nav a{
    color:white;
    text-decoration:none;
    font-weight:bold;
}

.hero{
    text-align:center;
    padding:60px 20px;
    background:white;
}

.hero h1{
    font-size:40px;
}

.btn{
    background:#2c7be5;
    color:white;
    padding:12px 25px;
    border:none;
    border-radius:5px;
    text-decoration:none;
    font-size:18px;
}

.services{
    padding:40px;
    text-align:center;
}

.service-box{
    display:inline-block;
    width:250px;
    margin:15px;
    padding:20px;
    background:white;
    border-radius:8px;
    box-shadow:0 0 10px rgba(0,0,0,0.1);
}

.booking{
    background:#e8f1ff;
    padding:50px;
    text-align:center;
}

form{
    max-width:400px;
    margin:auto;
}

input, select{
    width:100%;
    padding:12px;
    margin:10px 0;
    border-radius:5px;
    border:1px solid #ccc;
}

button{
    background:#2c7be5;
    color:white;
    padding:12px;
    border:none;
    border-radius:5px;
    width:100%;
    font-size:16px;
}

footer{
    background:#1f5fbf;
    color:white;
    text-align:center;
    padding:15px;
}
</style>
</head>

<body>

<header>
<h1>SmileCare Dental Clinic</h1>
<p>Your Healthy Smile Starts Here</p>
</header>

<nav>
<a href="#">Home</a>
<a href="#">Services</a>
<a href="#book">Book Now</a>
<a href="#">Contact</a>
</nav>

<section class="hero">
<h1>Professional Dental Care</h1>
<p>We provide the best dental treatments for your smile.</p>
<a href="#book" class="btn">Book Appointment</a>
</section>

<section class="services">
<h2>Our Services</h2>

<div class="service-box">
<h3>Teeth Cleaning</h3>
<p>Professional cleaning for healthy teeth.</p>
</div>

<div class="service-box">
<h3>Dental Implants</h3>
<p>Permanent solutions for missing teeth.</p>
</div>

<div class="service-box">
<h3>Teeth Whitening</h3>
<p>Brighten your smile instantly.</p>
</div>

</section>

<section class="booking" id="book">
<h2>Book Your Appointment</h2>

<form>
<input type="text" placeholder="Your Name" required>
<input type="email" placeholder="Email Address" required>
<input type="tel" placeholder="Phone Number" required>

<select required>
<option value="">Select Service</option>
<option>Teeth Cleaning</option>
<option>Dental Implants</option>
<option>Teeth Whitening</option>
</select>

<input type="date" required>

<button type="submit">Book Now</button>
</form>

</section>

<footer>
<p>© 2026 SmileCare Dental Clinic | All Rights Reserved</p>
</footer>

</body>
</html>
