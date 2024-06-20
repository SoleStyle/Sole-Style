# Sole-Style
Venta de Zapatillas Sneakers
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Tienda de Zapatillas</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenido a Mi Tienda de Zapatillas</h1>
    </header>
    <section class="hero">
        <img src="hero-image.jpg" alt="Zapatillas">
        <h2>Las mejores zapatillas para ti</h2>
    </section>
    <section class="products">
        <h2>Nuestros Productos</h2>
        <div class="product">
            <img src="zapatilla1.jpg" alt="Zapatilla 1">
            <h3>Zapatilla Deportiva</h3>
            <p>Precio: $50.00</p>
        </div>
        <div class="product">
            <img src="zapatilla2.jpg" alt="Zapatilla 2">
            <h3>Zapatilla Casual</h3>
            <p>Precio: $45.00</p>
        </div>
        <!-- Puedes agregar más productos aquí -->
    </section>
    <footer>
        <p>&copy; 2024 Mi Tienda de Zapatillas. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1em 0;
}

.hero {
    text-align: center;
    background-color: #fff;
    padding: 2em 0;
    margin: 1em 0;
}

.hero img {
    width: 100%;
    max-width: 600px;
}

.hero h2 {
    color: #333;
}

.products {
    text-align: center;
    padding: 2em 0;
}

.product {
    display: inline-block;
    width: 45%;
    margin: 1em 2%;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    padding: 1em;
}

.product img {
    width: 100%;
    max-width: 200px;
}

.product h3 {
    color: #333;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1em 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
