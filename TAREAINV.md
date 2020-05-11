JOSE ISRAEL ESPINOZA HARO
TAREA SESION 3.

INVESTIGAR LAS SIGUIENTES ETIQUETAS HTML;

A. <label></label>
    CREA UNA ETIQUETA, SE PUEDE UTILIZAR PARA FORMULARIOS, PARA UTILIZARSE EN LOS FORMULARIOS HTML.

        EJEMPLO:

        <form action="/action_page.php">
            <label for="casado">Casado</label>
            <input type="radio" name="edocivil" id="casado" value="casado"><br>
            <label for="soltero">Soltero</label>
            <input type="radio" name="edocivil" id="soltero" value="soltero"><br>
            <label for="otro">Otro</label>
            <input type="radio" name="edocivil" id="otro" value="otro"><br><br>
            <input type="submit" value="Enviar">
    </form>

B. <pre></pre>

    INDICA A LOS NAVEGADORES QUE DEBEN RESPETAR LOS SALTOS DE LÍNEA Y LOS ESPACIOS EN BLANCO DE UN DOCUMENTO PERO NO RESPETA LOS CARACTERES ESPECIALES. TAMBIÉN FORMATEA EL TEXTO EN UNA TIPOGRAFÍA TIPO MONOESPACE.

        EJEMPLO:
        

         <pre> TEXTO CON FORMATO PRE </pre>

C. <br>
    PERMITE AGREGAR UN SALTO DE LINEA, CON LA FINALIDAD DE HACER EL TEXTO MAS LEGIBLE.

        EJEMPLO:

        <h1>Se muestra un salto de linea html <br> continua en la linea de abajo </h1>

D. <table></table>
    PERMITE CREAR UNA TABLA EN HTML, SE COMPLEMENTA DE LAS ETIQUETAS:
        <tr></tr> CREA UNA FILA DE LA TABLA
        <th></th> CREA LOS TITULOS DE LAS COLUMAS
        <td></td> CREA UN REGISTRO DE LA TABLA

        EJEMPLO:

        <table>
            <tr>
                <th>Nombre</th>
                <th>Apellidos</th>
            </tr>
  
            <tr>
                <td>Israel</td>
                <td>Espinoza</td>
            </tr>
  
            <tr>
                <td>Regina</td>
                <td>Espinoza</td>
            </tr>
        </table>

