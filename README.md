<html lang="es">
  <head>
    <title>AppDeGatos</title>
    <link href="style.css" rel="stylesheet">
  </head>
  <body background="jj.gif">
  
   
    <center><h1>AppDeGatos</h1></center>
    <main>
      <h3>Imágenes de Gatos:</h3>
      <!-- TODO: Agregar enlace a imágenes de gatos -->
      <p>Haz click aquí para ver más <a href="https://unsplash.com/es/images/animals/kitten" target="_blank" rel="noopener noreferrer">imágenes de gatos.</a></p>

      <a href="#" target="_blank" rel="noopener noreferrer"><img class="zoom"  src="https://bit.ly/fcc-relaxing-cat" alt="Un lindo gato naranja recostado sobre su espalda."></a>



      <h3>Listas de Gatos</h3>

      <div>
        <p><font size="5">Cosas Que Los Gatos Aman:</font></p>
        <ul>
          <li>Menta gatuna</li>
          <li>Apuntadores Láser</li>
          <li>Lasaña</li>
        </ul>
        <img src="https://images.pexels.com/photos/5949888/pexels-photo-5949888.jpeg?auto=compress&cs=tinysrgb&w=600" width="300" height="200" alt="Lasaña">
        <p><font size="5">Cosas que los gatos <strong>odian</strong>:</font></p>
        <ol>
          <li>Tratamientos antipulgas</li>
          <li>Truenos</li>
          <li>Otros gatos</li>
        </ol>
      </div>
      <img src="https://images.pexels.com/photos/617278/pexels-photo-617278.jpeg?auto=compress&cs=tinysrgb&w=600" width="300" height="200" alt="Gatos">
     <formulario acción="https://formsubmit.co/ byroncontreras551@gmail.com" método="POST">
        <tipo de entrada="texto" nombre="nombre" requerido>
        <tipo de entrada="correo electrónico" nombre="correo electrónico" requerido>
        <tipo de botón="enviar">Enviar</botón>
   </ formulario>
        <!-- Botones de Radio -->
        <label for="interior">
          <input id="interior" type="radio" value="interior" name="interior-exterior">Interior
        </label>
        <br>
        <label for="exterior">
          <input id="exterior" type="radio" value="exterior" name="interior-exterior">Exterior
        </label>
        <br>

    
    <h3>
      ¿Cómo suele ser su gato?</h3>
          <input type="checkbox">Amoroso
         
          
          <input type="checkbox">Peresoso

          
          
          <input type="checkbox">Enérgico

        
         
          <br>
        <input type="text" placeholder="URL de la foto de su gato" required><br>
    
     
        <div class="col">
          <div class="container">
            <h1>Cuentanos Acerca de ti </h1>
              <div class="form-group">
                <div class="mb-3">
                  <div class="col">
                    <input type="text" name="name" class="form-control" placeholder="Nombre Completo" required>
                  </div>
                  <div class="col">
                    <input type="email" name="email" class="form-control" placeholder="Escribe Tu Correo" required>
                  </div>
                </div>
              </div>
              <div class="form-group">
                <textarea placeholder="Dejanos Tu Comentario" class="form-control" name="message" rows="3" required></textarea>
              </div>
              <button type="submit" class="btn btn-lg btn-dark btn-block">Enviar</button>
            </form>
        <button type="reset">Limpiar</button><br>
      </form>
        <br>
        <font color="black">Toda la informacion respondida en este formulario es enviada a mi correo electronico, para cosultar informacion comunicarse conmigo  </font>
    </main>
    <br>
    <footer>
      <p><small>Sin Derechos de Autor - <a href="https://www.freecodecamp.org/espanol/">freeCodeCamp.org</a></small></p>
    </footer>
  </body>
</html>
