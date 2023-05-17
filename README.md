<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/7846fa448f.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="./css/style.css">
    <title>Portfolio de Lautaro Figliuolo</title>
</head>
<body>
  <article>
      <!-- MENU DE NAVEGACION-->        
      <nav class="menu">
          <ul class="menu2">
            <li><a href="#sobreMi">SOBRE MÍ</a> </li>
            <li><a href="#skills">SKILLS</a></li>
            <li><a href="#inicio">REDES</a></li>
            <li><a href="#contacto">CONTACTAR</a> </li>
          </ul>
        </nav>
      <!--FIN MENU DE NAVEGACION--> 

      <!--BLOQUE DE INICIO-->
      <section id="inicio" >
          <h2 >Lautaro Figliuolo</h2>
          <h3 class="hastag">#Estudiante</h3>     
          <h3 class="hastag">#Programador</h3>
          <ul id="redes">
            <li><a href="https://www.instagram.com/lautarofigliuolo/" target="_blank"><i class="fa-brands fa-instagram"></i></a></li>
            <li><a href="https://twitter.com/TatoFigliuolo" target="_blank"><i class="fa-brands fa-twitter"></i></a></li>
            <li><a href=""  target="_blank"><i class="fa-brands fa-linkedin" ></i></a></li><!--Todavia no tengo perfil-->
          </ul>
      </section>
      <!--FIN BLOQUE DE INICIO-->

      <!--BLOQUE DE SOBRE MI-->
      <section id="sobreMi">
          <h2>SOBRE MÍ</h2>
          <div class="filaSobreMi">
            <div>
              <img src="imagenes/perfil.jpg" alt="Foto de perfil" id="foto">
            </div>
            <div>
              <p>Soy <strong>Lautaro Figliuolo</strong>, tengo 23 años y actualmente estoy cursando la carrera Lic. en informatica y desarrollo de software en la universidad Aconcangua de Mendoza, Argentina. <br> Soy estudiante con conocimientos adquiridos en diversos lenguajes de programación y habilidades en el desarrollo de programas, aplicaciones y páginas web. <br> Me considero una persona comprometida con la excelencia y la calidad en cada uno de mis proyectos. <br>
              Mi filosofía de trabajo se basa en el aprendizaje continuo y el trabajo en equipo. Me encanta colaborar y compartir conocimientos con otros profesionales, ya que creo que el trabajo en equipo puede producir soluciones más eficientes e innovadoras. <br>
              Además, estoy siempre en constante aprendizaje, investigando y estudiando nuevas tecnologías y tendencias en informática y software, para estar actualizado en un mundo en constante evolución.</p>
            </div>
          </div>
      </section>
      <!-- FIN BLOQUE DE SOBRE MI-->

      <!--BLOQUE DE PORTFOLIO-->
      <section id="skills">
        <center><h2>Experiencia & Skills</h2></center>
        <div class="filaSkills">
            <div class="card">
                <img src="imagenes/card0.jpg" alt="Portfolio 1">
                <h3>HTML y CSS</h3>
                <h4>Avanzado</h4>
                <div class="sep"></div>
                <p>2 años de experiencia.</p><br>
            </div>
            <div class="card">
                <img src="imagenes/card1.jpg" alt="Portfolio 2">
                <h3>JS</h3>
                <h4>Medio</h4>
                <div class="sep"></div>
                <p>Menos de 1 año de experiencia.</p>
            </div>
            <div class="card">
                <img src="imagenes/card2.jpg" alt="Portfolio 3">
                <h3>PHP</h3>
                <h4>Avanzado</h4>
                <div class="sep"></div>
                <p>Mas de 1 año de experiencia.</p>
            </div>
            <div class="card">
                <img src="imagenes/card3.jpg" alt="Portfolio 4">
                <h3>MySQL</h3>
                <h4>Avanzado</h4>
                <div class="sep"></div>
                <p>1 año de experiencia.</p>              
            </div>
        </div>
      </section>
      <!-- FIN BLOQUE DE PORTFOLIO-->

      <!--BLOQUE DE CONTACTO-->
      <section id="contacto">
        <center>
        <div>
          <h2>CONTACTAR</h2>
          <h3>Enviame tus dudas.</h3>   
        </div>
        </center>
        <form action="#" id="formulario">
          <div class="itemform">
            <label for="nombre">Nombre:</label> 
            <input type="text" name="nombre" id="nombre" required> 
          </div>
          <div class="itemform">
            <label for="apellido">Apellido:</label>
            <input type="text" name="apellido" id="apellido" required> 
          </div>
          <div class="itemform">
            <label for="empresa">Empresa:</label>
            <input type="text" name="empresa" id="empresa"> 
          </div>
          <div class="itemform">
            <label for="email">Email:</label>
            <input type="email" name="email" id="email" required>
          </div>
          <div class="itemform">
            <label for="Mensaje">Mensaje:</label>
            <textarea name="mensaje" id="mensaje" cols="33" rows="5"></textarea>
          </div>
          <div class="itemform" id="boton">
            <input type="submit" value="CONTACTAR">
          </div>
        </form>
      </section>
      <!--FIN BLOQUE DE CONTACTO-->
  </article>
</body>
</html>
