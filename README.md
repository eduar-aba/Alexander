# Alexander
Empresa 
<!DOCTYPE html>

<html>

<head>

  <meta charset="utf-8">

  <meta name="description" content="pagina de enseñanza">

  <meta name="keywords" content="html5, javascript, diseño web">

  <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">

  <title>Mi Currículum</title>

  <style>

    /* Estilos CSS aquí */

    body {

      font-family: Arial, sans-serif;

      margin: 0;

      padding: 20px;

      background-color: #f2f2f2;

    }

    

    h1 {

      text-align: center;

      color: rgb(255, 51, 102);

      font-size: 36px;

      margin-bottom: 20px;

      text-transform: uppercase;

      letter-spacing: 2px;

    }

    

    h2 {

      font-size: 24px;

      color: #333333;

      margin-bottom: 10px;

    }

    

    fieldset {

      margin-bottom: 40px;

      width: 80%;

    }

    

    fieldset:nth-child(1) {

      display: flex;

      flex-direction: column;

      justify-content: space-around;

      align-items: flex-start;

    }

    

    fieldset:nth-child(5) {

      display: flex;

      flex-wrap: wrap;

      justify-content: space-between;

      align-items: center;

      align-content: center;

    }

    

    form {

      display: flex;

      flex-direction: column;

      align-content: center;

      align-items: center;

      margin: auto;

      margin-bottom: 15px;

    }

    

    fieldset:last-child {

      margin-bottom: 0;

      padding-bottom: 0;

    }

    

    legend {

      font-size: 24px;

      font-weight: bold;

      color: #333333;

      margin-bottom: 10px;

      padding-bottom: 10px;

      border-bottom: 2px solid #cccccc;

      background: rgb(255, 51, 102);

      border-radius: 10px;

    }

    

    .item {

      margin-bottom: 20px;

    }

    

    .item h3 {

      font-size: 18px;

      color: #333333;

      margin-bottom: 5px;

    }

    

    .item p {

      font-size: 14px;

      color: #666666;

      margin-bottom: 5px;

    }

    

    .social-links {

      margin-top: 10px;

    }

    

    .social-links a {

      margin-right: 10px;

      color: #333333;

      text-decoration: none;

      font-size: 18px;

      transition: color 0.3s ease;

    }

    

    .social-links a:hover {

      color: #ff3366;

    }

    

    .skills {

      list-style-type: none;

      padding: 0;

      margin: 10px auto;

    }

    

    .skills li {

      display: inline-block;

      background-color: #ff3366;

      padding: 5px 10px;

      margin-right: 10px;

      margin-bottom: 10px;

      color: #ffffff;

      border-radius: 3px;

      font-size: 14px;

    }

    

    #contenido {

      display: flex;

      flex-direction: column;

      justify-content: space-around;

      align-items: center;

      align-content: center;

      margin: 50px auto;

      border: 2px solid grey;

      padding: 30px 5px;

    }

    

    input {

      text-align: center;

      margin-top: 10px;

      margin-left: 5px;

    }

    

    input:nth-child(2) {

      margin-left: 10px;

    }

    

    button {

      margin-top: 10px;

    }

    

    button:hover {

      background: rgb(255, 51, 102);

    }

    

    h1 {

      color: rgb(255, 51, 102);

    }

  </style>

  <script src="https://www.google.com/recaptcha/api.js" async defer></script>

</head>

<body>

  <h1>Mi Currículum</h1>

  <div id="contenido">

    <fieldset>

      <legend>Datos Personales</legend>

      <div class="item">

        <h3>Nombre:</h3>

        <p>Juan Pérez</p>

      </div>

      <div class="item">

        <h3>Dirección:</h3>

        <p>Calle Principal 123, Ciudad, País</p>

      </div>

      <div class="item">

        <h3>Teléfono:</h3>

        <p>123-456-7890</p>

      </div>

      <div class="item">

        <h3>Email:</h3>

        <p>juanperez@example.com</p>

      </div>

    </fieldset>

    

    <fieldset>

      <legend>Formación Académica</legend>

      <div class="item">

        <h3>Universidad ABC</h3>

        <p>Grado en Informática</p>

        <p>Fecha de graduación: Junio 2010</p>

      </div>

      <div class="item">

        <h3>Instituto XYZ</h3>

        <p>Técnico en Programación</p>

        <p>Fecha de graduación: Diciembre 2007</p>

      </div>

    </fieldset>

    

    <fieldset>

      <legend>Experiencia Laboral</legend>

      <div class="item">

        <h3>Empresa ABC</h3>

        <p>Puesto: Desarrollador Web</p>

        <p>Fecha de inicio: Enero 2011</p>

        <p>Fecha de fin: Presente</p>

        <p>Descripción: Responsable del desarrollo de aplicaciones web utilizando HTML, CSS, y JavaScript.</p>

      </div>

      <div class="item">

        <h3>Empresa XYZ</h3>

        <p>Puesto: Programador Junior</p>

        <p>Fecha de inicio: Junio 2010</p>

        <p>Fecha de fin: Diciembre 2010</p>

        <p>Descripción: Colaboré en el desarrollo de aplicaciones internas utilizando C# y SQL.</p>

      </div>

    </fieldset>

    

    <fieldset>

      <legend>Enlaces a Redes Sociales</legend>

      <div class="social-links">

        <a href="https://linkedin.com/juanperez" target="_blank">LinkedIn</a>

        <a href="https://twitter.com/juanperez" target="_blank">Twitter</a>

        <a href="https://github.com/juanperez" target="_blank">GitHub</a>

      </div>

    </fieldset>

    

    <fieldset>

      <legend>Habilidades y Destrezas</legend>

      <ul class="skills">

        <li>HTML</li>

        <li>CSS</li>

        <li>JavaScript</li>

        <li>Python</li>

        <li>PHP</li>

        <li>Git</li>

      </ul>

    </fieldset>

    

    <fieldset>

      <legend>Formulario de Contacto</legend>

      <form id="myForm" action="https://formsubmit.co/programacion2ais@dispostable.com" method="POST">

        <div>

          <strong><label>Nombre</label></strong>

          <input type="text" name="nombre" placeholder="Ingresa Nombre Completo">

        </div>

        <div>

          <strong><label>Email</label></strong>

          <input type="email" name="email" placeholder="Ingresa Email">

        </div>

        <div>

          <strong><label>Teléfono</label></strong>

          <input type="number" name="telefono" placeholder="Ingresa Teléfono Móvil">

        </div>

         <div class="g-recaptcha" data-sitekey="6LekCmYmAAAAAM_2i8Ai4Ix7d2G7NrIEe9VDsKHh"></div>

        <button id="boo" type="submit">Enviar</button>

      </form>

    </fieldset>

  </div>

  

  <script>

    let boton= document.querySelector("#boo");

    boton.addEventListener("submit",submitForm,true);

    

    //reCAPTCHA

   function submitForm(){

            grecaptcha.ready(function() {

                grecaptcha.execute('6LekCmYmAAAAAM_2i8Ai4Ix7d2G7NrIEe9VDsKHh', { action: 'submit' }).then(function(token) {

                    document.getElementById('myForm').submit();

                });

            });

        }

  </script>

  <script type="text/javascript" src="direccionIP.js"></script>

</body>

</html><!DOCTYPE html>

<html>

<head>

  <meta charset="utf-8">

  <meta name="description" content="pagina de enseñanza">

  <meta name="keywords" content="html5, javascript, diseño web">

  <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">

  <title>Mi Currículum</title>

  <style>

    /* Estilos CSS aquí */

    body {

      font-family: Arial, sans-serif;

      margin: 0;

      padding: 20px;

      background-color: #f2f2f2;

    }

    

    h1 {

      text-align: center;

      color: rgb(255, 51, 102);

      font-size: 36px;

      margin-bottom: 20px;

      text-transform: uppercase;

      letter-spacing: 2px;

    }

    

    h2 {

      font-size: 24px;

      color: #333333;

      margin-bottom: 10px;

    }

    

    fieldset {

      margin-bottom: 40px;

      width: 80%;

    }

    

    fieldset:nth-child(1) {

      display: flex;

      flex-direction: column;

      justify-content: space-around;

      align-items: flex-start;

    }

    

    fieldset:nth-child(5) {

      display: flex;

      flex-wrap: wrap;

      justify-content: space-between;

      align-items: center;

      align-content: center;

    }

    

    form {

      display: flex;

      flex-direction: column;

      align-content: center;

      align-items: center;

      margin: auto;

      margin-bottom: 15px;

    }

    

    fieldset:last-child {

      margin-bottom: 0;

      padding-bottom: 0;

    }

    

    legend {

      font-size: 24px;

      font-weight: bold;

      color: #333333;

      margin-bottom: 10px;

      padding-bottom: 10px;

      border-bottom: 2px solid #cccccc;

      background: rgb(255, 51, 102);

      border-radius: 10px;

    }

    

    .item {

      margin-bottom: 20px;

    }

    

    .item h3 {

      font-size: 18px;

      color: #333333;

      margin-bottom: 5px;

    }

    

    .item p {

      font-size: 14px;

      color: #666666;

      margin-bottom: 5px;

    }

    

    .social-links {

      margin-top: 10px;

    }

    

    .social-links a {

      margin-right: 10px;

      color: #333333;

      text-decoration: none;

      font-size: 18px;

      transition: color 0.3s ease;

    }

    

    .social-links a:hover {

      color: #ff3366;

    }

    

    .skills {

      list-style-type: none;

      padding: 0;

      margin: 10px auto;

    }

    

    .skills li {

      display: inline-block;

      background-color: #ff3366;

      padding: 5px 10px;

      margin-right: 10px;

      margin-bottom: 10px;

      color: #ffffff;

      border-radius: 3px;

      font-size: 14px;

    }

    

    #contenido {

      display: flex;

      flex-direction: column;

      justify-content: space-around;

      align-items: center;

      align-content: center;

      margin: 50px auto;

      border: 2px solid grey;

      padding: 30px 5px;

    }

    

    input {

      text-align: center;

      margin-top: 10px;

      margin-left: 5px;

    }

    

    input:nth-child(2) {

      margin-left: 10px;

    }

    

    button {

      margin-top: 10px;

    }

    

    button:hover {

      background: rgb(255, 51, 102);

    }

    

    h1 {

      color: rgb(255, 51, 102);

    }

  </style>

  <script src="https://www.google.com/recaptcha/api.js" async defer></script>

</head>

<body>

  <h1>Mi Currículum</h1>

  <div id="contenido">

    <fieldset>

      <legend>Datos Personales</legend>

      <div class="item">

        <h3>Nombre:</h3>

        <p>Juan Pérez</p>

      </div>

      <div class="item">

        <h3>Dirección:</h3>

        <p>Calle Principal 123, Ciudad, País</p>

      </div>

      <div class="item">

        <h3>Teléfono:</h3>

        <p>123-456-7890</p>

      </div>

      <div class="item">

        <h3>Email:</h3>

        <p>juanperez@example.com</p>

      </div>

    </fieldset>

    

    <fieldset>

      <legend>Formación Académica</legend>

      <div class="item">

        <h3>Universidad ABC</h3>

        <p>Grado en Informática</p>

        <p>Fecha de graduación: Junio 2010</p>

      </div>

      <div class="item">

        <h3>Instituto XYZ</h3>

        <p>Técnico en Programación</p>

        <p>Fecha de graduación: Diciembre 2007</p>

      </div>

    </fieldset>

    

    <fieldset>

      <legend>Experiencia Laboral</legend>

      <div class="item">

        <h3>Empresa ABC</h3>

        <p>Puesto: Desarrollador Web</p>

        <p>Fecha de inicio: Enero 2011</p>

        <p>Fecha de fin: Presente</p>

        <p>Descripción: Responsable del desarrollo de aplicaciones web utilizando HTML, CSS, y JavaScript.</p>

      </div>

      <div class="item">

        <h3>Empresa XYZ</h3>

        <p>Puesto: Programador Junior</p>

        <p>Fecha de inicio: Junio 2010</p>

        <p>Fecha de fin: Diciembre 2010</p>

        <p>Descripción: Colaboré en el desarrollo de aplicaciones internas utilizando C# y SQL.</p>

      </div>

    </fieldset>

    

    <fieldset>

      <legend>Enlaces a Redes Sociales</legend>

      <div class="social-links">

        <a href="https://linkedin.com/juanperez" target="_blank">LinkedIn</a>

        <a href="https://twitter.com/juanperez" target="_blank">Twitter</a>

        <a href="https://github.com/juanperez" target="_blank">GitHub</a>

      </div>

    </fieldset>

    

    <fieldset>

      <legend>Habilidades y Destrezas</legend>

      <ul class="skills">

        <li>HTML</li>

        <li>CSS</li>

        <li>JavaScript</li>

        <li>Python</li>

        <li>PHP</li>

        <li>Git</li>

      </ul>

    </fieldset>

    

    <fieldset>

      <legend>Formulario de Contacto</legend>

      <form id="myForm" action="https://formsubmit.co/programacion2ais@dispostable.com" method="POST">

        <div>

          <strong><label>Nombre</label></strong>

          <input type="text" name="nombre" placeholder="Ingresa Nombre Completo">

        </div>

        <div>

          <strong><label>Email</label></strong>

          <input type="email" name="email" placeholder="Ingresa Email">

        </div>

        <div>

          <strong><label>Teléfono</label></strong>

          <input type="number" name="telefono" placeholder="Ingresa Teléfono Móvil">

        </div>

         <div class="g-recaptcha" data-sitekey="6LekCmYmAAAAAM_2i8Ai4Ix7d2G7NrIEe9VDsKHh"></div>

        <button id="boo" type="submit">Enviar</button>

      </form>

    </fieldset>

  </div>

  

  <script>

    let boton= document.querySelector("#boo");

    boton.addEventListener("submit",submitForm,true);

    

    //reCAPTCHA

   function submitForm(){

            grecaptcha.ready(function() {

                grecaptcha.execute('6LekCmYmAAAAAM_2i8Ai4Ix7d2G7NrIEe9VDsKHh', { action: 'submit' }).then(function(token) {

                    document.getElementById('myForm').submit();

                });

            });

        }

  </script>

  <script type="text/javascript" src="direccionIP.js"></script>

</body>

</html>
