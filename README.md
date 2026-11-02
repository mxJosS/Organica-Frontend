<h1 align="center">🌱 Orgánica</h1>

<p align="center">
  Página web de una granja orgánica que presenta sus servicios:<br>
  ganado vacuno, productos lácteos y frutas de la huerta.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery">
  <img src="https://img.shields.io/badge/Font_Awesome-538DD7?style=for-the-badge&logo=fontawesome&logoColor=white" alt="Font Awesome">
</p>

<hr>

<h2>👤 Autor</h2>

<table>
  <tr>
    <td><b>Nombre</b></td>
    <td>José Ángel Espinosa García</td>
  </tr>
  <tr>
    <td><b>Materia</b></td>
    <td>Desarrollo Frontend</td>
  </tr>
  <tr>
    <td><b>Grupo</b></td>
    <td>9SB</td>
  </tr>
</table>

<h2>🛠️ Tecnologías</h2>

<ul>
  <li><b>HTML5</b>: estructura de la página</li>
  <li><b>CSS3</b>: variables, Flexbox y media queries</li>
  <li><b>jQuery 3.7.1</b>: menú desplegable en celular</li>
  <li><b>Font Awesome 7.0.1</b>: ícono del menú</li>
</ul>

<h2>📁 Estructura</h2>

<pre>
├── index.html
├── styles.css
└── assets/
    ├── logo_arriba.png
    ├── logo_abajo.png
    ├── foto_slide.jpg
    ├── icono1.png
    ├── icono2.png
    └── icono3.png
</pre>

<h2>🧩 Secciones</h2>

<table>
  <thead>
    <tr>
      <th>Sección</th>
      <th>Clase</th>
      <th>Contenido</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Encabezado</td>
      <td><code>.encabezado</code></td>
      <td>Logo y menú de navegación</td>
    </tr>
    <tr>
      <td>Portada</td>
      <td><code>.portada</code></td>
      <td>Imagen de fondo con el título principal</td>
    </tr>
    <tr>
      <td>Servicios</td>
      <td><code>.servicios</code></td>
      <td>Tres tarjetas con ícono, título y descripción</td>
    </tr>
    <tr>
      <td>Pie de página</td>
      <td><code>.pie</code></td>
      <td>Logo y datos del autor</td>
    </tr>
  </tbody>
</table>

<p>
  Las clases usan nombres sencillos en español. Las partes de un mismo bloque comparten prefijo,
  por ejemplo <code>tarjeta</code>, <code>tarjeta-icono</code>, <code>tarjeta-titulo</code> y <code>tarjeta-texto</code>.
  La clase <code>.ancho</code> limita el contenido a 1200px y lo centra.
</p>

<h2>📱 Diseño responsivo</h2>

<p>En pantallas de hasta <b>480px</b>:</p>

<ul>
  <li>El menú se oculta y aparece un botón de hamburguesa que lo abre y cierra con <code>slideToggle()</code> de jQuery.</li>
  <li>Las tarjetas de servicios se acomodan en una sola columna.</li>
  <li>Los títulos y textos se hacen más pequeños.</li>
</ul>

<h2>🚀 Cómo verlo</h2>

<ol>
  <li>Descarga o clona el repositorio.</li>
  <li>Abre <code>index.html</code> en el navegador, o usa la extensión <b>Live Server</b> de VS Code.</li>
</ol>

<blockquote>
  <p>Se necesita conexión a internet para cargar jQuery y Font Awesome desde sus CDN.</p>
</blockquote>
