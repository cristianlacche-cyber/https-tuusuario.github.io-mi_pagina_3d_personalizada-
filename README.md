<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Impresiones 3D - Tu Negocio</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 font-sans">

  <!-- SECCIÓN DE INICIO -->
  <section id="inicio" class="h-screen flex flex-col items-center justify-center text-center bg-gradient-to-r from-purple-500 to-pink-500 text-white">
    <h1 class="text-5xl font-bold mb-6">Dale vida a tus ideas en 3D</h1>
    <p class="text-lg mb-8 max-w-xl">Ofrecemos impresiones 3D de alta calidad a precios accesibles. Escoge un diseño, mándalo y lo imprimimos para ti.</p>
    <a href="#catalogo" class="bg-white text-purple-600 px-6 py-3 rounded-full font-semibold shadow-lg hover:bg-gray-200 transition">
      Ver catálogo de diseños
    </a>
  </section>

  <!-- CATÁLOGO -->
  <section id="catalogo" class="py-16 px-8 bg-white">
    <h2 class="text-4xl font-bold text-center text-gray-800 mb-12">Explora Diseños Gratuitos</h2>

    <div class="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto">
      <!-- Card Thingiverse -->
      <div class="bg-gray-50 rounded-2xl shadow-lg p-6 text-center hover:scale-105 transition">
        <h3 class="text-2xl font-semibold mb-4">Thingiverse</h3>
        <p class="text-gray-600 mb-4">Miles de modelos 3D gratuitos y listos para imprimir.</p>
        <a href="https://www.thingiverse.com/" target="_blank" class="text-white bg-purple-600 px-4 py-2 rounded-full hover:bg-purple-700">Visitar</a>
      </div>

      <!-- Card Printables -->
      <div class="bg-gray-50 rounded-2xl shadow-lg p-6 text-center hover:scale-105 transition">
        <h3 class="text-2xl font-semibold mb-4">Printables</h3>
        <p class="text-gray-600 mb-4">Modelos de alta calidad de la comunidad de Prusa.</p>
        <a href="https://www.printables.com/" target="_blank" class="text-white bg-purple-600 px-4 py-2 rounded-full hover:bg-purple-700">Visitar</a>
      </div>

      <!-- Card MyMiniFactory -->
      <div class="bg-gray-50 rounded-2xl shadow-lg p-6 text-center hover:scale-105 transition">
        <h3 class="text-2xl font-semibold mb-4">MyMiniFactory</h3>
        <p class="text-gray-600 mb-4">Colección curada de diseños de artistas y makers.</p>
        <a href="https://www.myminifactory.com/" target="_blank" class="text-white bg-purple-600 px-4 py-2 rounded-full hover:bg-purple-700">Visitar</a>
      </div>
    </div>
  </section>

  <!-- CONTACTO -->
  <section id="contacto" class="py-16 px-8 bg-gray-100">
    <h2 class="text-4xl font-bold text-center text-gray-800 mb-12">Contáctanos</h2>

    <div class="max-w-3xl mx-auto grid md:grid-cols-2 gap-8">
      <!-- Formulario -->
      <form class="bg-white p-6 rounded-2xl shadow-lg space-y-4">
        <div>
          <label class="block text-gray-700">Nombre</label>
          <input type="text" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500">
        </div>
        <div>
          <label class="block text-gray-700">Correo electrónico</label>
          <input type="email" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500">
        </div>
        <div>
          <label class="block text-gray-700">Mensaje</label>
          <textarea rows="4" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500"></textarea>
        </div>
        <button type="submit" class="w-full bg-purple-600 text-white px-4 py-2 rounded-lg hover:bg-purple-700">Enviar</button>
      </form>

      <!-- Info de contacto -->
      <div class="flex flex-col justify-center space-y-6">
        <p class="text-lg text-gray-700">📧 Escríbenos: <a href="mailto:tunegocio@gmail.com" class="text-purple-600 hover:underline">tunegocio@gmail.com</a></p>
        <p class="text-lg text-gray-700">📱 WhatsApp: <a href="https://wa.me/521234567890" target="_blank" class="text-green-600 hover:underline">+52 123 456 7890</a></p>
        <p class="text-lg text-gray-700">📍 Ciudad, País</p>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bg-gray-800 text-white text-center py-6">
    <p>&copy; 2025 Tu Negocio de Impresiones 3D | Hecho con ❤️</p>
  </footer>

</body>
</html>
