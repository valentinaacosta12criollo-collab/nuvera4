<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Nuvéra — Renovación natural para tu piel</title>
  <meta name="description" content="Nuvéra: cremas naturales a base de cebo de res para renovar y nutrir la piel. Producto artesanal, ingredientes transparentes y efectividad comprobada." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --marfil:#FFF8ED;
      --vino:#C21B2B;
      --vino-bright:#E11B2B;
      --gris:#6B6B6B;
      --verde-soft:#EAF7F0;
      --max-width:1100px;
      --radius:14px;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,Arial,sans-serif;background:linear-gradient(180deg,var(--marfil),#fff);color:#111}
    .container{max-width:var(--max-width);margin:0 auto;padding:28px}

    header{display:flex;align-items:center;justify-content:space-between;padding:12px 0}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{background:linear-gradient(135deg,var(--vino),var(--vino-bright));color:white;padding:10px 14px;border-radius:12px;font-weight:800;font-size:20px;letter-spacing:0.6px}
    .tag{color:var(--gris);font-size:14px}

    .hero{display:grid;grid-template-columns:1fr 420px;gap:32px;align-items:center;padding:28px 0}
    .hero h1{font-size:40px;margin:0 0 12px;line-height:1.02}
    .hero p{color:var(--gris);margin:0 0 20px}
    .cta-row{display:flex;gap:12px;align-items:center}
    .btn{background:var(--vino);color:white;padding:12px 18px;border-radius:10px;border:0;font-weight:600;cursor:pointer}
    .btn-outline{background:transparent;border:2px solid var(--vino);color:var(--vino);padding:10px 16px;border-radius:10px;font-weight:600;cursor:pointer}

    .product-card{background:white;border-radius:var(--radius);padding:18px;box-shadow:0 6px 22px rgba(0,0,0,0.06)}
    .product-image{height:320px;border-radius:10px;background:linear-gradient(180deg,#f8f6f3,#fff);display:flex;align-items:center;justify-content:center;color:var(--gris);overflow:hidden;}
    .product-image img{max-height:100%;max-width:100%;object-fit:contain;border-radius:10px;}
    .price{font-size:22px;font-weight:700;margin-top:12px}

    .features{display:flex;gap:18px;margin-top:22px;flex-wrap:wrap}
    .feature{background:var(--verde-soft);padding:12px;border-radius:12px;min-width:180px}
    .feature h4{margin:0 0 6px}

    section{padding:28px 0;border-top:1px dashed rgba(0,0,0,0.04)}
    .grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}

    footer{padding:20px 0;color:var(--gris);font-size:14px;text-align:center}

    @media (max-width:900px){
      .hero{grid-template-columns:1fr;}
      .product-image{height:260px}
      .grid-3{grid-template-columns:1fr}
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">Nuvéra</div>
        <div>
          <div style="font-weight:600">Nuvéra</div>
          <div class="tag">Cuidado natural con cebo de res para renovar la piel</div>
        </div>
      </div>
      <nav aria-label="principal">
        <a href="#producto" style="margin-right:14px;color:var(--vino);font-weight:600;text-decoration:none">Producto</a>
        <a href="#beneficios" style="margin-right:14px;color:var(--gris);text-decoration:none">Beneficios</a>
        <a href="#contacto" style="color:var(--gris);text-decoration:none">Contacto</a>
      </nav>
    </header>

    <main>
      <section class="hero">
        <div>
          <h1>Nuvéra — <span style="color:var(--vino)">Renovación</span> natural para tu piel</h1>
          <p>Crema artesanal a base de <strong>cebo de res</strong> formulada para nutrir, reparar y renovar la piel. Ingredientes simples, efectos reales: hidratación profunda, equilibrio de la barrera cutánea y textura aterciopelada.</p>
          <div class="cta-row">
            <button class="btn">Comprar ahora</button>
            <button class="btn-outline">Ver ingredientes</button>
          </div>

          <div class="features" style="margin-top:20px">
            <div class="feature">
              <h4>Natural & efectivo</h4>
              <p style="margin:0;color:var(--gris)">Formulado con cebo de res purificado y extractos botánicos.</p>
            </div>
            <div class="feature">
              <h4>Artesanal</h4>
              <p style="margin:0;color:var(--gris)">Producido en pequeños lotes para garantizar calidad.</p>
            </div>
            <div class="feature">
              <h4>Sin aditivos agresivos</h4>
              <p style="margin:0;color:var(--gris)">Libre de parabenos, sulfatos y fragancias sintéticas.</p>
            </div>
          </div>
        </div>

        <!-- 🧴 Tarjeta de producto con imagen real -->
        <aside class="product-card" id="producto" aria-labelledby="producto-title">
          <div class="product-image" role="img" aria-label="Tarro de crema Nuvéra - Crema de Cebo de Res">
            <img src="producto-nuvera.png" alt="Tarro de crema Nuvéra - Crema de Cebo de Res">
          </div>
          <h3 id="producto-title" style="margin:14px 0 0">Crema Nuvéra — 60 ml</h3>
          <div class="price">$28.000 COP</div>
          <p style="color:var(--gris);margin-top:8px">Renueva la piel aportando lípidos naturales y mejorando la textura.</p>
          <div style="margin-top:12px;display:flex;gap:8px">
            <button class="btn" style="flex:1">Añadir al carrito</button>
            <button class="btn-outline" style="flex:1">Comprar en 1 clic</button>
          </div>
        </aside>
      </section>

      <section id="beneficios">
        <h2 style="margin:4px 0 12px">Beneficios principales</h2>
        <div class="grid-3">
          <article style="background:white;padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(0,0,0,0.04)">
            <h3>Hidratación profunda</h3>
            <p style="color:var(--gris)">El cebo de res aporta lípidos semejantes a los naturales de la piel, ayudando a retener humedad.</p>
          </article>
          <article style="background:white;padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(0,0,0,0.04)">
            <h3>Regeneración celular</h3>
            <p style="color:var(--gris)">Estimula la reparación de la barrera cutánea y mejora la apariencia de líneas finas.</p>
          </article>
          <article style="background:white;padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(0,0,0,0.04)">
            <h3>Textura sedosa</h3>
            <p style="color:var(--gris)">Deja la piel con una sensación no grasosa y un acabado aterciopelado.</p>
          </article>
        </div>
      </section>

      <section>
        <h2 style="margin:4px 0 12px">Ingredientes y proceso</h2>
        <p style="color:var(--gris);max-width:850px">Nuestra crema se elabora con <strong>cebo de res purificado</strong>, aceite de jojoba, manteca de karité, vitamina E y extractos botánicos seleccionados. El cebo se somete a procesos de purificación y filtrado para eliminar impurezas y garantizar seguridad cosmética. Producimos en pequeños lotes con pruebas de estabilidad y control de calidad.</p>

        <div style="display:flex;gap:18px;margin-top:18px;flex-wrap:wrap">
          <div style="flex:1;min-width:220px;background:white;padding:16px;border-radius:12px;box-shadow:0 6px 18px rgba(0,0,0,0.04)">
            <h4>Modo de uso</h4>
            <ol style="margin:8px 0 0 18px;color:var(--gris)">
              <li>Limpiar la piel con un limpiador suave.</li>
              <li>Aplicar una pequeña cantidad sobre la piel húmeda.</li>
              <li>Masajear hasta su completa absorción.</li>
            </ol>
          </div>
          <div style="flex:1;min-width:220px;background:white;padding:16px;border-radius:12px;box-shadow:0 6px 18px rgba(0,0,0,0.04)">
            <h4>Precauciones</h4>
            <ul style="margin:8px 0 0 18px;color:var(--gris)">
              <li>Hacer prueba en una pequeña área si la piel es sensible.</li>
              <li>Evitar contacto con ojos. En caso de irritación, suspender uso.</li>
              <li>No ingerir. Mantener fuera del alcance de los niños.</li>
            </ul>
          </div>
        </div>
      </section>

      <section id="contacto">
        <h2 style="margin:4px 0 12px">Contáctanos</h2>
        <div style="display:grid;grid-template-columns:1fr 320px;gap:20px;align-items:start">
          <form style="background:white;padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(0,0,0,0.04)" onsubmit="event.preventDefault();alert('Gracias — formulario demo (sin backend)');">
            <label for="name" style="display:block;margin-bottom:8px;font-weight:600">Nombre</label>
            <input id="name" name="name" required placeholder="Tu nombre" style="width:100%;padding:10px;border-radius:8px;border:1px solid #e7e7e7;margin-bottom:12px" />

            <label for="email" style="display:block;margin-bottom:8px;font-weight:600">Email</label>
            <input id="email" name="email" type="email" required placeholder="correo@ejemplo.com" style="width:100%;padding:10px;border-radius:8px;border:1px solid #e7e7e7;margin-bottom:12px" />

            <label for="message" style="display:block;margin-bottom:8px;font-weight:600">Mensaje</label>
            <textarea id="message" name="message" rows="4" placeholder="¿En qué podemos ayudarte?" style="width:100%;padding:10px;border-radius:8px;border:1px solid #e7e7e7;margin-bottom:12px"></textarea>

            <button class="btn" type="submit">Enviar mensaje</button>
          </form>

          <aside style="background:linear-gradient(180deg,#fff,#fff7f2);padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(0,0,0,0.02)">
            <h4 style="margin-top:0">Dónde encontrarnos</h4>
            <p style="color:var(--gris);margin:6px 0">Email: hola@nuvéra.com</p>
            <p style="color:var(--gris);margin:6px 0">Instagram: @nuvera_oficial</p>
            <p style="color:var(--gris);margin:6px 0">Producción local — envíos nacionales</p>
            <div style="margin-top:12px">
              <button class="btn-outline" onclick="alert('Teléfono demo: +57 300 000 0000')">Ver teléfono</button>
            </div>
          </aside>
        </div>
      </section>
    </main>

    <footer>
      <div style="max-width:var(--max-width);margin:0 auto;padding:18px 0">© <strong>Nuvéra</strong> — Crema natural de cebo de res. Hecho con cariño. • Política de privacidad • Términos</div>
    </footer>
  </div>
</body>
</html>
