# Al-Aayat-Agrofoods-and-products-
Mustard oil manufacturing 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Al Aayat Agrofoods & Products</title>

<style>
body{
    margin:0;
    font-family: Arial, sans-serif;
    background:#f7f7f7;
}
header{
    background:#0b6623;
    color:white;
    padding:15px;
    text-align:center;
}
header h1{
    margin:0;
    font-size:28px;
}
nav{
    background:#145a32;
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
}
nav a{
    color:white;
    padding:12px 20px;
    text-decoration:none;
    font-weight:bold;
}
nav a:hover{
    background:#1e8449;
}
.hero{
    background:url('https://images.unsplash.com/photo-1604908177522-0403cfd408f6') center/cover;
    color:white;
    padding:80px 20px;
    text-align:center;
}
.hero h2{
    font-size:40px;
}
.hero p{
    font-size:18px;
}
.section{
    padding:40px 20px;
    max-width:1100px;
    margin:auto;
}
.section h2{
    text-align:center;
    color:#0b6623;
}
.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
    margin-top:30px;
}
.product{
    background:white;
    border-radius:10px;
    padding:20px;
    box-shadow:0 2px 8px rgba(0,0,0,0.1);
    text-align:center;
}
.product img{
    width:100%;
    height:180px;
    object-fit:cover;
    border-radius:10px;
}
.product h3{
    color:#145a32;
}
.about{
    background:white;
    border-radius:10px;
    padding:30px;
    box-shadow:0 2px 8px rgba(0,0,0,0.1);
}
.contact{
    background:#0b6623;
    color:white;
    padding:40px 20px;
    text-align:center;
}
.contact a{
    color:white;
    font-size:20px;
    text-decoration:none;
}
.whatsapp{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    color:white;
    padding:15px 20px;
    border-radius:50px;
    text-decoration:none;
    font-weight:bold;
}
footer{
    background:#145a32;
    color:white;
    text-align:center;
    padding:10px;
}
</style>
</head>

<body>

<header>
    <h1>Al Aayat Agrofoods & Products</h1>
    <p>Pure | Natural | Quality Agro Products</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
</nav>

<section class="hero" id="home">
    <h2>Pure & Natural Mustard Oil</h2>
    <p>Traditional Cold Pressed (Kachi Ghani) Agro Products</p>
</section>

<section class="section" id="about">
    <h2>About Us</h2>
    <div class="about">
        <p>
            <strong>Al Aayat Agrofoods & Products</strong> ek bharosemand agro brand hai jo
            shuddh, natural aur high quality food products provide karta hai.
            Hamara main focus cold pressed mustard oil aur farm fresh agro products par hai.
        </p>
        <p>
            Hamara mission hai har ghar tak sehatmand aur milawat-free products pahunchana.
        </p>
    </div>
</section>

<section class="section" id="products">
    <h2>Our Products</h2>
    <div class="products">
        <div class="product">
            <img src="https://images.unsplash.com/photo-1604908177522-0403cfd408f6">
            <h3>Mustard Oil (Kachi Ghani)</h3>
            <p>100% Pure & Cold Pressed Mustard Oil</p>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1567306226416-28f0efdc88ce">
            <h3>Wheat & Grains</h3>
            <p>Premium Quality Farm Grains</p>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1592924357228-91a4daadcfea">
            <h3>Agro Food Products</h3>
            <p>Fresh & Natural Agro Foods</p>
        </div>
    </div>
</section>

<section class="contact" id="contact">
    <h2>Contact Us</h2>
    <p>📍 India</p>
    <p>📞 Phone: +91-XXXXXXXXXX</p>
    <p>📧 Email: alaayatagro@gmail.com</p>
</section>

<a class="whatsapp" href="https://wa.me/91XXXXXXXXXX" target="_blank">
    WhatsApp Us
</a>

<footer>
    <p>© 2026 Al Aayat Agrofoods & Products. All Rights Reserved.</p>
</footer>

</body>
</html>
