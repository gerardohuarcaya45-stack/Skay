<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Hola mundo</title>
    <style>
      #titulo {
        color: blue;
      }
      .preguntas {
        font-family: Arial;
        color: green;
      }
    </style>
  </head>
  <body>
    <h1 id="titulo"><u>CUESTIONARIO</u></h1>
    <label>Ingresa tu correo electrónico</label>
    <input type="correo" name="correo">
    <br>
    <input type="radio" name="genero"> Hombre
    <input type="radio" name="genero"> Mujer
    <div>
      <p>Bienvenido a esta página web dónde <b>te encontrarás a tí mismo</b></p>
    </div>
  <form>
    <ol>
      <li class="preguntas">¿Cómo te sientes hoy?<input type="text" placeholder="Escribe"></li>
      <li class="preguntas">¿Por qué te sientes así?<input type="text" placeholder="Escribe"></li>
      <li class="preguntas">¿Qué te gustó más del día?<input type="text" placeholder="Escribe"></li>
      <li class="preguntas">¿Qué menos te gustú del día?<input type="text" placeholder="Escribe"></li>
    </ol>
    <li><button id="boton">Bien</button></li>
    <li><button id="buton">Mal</button></li>
  </form>

  </body>
</html>

