<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Rappi-ditto</title>
</head>

<body>

<header>

<h1>🚲 Rappi-Ditto</h1>

<input type="text" placeholder="Buscar productos o restaurantes...">

<nav>
<button>Inicio</button>
<button>Restaurantes</button>
<button>Promociones</button>
<button onclick="mostrarCarrito()">
🛒 Carrito (<span id="cantidad">0</span>)
</button>
</nav>

</header>

<section class="banner">

<h2>¡Pide tu comida favorita!</h2>

<p>Domicilios rápidos y amigables con el medio ambiente 🍃</p>

</section>

<section>

<h2>🍔 Hamburguesas</h2>

<div class="producto">
<h3>Hamburguesa Clásica</h3>
<p>$20.000</p>
<button onclick="agregar('Hamburguesa Clásica',20000)">Agregar</button>
</div>

<div class="producto">
<h3>Hamburguesa Doble</h3>
<p>$28.000</p>
<button onclick="agregar('Hamburguesa Doble',28000)">Agregar</button>
</div>

</section>

<section>

<h2>🍕 Pizzas</h2>

<div class="producto">
<h3>Pizza Pepperoni</h3>
<p>$38.000</p>
<button onclick="agregar('Pizza Pepperoni',38000)">Agregar</button>
</div>

<div class="producto">
<h3>Pizza Hawaiana</h3>
<p>$35.000</p>
<button onclick="agregar('Pizza Hawaiana',35000)">Agregar</button>
</div>

</section>

<section>

<h2>🍣 Sushi</h2>

<div class="producto">
<h3>California Roll</h3>
<p>$32.000</p>
<button onclick="agregar('California Roll',32000)">Agregar</button>
</div>

<div class="producto">
<h3>Salmón Roll</h3>
<p>$37.000</p>
<button onclick="agregar('Salmón Roll',37000)">Agregar</button>
</div>

</section>

<section>

<h2>🥤 Bebidas</h2>

<div class="producto">
<h3>Coca-Cola</h3>
<p>$8.000</p>
<button onclick="agregar('Coca-Cola',8000)">Agregar</button>
</div>

<div class="producto">
<h3>Limonada Natural</h3>
<p>$7.000</p>
<button onclick="agregar('Limonada Natural',7000)">Agregar</button>
</div>

</section>

<section>

<h2>🍰 Postres</h2>

<div class="producto">
<h3>Cheesecake</h3>
<p>$15.000</p>
<button onclick="agregar('Cheesecake',15000)">Agregar</button>
</div>

<div class="producto">
<h3>Brownie</h3>
<p>$18.000</p>
<button onclick="agregar('Brownie',18000)">Agregar</button>
</div>

</section>

<hr>

<section id="carrito">

<h2>🛒 Carrito de Compras</h2>

<ul id="lista"></ul>

<h3>Total: $<span id="total">0</span></h3>

<button onclick="realizarPedido()">
Confirmar Pedido
</button>

</section>

<hr>

<section id="login">

<h2>👤 Inicio de Sesión</h2>

<input id="usuario" type="text" placeholder="Usuario">

<input id="clave" type="password" placeholder="Contraseña">

<button onclick="iniciarSesion()">
Iniciar Sesión
</button>

<p id="estadoLogin">
No has iniciado sesión.
</p>

</section>

<hr>

<section id="domicilio">

<h2>🏠 Datos del domicilio</h2>

<input id="nombre" placeholder="Nombre completo">

<input id="direccion" placeholder="Dirección">

<input id="telefono" placeholder="Teléfono">

</section>

<hr>

<section>

<h2>🚴 Estado del pedido</h2>

<p id="estadoPedido">
Esperando pedido...
</p>

</section>
</body>
</html>
