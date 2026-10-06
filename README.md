<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#102c34">
<meta name="description" content="Presentación educativa sobre la acción popular en Colombia: fundamento constitucional, derechos colectivos, requisitos, procedimiento y río Bogotá.">
<title>Acción popular | Lo de todos se defiende</title>

<style>
:root{
  --bg:#f6f5ef;
  --paper:#fffefa;
  --ink:#17343a;
  --muted:#596c70;
  --green:#126b5a;
  --lime:#d5ee8b;
  --yellow:#ffce66;
  --coral:#ef9179;
  --line:#dce3dc;
  --radius:24px;
  --shadow:0 16px 45px #1638300c;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth;scroll-padding-top:90px}
body{margin:0;background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif;line-height:1.65}
button,input,textarea{font:inherit}
a{color:var(--green)}
button,a,input,textarea,summary{outline-offset:5px}
button{cursor:pointer}
svg{display:block;width:100%;height:auto}
.symbols{position:absolute;width:0;height:0;overflow:hidden}
.skip{position:absolute;top:-60px;left:16px;background:white;padding:10px;z-index:100}
.skip:focus{top:10px}
header{position:sticky;top:0;z-index:20;background:#f6f5eff2;border-bottom:1px solid var(--line)}
.nav{max-width:1200px;margin:auto;padding:14px 24px;display:flex;align-items:center;justify-content:space-between;gap:16px}
.brand{text-decoration:none;color:var(--ink);font-weight:850;letter-spacing:-.6px;line-height:1.2}
.brand span{display:block;font-size:11px;letter-spacing:2px;color:var(--green);margin-top:4px}
nav{display:flex;gap:16px;align-items:center}
nav a{font-size:13px;text-decoration:none;color:var(--ink)}
.btn{border:0;border-radius:99px;background:var(--green);color:white;padding:11px 19px;font-weight:700;text-decoration:none;display:inline-flex;align-items:center;justify-content:center;gap:8px}
.btn.secondary{background:var(--paper);color:var(--ink);border:1px solid var(--line)}
.progress{height:3px;background:var(--green);width:0}
main{max-width:1200px;margin:auto;padding:0 24px}
.slide{padding:75px 0;border-bottom:1px solid var(--line)}
.hero{display:grid;grid-template-columns:1.15fr 1fr;gap:40px;align-items:center;min-height:80vh}
.eyebrow{text-transform:uppercase;letter-spacing:2px;font-size:12px;font-weight:800;color:var(--green);margin:0 0 15px}
h1,h2,h3{line-height:1.12;letter-spacing:-1.3px;margin-top:0}
h1{font-size:clamp(38px,5.3vw,72px);margin-bottom:24px}
h2{font-size:clamp(30px,4vw,48px);margin-bottom:18px}
h3{font-size:23px;letter-spacing:-.6px;margin-bottom:12px}
p{margin:0 0 16px}
.lead{font-size:20px;color:var(--muted);max-width:800px}
.hero .lead{font-size:19px}
.highlight{color:var(--green)}
.tag{display:inline-block;padding:5px 11px;border-radius:99px;background:#e9efe2;color:var(--green);font-size:12px;font-weight:700;margin:3px 4px 3px 0}
.actions{display:flex;gap:12px;flex-wrap:wrap;margin-top:26px}
.visual{background:#e6eee1;border-radius:32px;overflow:hidden;position:relative}
.visual-note{padding:12px 20px;font-size:12px;color:var(--muted)}
.grid{display:grid;gap:20px;margin-top:28px}
.three{grid-template-columns:repeat(3,1fr)}
.two{grid-template-columns:repeat(2,1fr)}
.card{background:var(--paper);border:1px solid var(--line);padding:25px;border-radius:var(--radius);box-shadow:var(--shadow)}
.card p:last-child{margin-bottom:0}
.card .mini{height:140px;margin:-5px 0 18px}
.small{font-size:13px;color:var(--muted)}
.source{font-size:12px;color:var(--green);display:block;margin-top:12px}
.callout{padding:25px 30px;background:var(--ink);color:white;border-radius:var(--radius);margin-top:26px}
.callout p:last-child{margin-bottom:0}
.callout.light{background:#e9efdd;color:var(--ink)}
.number{font-size:44px;line-height:1;font-weight:850;color:var(--green);margin-bottom:12px}
ol,ul{padding-left:24px}
li{margin-bottom:9px}
blockquote{margin:20px 0;padding:22px 26px;border-left:5px solid var(--green);background:#eaf0e5;border-radius:0 15px 15px 0;font-size:20px}
.table-wrap{overflow:auto;border-radius:18px;border:1px solid var(--line);margin-top:25px}
table{width:100%;border-collapse:collapse;background:var(--paper);min-width:620px}
th,td{padding:17px;text-align:left;border-bottom:1px solid var(--line);vertical-align:top}
th{background:#e7eddf;font-size:14px}
tr:last-child td{border-bottom:0}
.timeline{display:grid;gap:13px;margin-top:28px}
.step{display:grid;grid-template-columns:48px 1fr;gap:18px;padding:22px;background:var(--paper);border:1px solid var(--line);border-radius:20px}
.step .bubble{width:44px;height:44px;border-radius:50%;background:var(--lime);display:grid;place-items:center;font-weight:850}
.step h3{font-size:20px;margin-bottom:8px}
.step p{margin:0}
.warning{background:#fff1dc;border:1px solid #ecd1a2;padding:20px;border-radius:18px;margin-top:20px}
details{background:var(--paper);border:1px solid var(--line);padding:18px 22px;border-radius:16px;margin-bottom:12px}
summary{cursor:pointer;font-weight:750}
details p{margin:14px 0 0}
.checks{display:grid;gap:9px;margin:20px 0}
.checks label{display:flex;align-items:flex-start;gap:12px;padding:13px;background:#eef2e7;border-radius:12px}
input[type=checkbox]{width:19px;height:19px;margin-top:4px;accent-color:var(--green);flex-shrink:0}
.quiz button{width:100%;text-align:left;border:1px solid var(--line);background:white;padding:13px 16px;border-radius:12px;margin:5px 0;color:var(--ink)}
.quiz button:hover{background:#edf3e5}
.feedback{min-height:34px;margin-top:12px;font-weight:700}
.field{display:block;font-size:14px;font-weight:700;margin:15px 0 6px}
input[type=text],textarea{width:100%;border:1px solid #c9d4cb;padding:12px;border-radius:12px;background:white;color:var(--ink)}
textarea{min-height:95px;resize:vertical}
.output{white-space:pre-wrap;background:#edf1e6;border-radius:16px;padding:22px;line-height:1.7;font-size:14px;margin-top:20px}
[hidden]{display:none!important}
footer{max-width:1200px;margin:auto;padding:35px 24px 100px;color:var(--muted);font-size:13px}
footer a{overflow-wrap:anywhere}
.presentation-bar{position:fixed;bottom:20px;left:50%;transform:translateX(-50%);z-index:30;background:var(--ink);color:white;padding:10px;border-radius:99px;display:flex;align-items:center;gap:15px;box-shadow:0 8px 30px #0003}
.presentation-bar button{border:0;border-radius:99px;background:#ffffff20;color:white;padding:9px 15px}
.presentation-bar span{font-size:13px;white-space:nowrap}
body.presenting .slide{display:none;border:0;min-height:calc(100vh - 85px);padding:45px 0 110px}
body.presenting .slide.active{display:block}
body.presenting .hero.active{display:grid}
body.presenting footer{display:none}
body.presenting nav a{display:none}
body.presenting .progress{display:none}
@media(max-width:850px){
  .hero,.three,.two{grid-template-columns:1fr}
  .hero{padding-top:45px;gap:28px}
  .slide{padding:48px 0}
  nav a{display:none}
  .nav{padding:12px 18px}
  main{padding:0 18px}
  .hero .visual{max-width:550px;width:100%;margin:auto}
  body.presenting .hero.active{display:block}
  body.presenting .hero .visual{margin-top:25px}
}
@media(prefers-reduced-motion:reduce){
  html{scroll-behavior:auto}
}
@media print{
  header,.actions,.presentation-bar,.quiz button,.form-actions{display:none!important}
  body{background:white}
  body.presenting .slide,.slide{display:block!important;min-height:0!important;padding:25px 0!important;break-inside:avoid}
  body.presenting .hero.active,.hero{display:block!important}
  .hero .visual{max-width:350px}
  .grid{gap:12px}
  .card{box-shadow:none}
  footer,body.presenting footer{display:block}
  a{color:inherit}
}
</style>
</head>

<body>
<a class="skip" href="#contenido">Saltar al contenido</a>

<!-- Ilustraciones originales reutilizables: sin descargas externas. -->
<svg class="symbols" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
<defs>
  <symbol id="city" viewBox="0 0 600 430">
    <rect width="600" height="430" fill="#e6eee1"/>
    <circle cx="470" cy="85" r="45" fill="#ffce66"/>
    <path d="M0 220 100 130 190 215 310 100 450 215 600 140V430H0Z" fill="#b5ccad"/>
    <path d="M0 260 130 200 240 250 390 170 600 245V430H0Z" fill="#8fac99"/>
    <rect x="70" y="190" width="80" height="160" rx="6" fill="#fffefa"/>
    <rect x="165" y="225" width="60" height="125" rx="5" fill="#d5ee8b"/>
    <rect x="350" y="180" width="80" height="170" rx="6" fill="#fffefa"/>
    <rect x="445" y="235" width="75" height="115" rx="6" fill="#ef9179"/>
    <g fill="#126b5a">
      <path d="M85 210h18v22H85zm30 0h18v22h-18zm-30 40h18v22H85zm30 0h18v22h-18zm250-45h18v22h-18zm30 0h18v22h-18zm-30 40h18v22h-18zm30 0h18v22h-18z"/>
    </g>
    <path d="M0 340Q150 305 300 355T600 345V430H0Z" fill="#126b5a"/>
    <path d="M0 390Q150 330 300 390T600 380" fill="none" stroke="#8bcfc0" stroke-width="24"/>
    <g transform="translate(225 190)">
      <rect x="0" y="0" width="110" height="70" rx="12" fill="#ffce66"/>
      <path d="m20 70 8 20 20-20" fill="#ffce66"/>
      <path d="M27 35h56M55 15v40" stroke="#17343a" stroke-width="9" stroke-linecap="round"/>
    </g>
    <g transform="translate(215 275)">
      <circle cx="30" cy="0" r="17" fill="#9e603f"/>
      <path d="M5 66V32Q30 5 55 32v34" fill="#ffce66"/>
      <circle cx="92" cy="9" r="17" fill="#c7805c"/>
      <path d="M67 75V40Q92 15 117 40v35" fill="#fffefa"/>
      <circle cx="152" cy="0" r="17" fill="#68462f"/>
      <path d="M127 66V32Q152 5 177 32v34" fill="#ef9179"/>
    </g>
  </symbol>

  <symbol id="river" viewBox="0 0 600 360">
    <rect width="600" height="360" fill="#e4eee3"/>
    <circle cx="490" cy="70" r="34" fill="#ffce66"/>
    <path d="M0 185 110 65 220 190 360 70 600 180V360H0Z" fill="#9bb69b"/>
    <path d="M0 240 130 155 270 235 450 130 600 230V360H0Z" fill="#126b5a"/>
    <path d="M285 175Q430 210 290 250T330 360" fill="none" stroke="#77c6c5" stroke-width="76"/>
    <path d="M285 175Q430 210 290 250T330 360" fill="none" stroke="#ccecea" stroke-width="8" stroke-dasharray="24 15"/>
    <g fill="#d5ee8b">
      <circle cx="80" cy="230" r="32"/><circle cx="480" cy="250" r="37"/>
    </g>
    <g stroke="#614b35" stroke-width="9">
      <path d="M80 245v60M480 268v55"/>
    </g>
    <path d="m115 310 32-35 32 35zm345 20 30-35 30 35z" fill="#ffce66"/>
  </symbol>

  <symbol id="justice" viewBox="0 0 320 200">
    <rect width="320" height="200" rx="24" fill="#edf1e4"/>
    <circle cx="160" cy="90" r="70" fill="#d5ee8b"/>
    <path d="M160 35v115M98 65h124M125 160h70" stroke="#17343a" stroke-width="9" stroke-linecap="round"/>
    <path d="m105 65-30 55h60zm110 0-30 55h60z" fill="#ffce66" stroke="#126b5a" stroke-width="5" stroke-linejoin="round"/>
  </symbol>

  <symbol id="people" viewBox="0 0 320 200">
    <rect width="320" height="200" rx="24" fill="#eaf0e4"/>
    <circle cx="160" cy="75" r="50" fill="#ffce66"/>
    <g>
      <circle cx="80" cy="85" r="22" fill="#895437"/>
      <path d="M43 165v-34a37 37 0 0 1 74 0v34" fill="#126b5a"/>
      <circle cx="160" cy="78" r="23" fill="#c7835e"/>
      <path d="M122 170v-38a38 38 0 0 1 76 0v38" fill="#ef9179"/>
      <circle cx="242" cy="85" r="22" fill="#65432f"/>
      <path d="M205 165v-34a37 37 0 0 1 74 0v34" fill="#126b5a"/>
    </g>
  </symbol>

  <symbol id="document" viewBox="0 0 320 200">
    <rect width="320" height="200" rx="24" fill="#eaf0e4"/>
    <rect x="88" y="20" width="145" height="160" rx="13" fill="#fffefa"/>
    <path d="M112 53h95M112 77h75M112 102h95M112 127h60" stroke="#91ad96" stroke-width="7" stroke-linecap="round"/>
    <circle cx="230" cy="145" r="35" fill="#126b5a"/>
    <path d="m211 145 13 13 25-29" fill="none" stroke="#d5ee8b" stroke-width="7" stroke-linecap="round" stroke-linejoin="round"/>
  </symbol>

  <symbol id="shield" viewBox="0 0 320 200">
    <rect width="320" height="200" rx="24" fill="#eaf0e4"/>
    <path d="M160 20 230 45v58q0 48-70 78-70-30-70-78V45Z" fill="#126b5a"/>
    <path d="m125 98 25 25 46-52" fill="none" stroke="#d5ee8b" stroke-width="13" stroke-linecap="round" stroke-linejoin="round"/>
    <circle cx="255" cy="45" r="17" fill="#ffce66"/>
    <circle cx="65" cy="155" r="20" fill="#ef9179"/>
  </symbol>

  <symbol id="park" viewBox="0 0 320 200">
    <rect width="320" height="200" rx="24" fill="#eaf0e4"/>
    <path d="M0 170Q130 125 320 165v35H0Z" fill="#b9d29e"/>
    <circle cx="80" cy="68" r="40" fill="#126b5a"/>
    <circle cx="110" cy="87" r="29" fill="#126b5a"/>
    <path d="M85 95v73" stroke="#806044" stroke-width="10"/>
    <path d="M158 128h105M165 149h90M175 149v23M245 149v23" stroke="#17343a" stroke-width="9" stroke-linecap="round"/>
    <circle cx="256" cy="48" r="23" fill="#ffce66"/>
  </symbol>
</defs>
</svg>

<header>
  <div class="nav">
    <a class="brand" href="#inicio">Lo de todos se defiende<span>ACCIÓN POPULAR · COLOMBIA</span></a>
    <nav aria-label="Navegación principal">
      <a href="#fundamento">La herramienta</a>
      <a href="#ruta">Procedimiento</a>
      <a href="#caso">Río Bogotá</a>
      <button class="btn" id="presentationToggle" type="button">Presentar</button>
    </nav>
  </div>
  <div class="progress" id="progress" aria-hidden="true"></div>
</header>

<main id="contenido">

<section class="slide hero" id="inicio" aria-labelledby="titulo">
  <div>
    <p class="eyebrow">01 / Arranquemos con el chisme</p>
    <h1 id="titulo">¿Quiubo, y quién responde si nos dañan <span class="highlight">el río del barrio?</span></h1>
    <p class="lead">Imagínate el chisme: el río huele terrible, el parque quedó cerrado y todos dicen “eso no es conmigo”. ¿De verdad toca quedarse mirando?</p>
    <p>No. En Colombia existe una herramienta para llevar la defensa de los derechos colectivos ante un juez: la acción popular.</p>
    <span class="tag">Constitucional</span>
    <span class="tag">Participativa</span>
    <span class="tag">Defensa colectiva</span>
    <div class="actions">
      <a class="btn" href="#fundamento">Entremos en materia →</a>
      <button class="btn secondary" type="button" onclick="window.print()">Imprimir / guardar PDF</button>
    </div>
    <p class="small" style="margin-top:18px">Una persona puede iniciar el proceso. Lo colectivo es el derecho que protege, no el número de firmas.</p>
  </div>
  <div class="visual">
    <svg viewBox="0 0 600 430" role="img" aria-label="Ilustración de una comunidad, edificios, montañas y un río">
      <use href="#city"></use>
    </svg>
    <div class="visual-note">Ilustración conceptual original · Comunidad y derechos colectivos.</div>
  </div>
</section>

<section class="slide" id="fundamento">
  <p class="eyebrow">02 / La base constitucional</p>
  <h2>Artículo 88: lo común también tiene defensa.</h2>
  <p class="lead">La Constitución reconoce las acciones populares para proteger derechos e intereses colectivos y encarga a la ley regular su ejercicio.</p>
  <div class="grid three">
    <article class="card">
      <svg class="mini" viewBox="0 0 320 200" role="img" aria-label="Balanza de justicia"><use href="#justice"></use></svg>
      <h3>Primer inciso</h3>
      <p>Ordena regular la protección colectiva: patrimonio, espacio público, seguridad, salubridad, moralidad administrativa, ambiente, libre competencia y otros derechos semejantes.</p>
    </article>
    <article class="card">
      <svg class="mini" viewBox="0 0 320 200" role="img" aria-label="Personas reunidas"><use href="#people"></use></svg>
      <h3>Segundo inciso</h3>
      <p>También prevé acciones por daños ocasionados a un número plural de personas. La Ley 472 desarrolla la acción de grupo para obtener indemnización de perjuicios individuales.</p>
    </article>
    <article class="card">
      <svg class="mini" viewBox="0 0 320 200" role="img" aria-label="Documento jurídico"><use href="#document"></use></svg>
      <h3>Tercer inciso</h3>
      <p>Encarga a la ley definir casos de responsabilidad civil objetiva por daños a derechos e intereses colectivos. No significa que toda acción popular genere responsabilidad automática.</p>
    </article>
  </div>
  <div class="callout light">
    <p>Es una herramienta democrática porque abre la defensa judicial de lo común a las personas y organizaciones. No es una votación: decide un juez con hechos, pruebas y garantías procesales.</p>
  </div>
  <a class="source" href="https://www.constitucioncolombia.com/titulo-2/capitulo-4/articulo-88" target="_blank" rel="noopener noreferrer">Base: Constitución, artículo 88; Ley 472 de 1998, artículos 1–3.</a>
</section>

<section class="slide" id="naturaleza">
  <p class="eyebrow">03 / Qué es y para qué sirve</p>
  <h2>Prevenir, detener y restaurar.</h2>
  <p class="lead">La acción popular es un medio judicial de protección de derechos e intereses colectivos frente a acciones u omisiones de autoridades o particulares.</p>
  <div class="grid three">
    <article class="card">
      <div class="number">01</div><h3>Prevenir</h3>
      <p>Evitar un daño contingente: no es necesario esperar a que el daño se consume si existe una amenaza acreditada.</p>
    </article>
    <article class="card">
      <div class="number">02</div><h3>Hacer cesar</h3>
      <p>Detener el peligro, la amenaza o la vulneración que afecta a la comunidad.</p>
    </article>
    <article class="card">
      <div class="number">03</div><h3>Restaurar</h3>
      <p>Restituir las cosas a su estado anterior cuando sea posible, mediante órdenes judiciales concretas.</p>
    </article>
  </div>
  <div class="table-wrap">
    <table>
      <thead><tr><th>Característica</th><th>Explicación sin enredos</th></tr></thead>
      <tbody>
        <tr><td>Constitucional y colectiva</td><td>Su fundamento es el artículo 88. Protege intereses comunes, no solamente una inconformidad individual.</td></tr>
        <tr><td>Autónoma y principal</td><td>No es subsidiaria: su ejercicio no depende de agotar otros procesos judiciales. Sí debe cumplir sus requisitos propios.</td></tr>
        <tr><td>Legitimación amplia</td><td>Una persona natural o jurídica puede promoverla, sin reunir un número mínimo de demandantes.</td></tr>
        <tr><td>Preventiva y restitutoria</td><td>Puede actuar ante amenazas y frente a daños ya causados, buscando cesación y restauración cuando sea posible.</td></tr>
        <tr><td>Protección urgente posible</td><td>Permite medidas cautelares. No es una tutela ni garantiza una sentencia inmediata.</td></tr>
      </tbody>
    </table>
  </div>
  <p class="small" style="margin-top:16px">No está diseñada para cobrar una indemnización personal. La acción de grupo tiene una finalidad indemnizatoria distinta; las decisiones en acción popular pueden incluir reparación del daño colectivo en los términos legales.</p>
  <a class="source" href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=188" target="_blank" rel="noopener noreferrer">Ley 472: artículos 2, 9, 12, 25 y 34.</a>
  <a class="source" href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=55362" target="_blank" rel="noopener noreferrer">Consejo de Estado: autonomía y carácter no subsidiario.</a>
</section>

<section class="slide" id="derechos">
  <p class="eyebrow">04 / ¿Qué podemos defender?</p>
  <h2>No es “todo me molesta”. Es un derecho colectivo.</h2>
  <p class="lead">El artículo 4 de la Ley 472 enumera derechos colectivos. Estos son algunos de los más cercanos a la vida cotidiana.</p>
  <div class="grid three">
    <article class="card">
      <svg class="mini" viewBox="0 0 600 360" role="img" aria-label="Río y vegetación"><use href="#river"></use></svg>
      <h3>Ambiente y equilibrio ecológico</h3>
      <p>Ríos, ecosistemas, conservación de especies y aprovechamiento racional de recursos naturales.</p>
    </article>
    <article class="card">
      <svg class="mini" viewBox="0 0 320 200" role="img" aria-label="Parque con árbol y banca"><use href="#park"></use></svg>
      <h3>Espacio público</h3>
      <p>Goce del espacio público y defensa de bienes de uso público: parques, andenes y zonas comunes de uso público.</p>
    </article>
    <article class="card">
      <svg class="mini" viewBox="0 0 320 200" role="img" aria-label="Escudo de protección"><use href="#shield"></use></svg>
      <h3>Seguridad y salubridad</h3>
      <p>Seguridad y salubridad públicas; prevención de desastres previsibles técnicamente.</p>
    </article>
    <article class="card"><h3>Patrimonio público y moralidad</h3><p>Defensa de recursos públicos y moralidad administrativa. Una acusación genérica de corrupción no sustituye la prueba de la vulneración.</p></article>
    <article class="card"><h3>Servicios públicos</h3><p>Acceso a los servicios públicos y prestación eficiente y oportuna, así como infraestructura que garantice salubridad.</p></article>
    <article class="card"><h3>Otros derechos colectivos</h3><p>Patrimonio cultural, libre competencia, derechos de consumidores y usuarios, y urbanismo conforme a las normas.</p></article>
  </div>
  <a class="source" href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=188" target="_blank" rel="noopener noreferrer">Lista legal completa: artículo 4.</a>
</section>

<section class="slide" id="personas">
  <p class="eyebrow">05 / Quién puede actuar</p>
  <h2>Una sola persona puede dar el primer paso.</h2>
  <div class="grid two">
    <article class="card">
      <h3>Artículo 12: legitimación amplia</h3>
      <ul>
        <li>Toda persona natural o jurídica.</li>
        <li>ONG y organizaciones populares, cívicas o similares.</li>
        <li>Entidades públicas de control, intervención o vigilancia, si no originaron la amenaza o vulneración.</li>
        <li>Procurador General, Defensor del Pueblo y personeros, dentro de su competencia.</li>
        <li>Alcaldes y otros servidores públicos que deban proteger estos derechos por sus funciones.</li>
      </ul>
      <p class="small">El numeral 4 del artículo 12 se refiere específicamente al Procurador, al Defensor y a los personeros.</p>
    </article>
    <article class="card">
      <svg class="mini" viewBox="0 0 320 200" role="img" aria-label="Comunidad organizada"><use href="#people"></use></svg>
      <h3>Sin abogado, pero sin improvisar</h3>
      <p>El artículo 13 permite actuar directamente o por quien represente al legitimado. No es obligatorio contratar abogado para presentar la acción popular.</p>
      <p>La Personería o la Defensoría del Pueblo pueden colaborar en la elaboración de la demanda, conforme al artículo 17.</p>
      <p>Otras personas pueden coadyuvar antes del fallo de primera instancia: apoyar la protección colectiva dentro del proceso.</p>
    </article>
  </div>
  <blockquote>“No está pensada para batallas por intereses exclusivamente personales: una persona puede iniciarla y toda una comunidad puede beneficiarse.”</blockquote>
  <a class="source" href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=188" target="_blank" rel="noopener noreferrer">Ley 472: artículos 12, 13, 17 y 24.</a>
</section>

<section class="slide" id="competencia">
  <p class="eyebrow">06 / Contra quién y ante quién</p>
  <h2>Identifica al responsable y al juez competente.</h2>
  <div class="grid two">
    <article class="card">
      <h3>¿Contra quién se dirige?</h3>
      <p>Contra la autoridad pública o el particular, persona natural o jurídica, cuya acción u omisión amenaza o vulnera el derecho colectivo.</p>
      <p>Si no conoces al responsable, explica esa circunstancia y aporta lo que sabes: el artículo 14 atribuye al juez determinarlo. No inventes nombres.</p>
    </article>
    <article class="card">
      <h3>¿Quién conoce el proceso?</h3>
      <p>La jurisdicción contencioso-administrativa conoce los casos originados en actos, acciones u omisiones de entidades públicas o particulares que desempeñan funciones administrativas.</p>
      <p>En los demás casos, conoce la jurisdicción ordinaria civil, mediante los jueces civiles del circuito.</p>
      <p class="small">En la jurisdicción administrativa, la primera instancia puede corresponder a un juzgado o tribunal según las reglas vigentes del CPACA y la entidad demandada. Verifica el reparto concreto.</p>
    </article>
  </div>
  <div class="callout light">
    <p>Regla territorial de la Ley 472: lugar de ocurrencia de los hechos o domicilio del demandado, a elección del actor, teniendo en cuenta las reglas de competencia aplicables.</p>
  </div>
  <a class="source" href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=188" target="_blank" rel="noopener noreferrer">Ley 472: artículos 14–16. Complementar con las reglas vigentes del CPACA.</a>
</section>

<section class="slide" id="requisitos">
  <p class="eyebrow">07 / Preparación de la demanda</p>
  <h2>Menos “hagan algo”. Más hechos y pedidos concretos.</h2>
  <p class="lead">El artículo 18 establece qué debe incluir la demanda. Usa esta lista como revisión inicial, no como garantía de admisión.</p>
  <div class="grid two">
    <article class="card">
      <h3>Lista de verificación</h3>
      <div class="checks" id="checklist">
        <label><input type="checkbox"> <span>Identifiqué el derecho o interés colectivo amenazado o vulnerado.</span></label>
        <label><input type="checkbox"> <span>Describí los hechos, lugares, fechas y acciones u omisiones relevantes.</span></label>
        <label><input type="checkbox"> <span>Formulé pretensiones: qué órdenes concretas solicito.</span></label>
        <label><input type="checkbox"> <span>Señalé al presunto responsable, si es posible, o expliqué por qué lo desconozco.</span></label>
        <label><input type="checkbox"> <span>Indiqué y aporté las pruebas disponibles; solicité las que requieren intervención judicial.</span></label>
        <label><input type="checkbox"> <span>Incluí direcciones para notificaciones.</span></label>
        <label><input type="checkbox"> <span>Incluí mi nombre e identificación.</span></label>
        <label><input type="checkbox"> <span>Revisé la reclamación previa del CPACA, cuando aplica, o sustenté la excepción urgente.</span></label>
      </div>
      <p id="checkStatus" class="small" aria-live="polite">0 de 8 puntos revisados.</p>
    </article>
    <article class="card">
      <svg class="mini" viewBox="0 0 320 200" role="img" aria-label="Documento revisado"><use href="#document"></use></svg>
      <h3>¿Qué pruebas ayudan?</h3>
      <p>Fotografías y videos contextualizados, comunicaciones radicadas, respuestas oficiales, testimonios, informes e inspecciones o estudios técnicos pertinentes.</p>
      <p>Explica qué demuestra cada prueba y cómo se conecta con el derecho colectivo.</p>
      <div class="warning">La carga probatoria corresponde al demandante. Si hay dificultades económicas o técnicas, el artículo 30 prevé intervención del juez para obtener elementos indispensables. Eso no elimina el deber de sustentar los hechos.</div>
    </article>
  </div>
  <a class="source" href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=188" target="_blank" rel="noopener noreferrer">Ley 472: artículos 18 y 30.</a>
</section>

<section class="slide" id="ruta">
  <p class="eyebrow">08 / Procedimiento paso a paso</p>
  <h2>Del problema colectivo a una orden judicial.</h2>
  <div class="timeline">
    <article class="step"><div class="bubble">1</div><div><h3>Documentar y reclamar previamente cuando aplica</h3><p>En los casos del artículo 144 del CPACA, pide a la autoridad o al particular que ejerce funciones administrativas adoptar medidas de protección. Si no atiende la reclamación dentro de 15 días o se niega, puedes acudir al juez. La excepción por peligro inminente de perjuicio irremediable debe sustentarse en la demanda.</p></div></article>
    <article class="step"><div class="bubble">2</div><div><h3>Presentar la demanda</h3><p>Expón derecho colectivo, hechos, pretensiones, responsable si se conoce, pruebas, notificaciones e identificación. Solicita medidas cautelares si existe una urgencia justificada.</p></div></article>
    <article class="step"><div class="bubble">3</div><div><h3>Admisión y correcciones</h3><p>El artículo 20 prevé pronunciamiento sobre admisión dentro de 3 días hábiles. Si hay defectos, el juez indica qué corregir y concede 3 días para subsanar; no hacerlo puede causar rechazo.</p></div></article>
    <article class="step"><div class="bubble">4</div><div><h3>Notificación y contestación</h3><p>Se notifica a los demandados, se informa a la comunidad y se comunica a las entidades pertinentes. La Ley 472 contempla 10 días de traslado para contestar.</p></div></article>
    <article class="step"><div class="bubble">5</div><div><h3>Audiencia de pacto de cumplimiento</h3><p>Se busca una fórmula de protección del derecho colectivo. El acuerdo requiere revisión y aprobación judicial; no consiste en renunciar libremente a derechos de la comunidad.</p></div></article>
    <article class="step"><div class="bubble">6</div><div><h3>Pruebas, alegatos y sentencia</h3><p>Si no hay pacto aprobado, continúa la actividad probatoria. El juez valora la amenaza o vulneración y puede ordenar hacer, no hacer o restaurar, según corresponda.</p></div></article>
    <article class="step"><div class="bubble">7</div><div><h3>Apelación y cumplimiento</h3><p>La sentencia de primera instancia admite apelación. El juez conserva facultades para asegurar el cumplimiento y puede conformar un comité de verificación.</p></div></article>
  </div>
  <div class="warning">La reclamación previa no equivale a agotar recursos administrativos ni a tramitar otro juicio. El artículo 10 de la Ley 472 y el requisito del artículo 144 del CPACA regulan cuestiones distintas.</div>
  <a class="source" href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=188" target="_blank" rel="noopener noreferrer">Ley 472: artículos 10, 18–22, 27–34 y 37.</a>
  <a class="source" href="https://www.consejodeestado.gov.co/documentos/boletines/158/AC/88001-23-33-000-2013-00025-02(AP).pdf" target="_blank" rel="noopener noreferrer">Consejo de Estado: reclamación previa, artículo 144 del CPACA.</a>
</section>

<section class="slide" id="tiempos">
  <p class="eyebrow">09 / Tiempos sin falsas promesas</p>
  <h2>¿Cuándo se presenta y cuánto tarda?</h2>
  <div class="callout light">
    <p>La acción puede promoverse mientras subsista la amenaza o peligro al derecho colectivo. El antiguo límite de 5 años para pedir restitución fue declarado inexequible: no lo uses como regla vigente.</p>
  </div>
  <div class="table-wrap">
    <table>
      <thead><tr><th>Actuación</th><th>Término previsto</th><th>Base</th></tr></thead>
      <tbody>
        <tr><td>Reclamación previa, cuando aplica</td><td>15 días sin atención, o negativa; existe excepción urgente sustentada.</td><td>CPACA, art. 144.</td></tr>
        <tr><td>Pronunciamiento sobre admisión</td><td>3 días hábiles desde la presentación.</td><td>Ley 472, art. 20.</td></tr>
        <tr><td>Subsanar defectos</td><td>3 días.</td><td>Ley 472, art. 20.</td></tr>
        <tr><td>Contestación</td><td>10 días de traslado.</td><td>Ley 472, art. 22.</td></tr>
        <tr><td>Citación al pacto</td><td>Dentro de 3 días después del vencimiento del traslado: es el término para citar, no la duración total de la audiencia.</td><td>Ley 472, art. 27.</td></tr>
        <tr><td>Pruebas</td><td>20 días, prorrogables por otros 20 por complejidad.</td><td>Ley 472, art. 28.</td></tr>
        <tr><td>Alegatos</td><td>5 días de término común.</td><td>Ley 472, art. 33.</td></tr>
        <tr><td>Sentencia</td><td>20 días después del término para alegar.</td><td>Ley 472, art. 34.</td></tr>
      </tbody>
    </table>
  </div>
  <p class="small" style="margin-top:18px">Estos son términos legales de referencia, no una promesa de duración total. Notificaciones, pruebas, recursos, reglas complementarias y circunstancias del expediente influyen. No deben sumarse como un plazo automático ni confundirse con el término de la tutela.</p>
  <a class="source" href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=188" target="_blank" rel="noopener noreferrer">Ley 472, artículo 11 y nota de la Sentencia C-215 de 1999; artículos 20–34.</a>
</section>

<section class="slide" id="cautelares">
  <p class="eyebrow">10 / Cuando esperar puede empeorar todo</p>
  <h2>Medidas cautelares: proteger antes del fallo.</h2>
  <div class="grid two">
    <article class="card">
      <svg class="mini" viewBox="0 0 320 200" role="img" aria-label="Escudo de protección urgente"><use href="#shield"></use></svg>
      <h3>Artículo 25 de la Ley 472</h3>
      <p>Antes de la notificación de la demanda y en cualquier estado del proceso, el juez puede decretar medidas motivadas, de oficio o a petición de parte, para prevenir un daño inminente o hacer cesar el causado.</p>
      <p class="small">En la jurisdicción administrativa también deben revisarse las reglas cautelares aplicables del CPACA. La medida no equivale a una sentencia anticipada.</p>
    </article>
    <article class="card">
      <h3>¿Qué puede ordenar?</h3>
      <ul>
        <li>Cesación inmediata de actividades que originan o mantienen el daño.</li>
        <li>Ejecución de actos necesarios cuando el riesgo proviene de una omisión.</li>
        <li>Caución para garantizar el cumplimiento de medidas.</li>
        <li>Estudios para determinar el daño y las medidas urgentes para mitigarlo, en los términos legales.</li>
      </ul>
      <h3>¿Cómo pedirlas?</h3>
      <p>Describe la urgencia, aporta soportes y formula una medida concreta relacionada con el derecho colectivo. No basta escribir “es urgente”.</p>
    </article>
  </div>
  <div class="warning">No existe un plazo único garantizado de respuesta inmediata para toda solicitud cautelar. Su procedencia y trámite dependen de la medida, la jurisdicción y las normas aplicables.</div>
  <a class="source" href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=188" target="_blank" rel="noopener noreferrer">Ley 472, artículos 25–26.</a>
</section>

<section class="slide" id="caso">
  <p class="eyebrow">11 / Caso real colombiano</p>
  <h2>Río Bogotá: el derecho colectivo llegó al Consejo de Estado.</h2>
  <div class="grid two">
    <div class="visual">
      <svg viewBox="0 0 600 360" role="img" aria-label="Ilustración conceptual de recuperación de una cuenca"><use href="#river"></use></svg>
      <div class="visual-note">Representación conceptual: no muestra el estado actual del río Bogotá.</div>
    </div>
    <article class="card">
      <span class="tag">28 de marzo de 2014</span>
      <h3>Una sentencia sobre toda una cuenca</h3>
      <p>La Sección Primera del Consejo de Estado decidió la acción popular relacionada con la contaminación del río Bogotá y su cuenca.</p>
      <p>Protegió derechos colectivos ambientales y dispuso medidas de recuperación, coordinación institucional y control de las fuentes de contaminación, con obligaciones para autoridades y otros actores vinculados.</p>
      <p class="small">Radicación: 25000-23-27-000-2001-90479-01(AP).</p>
    </article>
  </div>
  <div class="callout">
    <h3>¿Por qué importa?</h3>
    <p>Muestra que la acción popular puede abordar problemas colectivos complejos y exigir respuestas coordinadas. Una sentencia no significa que el problema quede solucionado ese mismo día: el cumplimiento y su seguimiento son fundamentales.</p>
  </div>
  <p class="small" style="margin-top:18px">No confundas dos hitos: 2010 corresponde a la ley que eliminó incentivos; 2014, a esta sentencia del río Bogotá.</p>
  <a class="source" href="https://www.consejodeestado.gov.co/documentos/boletines/141/AC/25000-23-27-000-2001-90479-01(AP).pdf" target="_blank" rel="noopener noreferrer">Consultar sentencia del Consejo de Estado, 28 de marzo de 2014.</a>
</section>

<section class="slide" id="ley2010">
  <p class="eyebrow">12 / Aclaración clave</p>
  <h2>En 2010 quitaron el incentivo. No la herramienta.</h2>
  <div class="grid two">
    <article class="card">
      <h3>Ley 1425 de 2010</h3>
      <span class="tag">29 de diciembre de 2010</span>
      <p>Derogó los artículos 39 y 40 de la Ley 472, que establecían incentivos económicos para el actor popular.</p>
      <p>Por eso no debe prometerse el antiguo incentivo como recompensa por presentar hoy una acción popular.</p>
    </article>
    <article class="card">
      <h3>¿Qué no eliminó?</h3>
      <p>No eliminó la acción popular, la legitimación ciudadana, las medidas cautelares ni el recurso de apelación contra la sentencia de primera instancia.</p>
      <p>El artículo 37 de la Ley 472 contempla la apelación de esa sentencia, con las reglas procesales aplicables.</p>
    </article>
  </div>
  <blockquote>“Sin incentivo económico no significa sin derechos ni sin mecanismos de defensa.”</blockquote>
  <a class="source" href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=41034" target="_blank" rel="noopener noreferrer">Ley 1425 de 2010, artículos 1 y 2.</a>
  <a class="source" href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=188" target="_blank" rel="noopener noreferrer">Apelación: Ley 472, artículo 37.</a>
</section>

<section class="slide" id="ejemplos">
  <p class="eyebrow">13 / Del concepto al barrio</p>
  <h2>Ejemplos para entender la lógica.</h2>
  <p class="lead">Estas situaciones son hipotéticas y están contextualizadas en Colombia; no son sentencias reales ni predicciones de éxito.</p>
  <div class="grid three">
    <article class="card">
      <h3>Vertimientos en una quebrada</h3>
      <p>Una comunidad documenta descargas que afectan la quebrada y pide proteger el ambiente sano y el equilibrio ecológico.</p>
      <p class="small">Pruebas posibles: registros con fecha y ubicación, informes, inspecciones y comunicaciones a autoridades.</p>
    </article>
    <article class="card">
      <h3>Andén de uso público bloqueado</h3>
      <p>Una ocupación impide el paso por un andén. Se busca proteger el goce del espacio público y los bienes de uso público.</p>
      <p class="small">Debe verificarse la naturaleza pública del espacio, la afectación y la responsabilidad por acción u omisión.</p>
    </article>
    <article class="card">
      <h3>Riesgo de desastre previsible</h3>
      <p>Hay evidencia técnica de riesgo para un sector y se denuncia la omisión de medidas de prevención.</p>
      <p class="small">Derecho relacionado: seguridad y prevención de desastres previsibles técnicamente. El soporte técnico puede ser decisivo.</p>
    </article>
  </div>
  <a class="source" href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=188" target="_blank" rel="noopener noreferrer">Derechos y criterios de referencia: Ley 472, artículos 4, 9, 18 y 30.</a>
</section>

<section class="slide" id="errores">
  <p class="eyebrow">14 / Lo que debilita una acción</p>
  <h2>El chisme llama la atención. Las pruebas sostienen el caso.</h2>
  <div class="table-wrap">
    <table>
      <thead><tr><th>Error</th><th>Cómo corregirlo</th></tr></thead>
      <tbody>
        <tr><td>“Esto está muy mal”, sin señalar el derecho.</td><td>Identifica el derecho colectivo y explica la amenaza o vulneración.</td></tr>
        <tr><td>Relato sin fechas, ubicación o conducta.</td><td>Organiza hechos verificables y distingue lo observado de lo supuesto.</td></tr>
        <tr><td>No indicar al responsable conocido.</td><td>Identifícalo si es posible. Si lo desconoces, dilo y aporta información para determinarlo.</td></tr>
        <tr><td>Pedir únicamente dinero para sí mismo.</td><td>Revisa si necesitas otra vía. La finalidad popular es proteger derechos colectivos, no indemnizar perjuicios personales.</td></tr>
        <tr><td>Solicitar “que arreglen todo”.</td><td>Formula órdenes concretas, relacionadas con los hechos y el derecho.</td></tr>
        <tr><td>Omitir reclamación previa cuando corresponde.</td><td>Aporta la reclamación y sus soportes, o sustenta la excepción por perjuicio irremediable inminente.</td></tr>
        <tr><td>Afirmaciones sin soporte.</td><td>Aporta pruebas pertinentes y solicita las que no puedas obtener explicando la necesidad.</td></tr>
        <tr><td>Ignorar una orden de subsanación.</td><td>Corrige dentro del término indicado y atiende cada defecto señalado.</td></tr>
        <tr><td>Creer que ganar basta.</td><td>Revisa el cumplimiento de las órdenes y los mecanismos judiciales de seguimiento.</td></tr>
      </tbody>
    </table>
  </div>
  <p class="small" style="margin-top:18px">Estos errores no producen todos el mismo resultado: algunos pueden llevar a inadmisión o rechazo; otros afectan la prueba o el éxito de las pretensiones.</p>
  <a class="source" href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=188" target="_blank" rel="noopener noreferrer">Ley 472: artículos 14, 18, 20, 30 y 34.</a>
</section>

<section class="slide" id="preguntas">
  <p class="eyebrow">15 / A ver, ¿sí quedó claro?</p>
  <h2>Preguntas para poner a conversar al salón.</h2>
  <div class="grid two">
    <article class="card quiz">
      <h3>¿Cuántas personas se necesitan para presentar una acción popular?</h3>
      <button type="button" data-correct="true" data-feedback="¡Eso! Puede presentarla una sola persona. Lo colectivo es el derecho protegido.">Una persona puede hacerlo.</button>
      <button type="button" data-correct="false" data-feedback="No. No se exige reunir 20 demandantes para presentar una acción popular.">Mínimo veinte personas.</button>
      <button type="button" data-correct="false" data-feedback="No. El artículo 12 reconoce legitimación mucho más amplia.">Solo una entidad pública.</button>
      <p class="feedback" aria-live="polite"></p>
    </article>
    <article class="card quiz">
      <h3>¿Qué eliminó la Ley 1425 de 2010?</h3>
      <button type="button" data-correct="false" data-feedback="No. La acción popular sigue siendo una herramienta de protección colectiva.">La acción popular completa.</button>
      <button type="button" data-correct="true" data-feedback="Correcto. Derogó los artículos 39 y 40 sobre incentivos económicos.">Los incentivos económicos de los artículos 39 y 40.</button>
      <button type="button" data-correct="false" data-feedback="No. La sentencia de primera instancia admite apelación según el artículo 37 y las reglas aplicables.">Toda posibilidad de apelar.</button>
      <p class="feedback" aria-live="polite"></p>
    </article>
  </div>
  <div style="margin-top:25px">
    <details><summary>¿Toca esperar a que ocurra el daño?</summary><p>No. La acción popular también es preventiva: puede buscar evitar un daño contingente o detener una amenaza acreditada.</p></details>
    <details><summary>¿No necesitar abogado significa que puedo improvisar?</summary><p>No. Debes identificar el derecho, explicar los hechos, formular pretensiones y sustentar el caso. Puedes pedir apoyo a la Personería o la Defensoría.</p></details>
    <details><summary>¿Es subsidiaria, como suele decirse de la tutela?</summary><p>No. Es autónoma y principal. Eso no elimina requisitos propios como la reclamación previa del CPACA cuando corresponde.</p></details>
    <details><summary>¿Cuál sería el derecho colectivo en un parque público cerrado indebidamente?</summary><p>Podría estar comprometido el goce del espacio público y la defensa de bienes de uso público. Deben verificarse los hechos, la naturaleza del parque y la justificación de la restricción.</p></details>
    <details><summary>¿Qué hace más fuerte un caso: muchas firmas o hechos claros?</summary><p>No hay un mínimo de firmas. La claridad de los hechos, la conexión con el derecho colectivo, las pruebas y las pretensiones son fundamentales. La organización comunitaria puede apoyar, pero no reemplaza esos elementos.</p></details>
  </div>
  <a class="source" href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=188" target="_blank" rel="noopener noreferrer">Bases: Ley 472, artículos 2, 4, 12, 13, 17, 18 y 37.</a>
</section>

<section class="slide" id="taller">
  <p class="eyebrow">16 / Mini taller participativo</p>
  <h2>Convierte una queja en un mapa del problema.</h2>
  <p class="lead">Rellena los campos para crear una ficha educativa. No se envía información y no se genera una demanda lista para radicar.</p>
  <div class="grid two">
    <form class="card" id="worksheet">
      <label class="field" for="problem">¿Qué está pasando y dónde?</label>
      <textarea id="problem" placeholder="Ej.: Descargas recurrentes en una quebrada del sector, observadas en estas fechas..." required></textarea>
      <label class="field" for="right">¿Qué derecho colectivo podría estar afectado?</label>
      <input id="right" type="text" placeholder="Ej.: Ambiente sano y equilibrio ecológico." required>
      <label class="field" for="responsible">¿Quién podría ser responsable?</label>
      <input id="responsible" type="text" placeholder="Indica lo conocido o explica que no se conoce.">
      <label class="field" for="evidence">¿Qué pruebas tienes o necesitas?</label>
      <textarea id="evidence" placeholder="Fechas, fotos contextualizadas, informes, reclamaciones..."></textarea>
      <label class="field" for="request">¿Qué medida concreta propones?</label>
      <textarea id="request" placeholder="Una medida relacionada con el riesgo y respaldada por los hechos." required></textarea>
      <div class="actions form-actions">
        <button class="btn" type="submit">Crear ficha</button>
        <button class="btn secondary" type="reset">Limpiar</button>
      </div>
    </form>
    <article class="card">
      <svg class="mini" viewBox="0 0 320 200" role="img" aria-label="Documento de trabajo"><use href="#document"></use></svg>
      <h3>Una idea ordenada vale más.</h3>
      <p>Pregunta siempre: ¿qué pasa?, ¿a quién afecta colectivamente?, ¿qué derecho está comprometido?, ¿qué lo demuestra?, ¿qué orden podría protegerlo?</p>
      <div class="output" id="worksheetOutput" hidden aria-live="polite"></div>
      <p class="small" style="margin-top:18px">Los datos permanecen en esta página y se pierden al recargar. La ficha no revisa competencia, requisitos procesales ni suficiencia probatoria.</p>
    </article>
  </div>
</section>

<section class="slide" id="cierre">
  <p class="eyebrow">17 / La idea que nos llevamos</p>
  <h2>La unión hace la fuerza.<br><span class="highlight">Los derechos le dan dirección.</span></h2>
  <div class="grid two">
    <div>
      <p class="lead">La acción popular convierte la preocupación por lo común en una solicitud judicial de protección.</p>
      <p>Puede comenzar con una persona, pero su sentido no es una batalla por intereses exclusivamente individuales: es defender aquello que la comunidad comparte.</p>
      <blockquote>“¿Quién responde?” deja de ser solo un chisme cuando identificamos el derecho, reunimos pruebas y pedimos una protección concreta.</blockquote>
      <p class="small">Material educativo. Para un caso real, verifica las normas vigentes, la competencia y los requisitos aplicables; busca orientación en la Personería, la Defensoría o con un profesional.</p>
    </div>
    <div class="visual">
      <svg viewBox="0 0 600 430" role="img" aria-label="Comunidad junto a un río y una ciudad"><use href="#city"></use></svg>
    </div>
  </div>
</section>
</main>

<footer>
  <p>Presentación educativa sobre derecho colombiano. Ilustraciones SVG originales incorporadas; no representan pruebas ni fotografías de casos reales.</p>
  <p>Fuentes principales:
    <a href="https://www.constitucioncolombia.com/titulo-2/capitulo-4/articulo-88" target="_blank" rel="noopener noreferrer">Constitución, artículo 88</a> ·
    <a href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=188" target="_blank" rel="noopener noreferrer">Ley 472 de 1998</a> ·
    <a href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=41034" target="_blank" rel="noopener noreferrer">Ley 1425 de 2010</a> ·
    <a href="https://www.consejodeestado.gov.co/documentos/boletines/158/AC/88001-23-33-000-2013-00025-02(AP).pdf" target="_blank" rel="noopener noreferrer">Reclamación previa del CPACA</a> ·
    <a href="https://www.consejodeestado.gov.co/documentos/boletines/141/AC/25000-23-27-000-2001-90479-01(AP).pdf" target="_blank" rel="noopener noreferrer">Sentencia del río Bogotá</a>.
  </p>
</footer>

<div class="presentation-bar" id="presentationBar" hidden aria-label="Controles de presentación">
  <button id="previousSlide" type="button" aria-label="Diapositiva anterior">←</button>
  <span id="slideCounter" aria-live="polite">1 / 17</span>
  <button id="nextSlide" type="button" aria-label="Diapositiva siguiente">→</button>
  <button id="exitPresentation" type="button">Salir</button>
</div>

<script>
(() => {
  const slides = Array.from(document.querySelectorAll(".slide"));
  const toggle = document.getElementById("presentationToggle");
  const bar = document.getElementById("presentationBar");
  const counter = document.getElementById("slideCounter");
  const previous = document.getElementById("previousSlide");
  const next = document.getElementById("nextSlide");
  let presenting = false;
  let current = 0;
  let returnScroll = 0;

  function renderSlide(){
    slides.forEach((slide,index) => slide.classList.toggle("active",index === current));
    counter.textContent = `${current + 1} / ${slides.length}`;
    previous.disabled = current === 0;
    next.disabled = current === slides.length - 1;
    window.scrollTo(0,0);
  }

  function setPresentation(enabled){
    presenting = enabled;
    if(enabled){
      returnScroll = window.scrollY;
      const nearest = slides.reduce((best,slide,index) =>
        Math.abs(slide.getBoundingClientRect().top - 85) <
        Math.abs(slides[best].getBoundingClientRect().top - 85) ? index : best,0);
      current = nearest;
    }
    document.body.classList.toggle("presenting",enabled);
    bar.hidden = !enabled;
    toggle.textContent = enabled ? "Salir del modo" : "Presentar";
    if(enabled) renderSlide();
    else{
      slides.forEach(slide => slide.classList.remove("active"));
      window.scrollTo(0,returnScroll);
    }
  }

  toggle.addEventListener("click",() => setPresentation(!presenting));
  document.getElementById("exitPresentation").addEventListener("click",() => setPresentation(false));
  previous.addEventListener("click",() => {
    if(current > 0){current--;renderSlide();}
  });
  next.addEventListener("click",() => {
    if(current < slides.length - 1){current++;renderSlide();}
  });

  document.addEventListener("keydown",event => {
    if(!presenting || /INPUT|TEXTAREA|SELECT/.test(event.target.tagName)) return;
    if(event.key === "Escape") setPresentation(false);
    if(event.key === "ArrowRight" && current < slides.length - 1){
      event.preventDefault();current++;renderSlide();
    }
    if(event.key === "ArrowLeft" && current > 0){
      event.preventDefault();current--;renderSlide();
    }
  });

  let ticking = false;
  function updateProgress(){
    const total = document.documentElement.scrollHeight - window.innerHeight;
    document.getElementById("progress").style.width =
      (total > 0 ? Math.min(100,window.scrollY / total * 100) : 0) + "%";
    ticking = false;
  }
  window.addEventListener("scroll",() => {
    if(!ticking){requestAnimationFrame(updateProgress);ticking = true;}
  },{passive:true});
  updateProgress();

  const checks = Array.from(document.querySelectorAll("#checklist input"));
  checks.forEach(check => check.addEventListener("change",() => {
    const count = checks.filter(item => item.checked).length;
    document.getElementById("checkStatus").textContent =
      `${count} de ${checks.length} puntos revisados.` +
      (count === checks.length ? " Revisión inicial completa; no garantiza admisión ni éxito." : "");
  }));

  document.querySelectorAll(".quiz button").forEach(button => {
    button.addEventListener("click",() => {
      const feedback = button.closest(".quiz").querySelector(".feedback");
      feedback.textContent = button.dataset.feedback;
      feedback.style.color = button.dataset.correct === "true" ? "#126b5a" : "#a94730";
    });
  });

  const form = document.getElementById("worksheet");
  const output = document.getElementById("worksheetOutput");
  const value = id => document.getElementById(id).value.trim();

  form.addEventListener("submit",event => {
    event.preventDefault();
    output.textContent =
`FICHA EDUCATIVA DEL PROBLEMA COLECTIVO

Situación y lugar:
${value("problem")}

Derecho colectivo propuesto:
${value("right")}

Posible responsable:
${value("responsible") || "No identificado: explicar lo conocido y la dificultad para determinarlo."}

Pruebas disponibles o necesarias:
${value("evidence") || "Pendiente de documentar."}

Medida propuesta:
${value("request")}

Pendientes:
Verificar competencia, reclamación previa cuando aplica, identificación, notificaciones, pretensiones y soporte probatorio.

Esta ficha no es una demanda lista para radicar.`;
    output.hidden = false;
  });
  form.addEventListener("reset",() => {
    output.hidden = true;
    output.textContent = "";
  });
})();
</script>
</body>
</html>
