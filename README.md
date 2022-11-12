# DII_P1.1_FERNANDO_CASTELLANOS_PRADA
Práctica 1.1 Desarrollo de interfaces.
Desarrolla una aplicación web en Java que conste de un formulario para realizar un login
siguiendo la siguiente descripción:
1. Como vista principal de la aplicación existe un fichero index.jsp, que se encuentra
en el raíz del proyecto y al que se accede directamente a través de la URL base.
Este fichero de entrada está formado por un formulario que contiene 3 cajas de
texto (input), 1 de tipo texto (text), para recoger el nombre del usuario (user), y 2
de tipo contraseña (password), para recoger el valor de la contraseña dos veces y
realizar un doble check (pass y pass2). Además cuenta con un botón para el envío
de los datos al Servlet.
2. Crea la clase de mapeo Usuario, con los atributos necesarios para almacenar los
datos (3 campos) y poder operar con ellos posteriormente a través de los objetos
de tipo Usuario que se crean con los datos recogidos del formulario.
3. El Servlet recoge los datos del formulario, a través de los parámetros (atributo
‘name’ de los inputs), y se mapean con la clase Usuario, que contiene los atributos
de tipo cadena user, pass y pass2.
4. En el caso de coincidir los valores de los dos campos de tipo contraseña, se
muestra una nueva vista con un mensaje, saludando al usuario por su nombre (por
ejemplo: “Hola X”, siendo X el valor correspondiente al parámetro user, recogido a
través del formulario de la vista principal).
5. Si las contraseñas no coinciden, se muestra una nueva vista con un mensaje,
advirtiendo al usuario del error e invitándole a volver a introducir correctamente
las contraseñas.
6. Realiza la modificación correspondiente para que el mensaje de error se genere en
la misma vista dónde se encuentre el formulario (index.jsp).
