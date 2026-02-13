<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicious Homemade Foods</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background-color: #fff7f2;
            color: #333;
        }
        header {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1606312619070-d48b4c652a52');
            background-size: cover;
            background-position: center;
            color: #fff;
            padding: 80px 20px;
            text-align: center;
        }
        header h1 {
            font-size: 42px;
        }
        header p {
            font-size: 20px;
            font-style: italic;
        }
        nav {
            background-color: #5c1a0f;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 50px 20px;
            max-width: 1100px;
            margin: auto;
        }
        h2 {
            text-align: center;
            color: #5c1a0f;
            margin-bottom: 30px;
        }
        .categories, .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        .card {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            text-align: center;
        }
        .card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 8px;
            margin-bottom: 10px;
        }
        .about {
            background-color: #fff1e8;
            border-radius: 10px;
            padding: 30px;
            line-height: 1.7;
        }
        .delivery {
            text-align: center;
            background-color: #ffe5d6;
            border-radius: 10px;
            padding: 30px;
            margin-top: 30px;
        }
        footer {
            background-color: #5c1a0f;
            color: #fff;
            padding: 30px 20px;
            text-align: center;
        }
        .contact-info p {
            margin: 8px 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Delicious Homemade Foods</h1>
    <p>"Made with love, served with sweetness"</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
</nav>

<section id="categories">
    <h2>Our Categories</h2>
    <div class="categories">
        <div class="card">Homemade Chocolates</div>
        <div class="card">Chocolate Gift Boxes</div>
        <div class="card">Festival Specials</div>
        <div class="card">Custom Orders</div>
    </div>
</section>

<section id="about">
    <h2>About Us</h2>
    <div class="about">
        <p>
            At <strong>Delicious Homemade Foods</strong>, we believe that good food brings happiness.
            Our chocolates are prepared with premium-quality ingredients, rich taste, and complete hygiene.
            Each product is lovingly handmade to ensure freshness, superior quality, and irresistible flavor.
            We focus on maintaining cleanliness, authentic taste, and customer satisfaction in every bite.
        </p>
    </div>
</section>

<section id="products">
    <h2>Our Products</h2>
    <div class="products">
        <div class="card">
            <img src="Images/darkchoco2.jpg" alt="Dark Chocolate">
            <h3>Dark Chocolate</h3>
            <p>Premium cocoa with rich and bold flavor.</p>
            <p><strong>Price:</strong> ₹199 / 250g(29-30chocolates)</p>
            <a href="https://wa.me/9182978397?text=Hi%2C%20I%20want%20to%20order%20Dark%20Chocolate%20250g.%20Is%20it%20available%3F" style="color:#fff;background:#25D366;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;">Order on WhatsApp</a>
        </div>
        <div class="card">
            <img src="milkchoco.jpg" alt="Milk Chocolate">
            <h3>Milk Chocolate</h3>
            <p>Smooth, creamy and loved by everyone.</p>
            <p><strong>Price:</strong> ₹199 / 250g(29-30chocolates)</p>
            <a href="https://wa.me/9182978397?text=I%20want%20to%20order%20Milk%20Chocolate" style="color:#fff;background:#25D366;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;">Order on WhatsApp</a>
        </div>
        <div class="card">
            <img src="nutschoco.jpeg" alt="Almond chocolate">
            <h3>Almond chocolates</h3>
            <p>Assorted chocolates in beautiful packaging.</p>
            <p><strong>Price:</strong> ₹279 /250g (29-30chocolates)</p>
            <a href="https://wa.me/9182978397?text=Hi%2C%20I%20want%20to%20order%20Almond%20Chocolates%20250g.%20Please%20confirm." style="color:#fff;background:#25D366;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;">Order on WhatsApp</a>
        </div>
        <div class="card">
            <img src="whitechoco.jpg" alt="White Chocolate">
            <h3>White Chocolate</h3>
            <p>Sweet, soft and creamy delight.</p>
            <p><strong>Price:</strong> ₹199 / 250g(29-30chocolates)</p>
            <a href="https://wa.me/9182978397?text=Hi%2C%20I%20want%20to%20order%20white%20Chocolates%20250g.%20Please%20confirm." style="color:#fff;background:#25D366;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;">Order on WhatsApp</a>
        </div>
        <div class="card">
            <img src="pistachoco.jpeg" alt="pista chocolate">
            <h3>Pista chocolate</h3>
            <p>Loaded with pista flavour</p>
            <p><strong>Price:</strong> ₹279 / 250g(29-30chocolates)</p>
            <a href="https://wa.me/9182978397?text=Hi%2C%20I%20want%20to%20order%20pista%20Chocolates%20250g.%20Please%20confirm." style="color:#fff;background:#25D366;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;">Order on WhatsApp</a>
        </div>
        <div class="card">
            <img src="milk and dark combo choco.jpeg" alt="milk and dark combo choco">
            <h3>Milk and Dark mix chocolates</h3>
            <p>Soft center with rich chocolate coating.</p>
            <p><strong>Price:</strong> ₹280 / 250g(29-30chocolates)</p>
            <a href="https://wa.me/9182978397?text=Hi%2C%20I%20want%20to%20order%20milk and dark combo %20Chocolates%20250g.%20Please%20confirm." style="color:#fff;background:#25D366;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;">Order on WhatsApp</a>
        </div>
        <div class="card">
            <img src="strawberry.jpeg" alt="Strawberry chocolates">
            <h3>Strawberry chocolates</h3>
            <p>loaded with strawberry flavour</p>
            <p><strong>Price:</strong> ₹279 / 250g(29-30chocolates)</p>
            <a href="https://wa.me/9182978397?text=Hi%2C%20I%20want%20to%20order%20Strawberry%20Chocolates%20250g.%20Please%20confirm." style="color:#fff;background:#25D366;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;">Order on WhatsApp</a>
        </div>
        <div class="card">
            <img src="dateschoco.webp" alt="Dates Chocolates">
            <h3>Dates chocolates</h3>
            <p>dates chocolates with extra nuts</p>
            <p><strong>Price:</strong> ₹300/250g(29-30 chocolates)</p>
            <a href="https://wa.me/9182978397?text=Hi%2C%20I%20want%20to%20order%20Date%20Chocolates%20250g.%20Please%20confirm." style="color:#fff;background:#25D366;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;">Order on WhatsApp</a>
        </div>
        <div class="card">
            <img src="almondbar.jpeg" alt="Almond Mini bars">
            <h3>Almond Mini bar chocolates</h3>
            <p>chocolate with almonds.</p>
            <p><strong>Price:</strong> Starts from ₹35-300</p>
            <a href="https://wa.me/9182978397?text=Hi%2C%20I%20want%20to%20order%20Almond bar%20Chocolates%20.%20Please%20confirm." style="color:#fff;background:#25D366;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;">Order on WhatsApp</a>
        </div>
        <div class="card">
            <img src="blueberrybar.jpeg" alt="blueberries mini and large chocolate bars">
            <h3>Blueberries mini and large chocolate bars</h3>
            <p>chocolate with blueberrys.</p>
            <p><strong>Price:</strong> Starts from ₹100-350</p>
            <a href="https://wa.me/9182978397?text=Hi%2C%20I%20want%20to%20order%20blueberries bar%20Chocolates%20.%20Please%20confirm." style="color:#fff;background:#25D366;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;">Order on WhatsApp</a>
        </div>
        <div class="card">
            <img src="couplechocobar.jpeg" alt="Couple chocolate bars">
            <h3>Couple chocolate bars </h3>
            <p>couple chocolate bars for your loved ones.</p>
            <p><strong>Price:</strong> ₹300</p>
            <a href="https://wa.me/9182978397?text=Hi%2C%20I%20want%20to%20order%20Couple%20Chocolates bars%20.%20Please%20confirm." style="color:#fff;background:#25D366;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;">Order on WhatsApp</a>
        </div>
        <div class="card">
            <img src="customaizedchoco.jpeg" alt="customaized chocolate bars">
            <h3>customaized chocolate bars with names </h3>
            <p>customaized chocolates also available with different desgins and flavours.</p>
            <p><strong>Price:</strong> ₹250 </p>
            <a href="https://wa.me/9182978397?text=Hi%2C%20I%20want%20to%20order coustamized bar%20Chocolates with name.%20Please%20confirm." style="color:#fff;background:#25D366;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;">Order on WhatsApp</a>
        </div>
        <div class="card">
            <img src="brownie.jpg" alt="chocolate brownie">
            <h3>chocolate brownie</h3>
            <p>Tasty brownie with chocolate</p>
            <p><strong>Price:</strong> ₹299(6 pieces) </p>
            <a href="https://wa.me/9182978397?text=Hi%2C%20I%20would%20like%20to%20order%20Chocolate%20Brownie%206%20pieces.%20Available%20today%3F" style="color:#fff;background:#25D366;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;">Order on WhatsApp</a>
        </div>
        <div class="card">
            <img src="cakepops.jpeg" alt="cake choco lollipos">
            <h3>cake choco lollipops </h3>
            <p> lovely choco lollipops </p>
            <p><strong>Price:</strong> ₹100(5 pieces) </p>
            <a href="https://wa.me/9182978397?text=I%20want%20to%20order%20Choco cake lollipops" style="color:#fff;background:#25D366;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;">Order on WhatsApp</a>
        </div>
        <div class="card">
            <img src="plumcake.jpeg" alt="choco plum cake whith nuts">
            <h3> choco Plum cake </h3>
            <p>sweet homemade delight with super taste and nuts</p>
            <p><strong>Price:</strong> ₹250 </p>
            <a href="https://wa.me/9182978397?text=I%20want%20to%20order%20Chocolate plum cake" style="color:#fff;background:#25D366;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;">Order on WhatsApp</a>
        </div>
        
        <div class="card">
            <img src="sprouted.webp" alt="Sprouted ragi powder">
            <h3>Sprouted ragi powder </h3>
            <p>Perfect for you health</p>
            <p><strong>Price:</strong> ₹80/250g </p>
            <a href="https://wa.me/9182978397?text=I%20want%20to%20order%20sprouted ragi powder" style="color:#fff;background:#25D366;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;">Order on WhatsApp</a>
        </div>
    
        <div class="card">
            <img src="kandipodi.jpg" alt="kandipodi">
            <h3>kandipodi </h3>
            <p>Complete meals with perfect taste </p>
            <p><strong>Price:</strong> ₹100/250g </p>
            <a href="https://wa.me/9182978397?text=I%20want%20to%20order%20Kandipodi" style="color:#fff;background:#25D366;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;">Order on WhatsApp</a>
        </div>
        <div class="card">
            <img src="jarcake.webp" alt="Jar cake">
            <h3>Jar cakes </h3>
            <p>yummy jar cakes </p>
            <p><strong>Price:</strong> ₹99/1bottle </p>
            <a href="https://wa.me/9182978397?text=I%20want%20to%20order%20Chocolate flavour jar cakes" style="color:#fff;background:#25D366;padding:8px 15px;border-radius:20px;text-decoration:none;display:inline-block;">Order on WhatsApp</a>
        </div>
        
    </div>

    <div class="delivery">
        <h3>Delivery & Ordering</h3>
        <p>✔ Online ordering available</p>
        <p>✔ Offline orders accepted</p>
        <p>✔ Home delivery across selected states</p>
        <p>✔ Pickup option also available</p>
        <a href="https://wa.me/9182978397" style="display:inline-block;margin-top:15px;padding:12px 25px;background:#25D366;color:#fff;text-decoration:none;border-radius:30px;font-weight:bold;">Order on WhatsApp</a>
    </div>
</section>

<section id="contact">
    <h2>Contact & Order</h2>
    <div class="contact-info">
        <p><strong>Phone / WhatsApp:</strong> +91-9182978397</p>
        <p><strong>Email:</strong> delicioushomemadefoods@gmail.com</p>
        <p><strong>Location:</strong> Available in multiple states</p>
    </div>

    <form onsubmit="sendOrderToWhatsApp(event)"
      style="max-width:500px;margin:30px auto;background:#fff;padding:20px;border-radius:10px;box-shadow:0 4px 8px rgba(0,0,0,0.1);">

    <h3 style="text-align:center;color:#5c1a0f;">Place Your Order</h3>

    <input type="text" id="customerName" placeholder="Your Name" required style="width:100%;padding:10px;margin:8px 0;">

    <input type="tel" id="phone" placeholder="Phone Number" required style="width:100%;padding:10px;margin:8px 0;">

    <input type="text" id="product" placeholder="Product Name" required style="width:100%;padding:10px;margin:8px 0;">

    <textarea id="address" placeholder="Delivery Address" required style="width:100%;padding:10px;margin:8px 0;"></textarea>

    <button type="submit"
        style="width:100%;padding:12px;background:#5c1a0f;color:#fff;border:none;border-radius:5px;font-size:16px;">
        Submit Order
    </button>
</form>

</section>

<footer>
    <p>© 2026 Delicious Homemade Foods | Homemade with Love ❤️</p>
</footer>
<script>
function sendOrderToWhatsApp(event) {
    event.preventDefault();

    const name = document.getElementById("customerName").value;
    const phone = document.getElementById("phone").value;
    const product = document.getElementById("product").value;
    const address = document.getElementById("address").value;

    const message = 
`New Order 📦
Name: ${name}
Phone: ${phone}
Product: ${product}
Address: ${address}`;

    const url = "https://wa.me/9182978397?text=" + encodeURIComponent(message);
    window.open(url, "_blank");
}
</script>
</body>
</html>
