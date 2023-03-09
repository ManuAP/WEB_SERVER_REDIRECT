<!DOCTYPE html>
<html>
<body>
	<h1>Redirect server</h1>
	<p>Este es un script muy simple de Python que crea un servidor web que redirige cualquier solicitud a una URL específica. El servidor se ejecuta en el puerto 80 y en cualquier dirección IP disponible (0.0.0.0).</p>
  <h2>Uso</h2>
<p>Para utilizar este script, navega hasta el directorio donde se encuentra el archivo y ejecuta el siguiente comando:</p>
<pre><code>python3 redirect_server.py URL</code></pre>
<p>Donde URL es la dirección a la que deseas que se redirijan todas las solicitudes.</p>

<h2>Ejemplo de uso</h2>
<p>Supongamos que tienes un sitio web en la dirección "http://ejemplo.com" y deseas redirigir todas las solicitudes a un nuevo sitio web en la dirección "http://nuevo-ejemplo.com". Para hacer esto, debes ejecutar el siguiente comando en la terminal:</p>
<pre><code>python3 redirect_server.py http://nuevo-ejemplo.com</code></pre>
<p>Ahora, cualquier solicitud recibida por el servidor se redirigirá automáticamente a la URL "http://nuevo-ejemplo.com".</p>

<h2>Atribución</h2>
<p>Este script utiliza la librería http.server de Python para crear un servidor web y redirigir las solicitudes a una URL específica. Para más información sobre esta librería, puedes revisar la documentación oficial de Python.</p>
</body>
</html>
