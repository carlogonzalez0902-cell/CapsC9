<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Tienda de Gorras</title>
  <link rel="stylesheet" href="style.css">
  <script src="script.js" defer></script>
</head>
<body>
  <header>
    <h1>Tu Tienda de Gorras</h1>
    <nav>
      <a href="#">Inicio</a>
      <a href="#catalogo">Catálogo</a>
      <a href="#contacto">Contacto</a>
    </nav>
    <div id="carrito">Carrito (0)</div>
  </header>

  <section id="banner">
    <h2>Tu estilo empieza en la cabeza</h2>
    <button onclick="scrollToCatalogo()">Compra ahora</button>
  </section>

  <section id="catalogo">
    <h2>Nuestros Productos</h2>
    <div class="producto">
      <img src="gorra1.jpg" alt="Gorra Negra">
      <h3>Gorra Negra</h3>
      <p>$15.00</p>
      <button onclick="addToCart('Gorra Negra', 15)">Añadir al carrito</button>
    </div>
    <div class="producto">
      <img src="gorra2.jpg" alt="Gorra Roja">
      <h3>Gorra Roja</h3>
      <p>$18.00</p>
      <button onclick="addToCart('Gorra Roja', 18)">Añadir al carrito</button>
    </div>
  </section>

  <footer id="contacto">
    <h2>Contáctanos</h2>
    <p>WhatsApp: +507 6000 0000</p>
    <p>Email: info@tiendadegorras.pa</p>
  </footer>
</body>
</html>

