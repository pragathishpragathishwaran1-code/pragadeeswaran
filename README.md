<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Food Corner</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f4f4f4;
}

header{
    background:#ff6b35;
    color:white;
    text-align:center;
    padding:20px;
}

nav{
    background:#333;
    text-align:center;
    padding:10px;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
}

.hero{
    text-align:center;
    padding:50px;
    background:linear-gradient(to right,#ff9966,#ff5e62);
    color:white;
}

.hero h1{
    font-size:50px;
}

.food-container{
    display:flex;
    justify-content:center;
    gap:20px;
    flex-wrap:wrap;
    padding:40px;
}

.card{
    background:white;
    width:250px;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 4px 10px rgba(0,0,0,0.2);
}

.card img{
    width:100%;
    height:180px;
    object-fit:cover;
}

.card h3{
    padding:10px;
}

.card p{
    padding:0 10px 10px;
}

.card button{
    margin:10px;
    padding:10px;
    width:90%;
    border:none;
    background:#ff6b35;
    color:white;
    border-radius:5px;
    cursor:pointer;
}

footer{
    background:#333;
    color:white;
    text-align:center;
    padding:15px;
}
</style>
</head>
<body>

<header>
    <h1>🍔 Food Corner</h1>
    <p>Delicious Food Delivered Fresh</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Menu</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
</nav>

<section class="hero">
    <h1>Welcome to Food Corner</h1>
    <p>Taste the best food in town!</p>
</section>

<section class="food-container">

    <div class="card">
        <img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?w=500" alt="Burger">
        <h3>Burger</h3>
        <p>Juicy and delicious burger.</p>
        <button>Order Now</button>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1513104890138-7c749659a591?w=500" alt="Pizza">
        <h3>Pizza</h3>
        <p>Hot cheesy pizza with toppings.</p>
        <button>Order Now</button>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c?w=500" alt="Salad">
        <h3>Salad</h3>
        <p>Healthy fresh vegetable salad.</p>
        <button>Order Now</button>
    </div>

</section>

<footer>
    <p>© 2026 Food Corner | All Rights Reserved</p>
</footer>

</body>
</html>
