<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Shubhkamna Fashion Studio</title>

<style>
body {
    margin:0;
    font-family: Arial;
    background:#f5f5f5;
}

header {
    background:black;
    color:white;
    padding:20px;
    text-align:center;
}

header h1 {
    color:#FFD700;
    margin:0;
}

.hero {
    background:url('shop.jpg') center/cover;
    height:300px;
    display:flex;
    justify-content:center;
    align-items:center;
    color:white;
    font-size:28px;
    font-weight:bold;
}

section {
    padding:20px;
}

.products {
    display:flex;
    flex-wrap:wrap;
    gap:15px;
}

.card {
    width:30%;
    background:white;
    padding:10px;
    box-shadow:0 0 10px rgba(0,0,0,0.1);
}

.card img {
    width:100%;
}

.contact {
    background:black;
    color:white;
    padding:20px;
}

.btn {
    display:inline-block;
    padding:12px 18px;
    margin:10px 5px;
    text-decoration:none;
    color:white;
    border-radius:5px;
}

.whatsapp {
    background:#25D366;
}

.upi {
    background:#ff6600;
}

.map {
    background:#007bff;
}

</style>
</head>

<body>

<header>
<h1>Shubhkamna Fashion Studio</h1>
<p>शुभकामना फैशन स्टूडियो</p>
</header>

<div class="hero">
Best Fashion Store in Gurugram
</div>

<section>
<h2>About Us</h2>
<p>
हम आपके लिए लाते हैं लेटेस्ट फैशन कपड़े और जूते सबसे अच्छे दाम में।
</p>
</section>

<section>
<h2>Our Collection</h2>

<div class="products">

<div class="card">
<img src="shoe1.jpg">
<h3>Premium Shoes</h3>
</div>

<div class="card">
<img src="shoe2.jpg">
<h3>Sports Shoes</h3>
</div>

<div class="card">
<img src="jeans.jpg">
<h3>Denim & Clothes</h3>
</div>

</div>

</section>

<section class="contact">
<h2>Contact & Order</h2>

<p>📍 Near Shiv Mandir Chowk, Rajiv Nagar, Sector 13, Gurugram</p>
<p>📞 098964 50189</p>
<p>🕒 9:30 AM – 10:00 PM</p>

<!-- WhatsApp Button -->
<a class="btn whatsapp" 
href="https://wa.me/919996715139?text=Hello%20Shubhkamna%20Fashion%20Studio,%20I%20want%20to%20order">
Order on WhatsApp</a>

<!-- UPI Payment Button -->
<a class="btn upi" 
href="upi://pay?pa=harshcheritydilsay@ptyes&pn=Shubhkamna%20Fashion%20Studio&cu=INR">
Pay via UPI</a>

<!-- Map Button -->
<a class="btn map" 
href="https://maps.app.goo.gl/igg5Smfj9H221WVM6">
View Location</a>

</section>

</body>
</html>
