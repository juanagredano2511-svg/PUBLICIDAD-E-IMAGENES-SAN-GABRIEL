<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#073b2b">
<title>Alejandro Impresiones Agredano</title>

<style>
:root {
  --green: #087844;
  --dark: #062d25;
  --lime: #b8ef45;
  --cream: #fffdf5;
}
* { box-sizing: border-box; }
html { scroll-behavior: smooth; }
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: var(--cream);
  color: #14231e;
  line-height: 1.6;
}
a { color: inherit; }
.topbar {
  background: var(--dark);
  color: white;
  padding: 12px 5%;
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 10px;
}
.topbar a { color: var(--lime); }
nav {
  background: white;
  padding: 18px 5%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 15px;
}
.brand {
  font-size: 19px;
  font-weight: bold;
  color: var(--green);
}
.navlinks { display: flex; gap: 18px; flex-wrap: wrap; }
.navlinks a { text-decoration: none; font-weight: bold; }
.hero {
  background: linear-gradient(125deg, #052d25, #087844, #a7d934);
  color: white;
  padding: 65px 6%;
  text-align: center;
}
.hero h1 { font-size: clamp(35px, 6vw, 60px); line-height: 1.1; }
.hero p { font-size: 18px; }
.btn {
  display: inline-block;
  padding: 13px 20px;
  border-radius: 10px;
  background: var(--lime);
  color: #17351e;
  text-decoration: none;
  font-weight: bold;
  margin: 8px;
}
section { padding: 55px 5%; }
.heading { text-align: center; margin-bottom: 30px; }
.heading h2 { font-size: 32px; }
.services {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 18px;
  max-width: 1100px;
  margin: auto;
}
.service {
  background: white;
  border: 1px solid #e1eae2;
  border-radius: 16px;
  padding: 24px;
  box-shadow: 0 5px 18px #0000000d;
}
.service .emoji { font-size: 35px; }
.service h3 { color: var(--green); margin-bottom: 5px; }
.service p { color: #65736b; margin-top: 5px; }
.banner { background: #f0f8e6; text-align: center; }
.contact {
  max-width: 600px;
  margin: auto;
  background: white;
  padding: 25px;
  border-radius: 16px;
}
.contact a { color: var(--green); font-weight: bold; }
footer {
  background: #041f1a;
  color: white;
  text-align: center;
  padding: 28px 15px;
}
.official {
  display: block;
  margin-top: 12px;
  color: var(--lime);
  font-weight: bold;
}
.float-wa {
  position: fixed;
  bottom: 18px;
  right: 15px;
  background: #1ebd62;
  color: white;
  padding: 13px 18px;
  border-radius: 30px;
  text-decoration: none;
  font-weight: bold;
}
</style>
</head>

<body>

<div class="topbar">
  <span>📍 Impresiones y diseño gráfico</span>
  <span>📲 WhatsApp: 341 147 5251</span>
</div>

<nav>
  <div class="brand">
    🐒 ALEJANDRO IMPRESIONES AGREDANO
  </div>
  <div class="navlinks">
    <a href="#servicios">Servicios</a>
    <a href="#nosotros">Nosotros</a>
    <a href="#contacto">Contacto</a>
  </div>
</nav>

<header class="hero">
  <h1>¡Dale vida a tus ideas!</h1>
  <p>
    Impresiones, artículos personalizados y diseño gráfico
    para tus eventos, negocios y proyectos.
  </p>
  <a class="btn"
     href="https://wa.me/523411475251?text=Hola,%20quiero%20cotizar">
     💬 Cotizar por WhatsApp
  </a>
  <a class="btn" href="#servicios">Ver servicios ↓</a>
</header>

<section id="servicios">
  <div class="heading">
    <h2>Nuestros servicios</h2>
    <p>¡Tenemos opciones para tus ideas y proyectos!</p>
  </div>

  <div class="services">

    <article class="service">
      <div class="emoji">📄</div>
      <h3>Copias</h3>
      <p>Copias de documentos en blanco y negro.</p>
    </article>

    <article class="service">
      <div class="emoji">🖨️</div>
      <h3>Impresiones</h3>
      <p>Impresiones de documentos a color y en blanco y negro.</p>
    </article>

    <article class="service">
      <div class="emoji">👕</div>
      <h3>Playeras y gorras</h3>
      <p>Personalización para eventos, equipos y negocios.</p>
    </article>

    <article class="service">
      <div class="emoji">🪧</div>
      <h3>Lonas</h3>
      <p>Diseños para anuncios, promociones y eventos.</p>
    </article>

    <article class="service">
      <div class="emoji">🎟️</div>
      <h3>Boletos y décimas</h3>
      <p>Impresos para rifas, eventos y ocasiones especiales.</p>
    </article>

    <article class="service">
      <div class="emoji">🎁</div>
      <h3>Recuerdos e invitaciones</h3>
      <p>Detalles personalizados para tus celebraciones.</p>
    </article>

    <article class="service">
      <div class="emoji">✨</div>
      <h3>Calcomanías y sellos</h3>
      <p>Opciones para identificar y decorar.</p>
    </article>

    <article class="service">
      <div class="emoji">🎨</div>
      <h3>Diseño gráfico</h3>
      <p>Diseños personalizados para tus proyectos.</p>
    </article>

    <article class="service">
      <div class="emoji">🧾</div>
      <h3>Notas de venta</h3>
      <p>Impresos para apoyar tu negocio.</p>
    </article>

    <article class="service">
      <div class="emoji">📚</div>
      <h3>Empastados</h3>
      <p>Acabados para documentos y trabajos.</p>
    </article>

  </div>
</section>

<section class="banner" id="nosotros">
  <h2>Tu idea es el comienzo</h2>
  <p>
    En Alejandro Impresiones Agredano te ayudamos
    a preparar tus diseños e impresos.
  </p>
</section>

<section id="contacto">
  <div class="contact">
    <h2>📞 Contáctanos</h2>
    <p>Solicita información y cotiza tu trabajo.</p>

    <p>
      💬 WhatsApp:
      <a href="https://wa.me/523411475251">
        341 147 5251
      </a>
    </p>

    <p>
      ☎️ Teléfono:
      <a href="tel:+523434270996">
        343 427 0996
      </a>
    </p>

    <a class="btn"
       href="https://wa.me/523411475251?text=Hola,%20quiero%20información">
       Pedir información
    </a>
  </div>
</section>

<footer>
  © <span id="year"></span> Alejandro Impresiones Agredano
  <br>Impresión y diseño gráfico
  <span class="official">
    Página web oficial Juanpablo
  </span>
</footer>

<a class="float-wa"
   href="https://wa.me/523411475251"
   target="_blank" rel="noopener">
   WhatsApp ↗
</a>

<script>
document.getElementById("year").textContent =
  new Date().getFullYear();
</script>

</body>
</html>
