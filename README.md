<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cetenry - Boutique Officielle</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: black; color: white; }
        header { background: black; color: white; padding: 20px; text-align: center; font-size: 30px; letter-spacing: 2px; }
        .container { max-width: 1200px; margin: auto; padding: 40px 20px; }
        .product-grid { display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; }
        .product { background: white; color: black; padding: 20px; border-radius: 10px; text-align: center; width: 300px; }
        .product img { width: 100%; max-width: 280px; border-radius: 5px; }
        .product h3 { margin: 10px 0; font-size: 20px; }
        .product p { font-size: 16px; }
        .price { font-weight: bold; font-size: 22px; }
        .btn { display: block; padding: 10px; background: black; color: white; text-decoration: none; margin-top: 10px; border-radius: 5px; }
        footer { background: black; color: white; text-align: center; padding: 20px; margin-top: 40px; }
    </style>
</head>
<body>
    <header>Cetenry - Boutique Officielle</header>
    <div class="container">
        <h2>Nos Produits</h2>
        <div class="product-grid">
            <div class="product">
                <img src="tshirt.jpg" alt="T-shirt Cetenry">
                <h3>T-shirt Cetenry</h3>
                <p>Un t-shirt minimaliste et élégant.</p>
                <p class="price">25€</p>
                <a href="#" class="btn">Acheter</a>
            </div>
            <div class="product">
                <img src="hoodie.jpg" alt="Hoodie Cetenry">
                <h3>Hoodie Cetenry</h3>
                <p>Un hoodie confortable et stylé.</p>
                <p class="price">50€</p>
                <a href="#" class="btn">Acheter</a>
            </div>
        </div>
    </div>
    <footer>
        &copy; 2025 Cetenry - Tous droits réservés.
    </footer>
</body>
</html>
