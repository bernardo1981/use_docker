Explicación del ejemplo:

Creamos una estructura de proyecto simple con tres archivos: app.py, requirements.txt y Dockerfile.
app.py contiene una aplicación Flask básica que muestra un mensaje.
requirements.txt especifica las dependencias del proyecto.
El Dockerfile define cómo construir la imagen Docker:

Usa una imagen base de Python 3.9.
Copia los archivos necesarios al contenedor.
Instala las dependencias.
Especifica el comando para ejecutar la aplicación.



Para usar este ejemplo:

Crea los archivos con el contenido proporcionado.
Abre una terminal en el directorio del proyecto.
Construye la imagen con docker build -t mi-app-flask .
Ejecuta el contenedor con docker run -p 5000:5000 mi-app-flask
Abre un navegador y visita http://localhost:5000 para ver la aplicación en funcionamiento.

Este ejemplo te muestra cómo Docker puede encapsular una aplicación y sus dependencias en un contenedor portátil y fácil de ejecutar.
¿Te gustaría que profundice en algún aspecto específico de Docker o que explique alguna parte del ejemplo en más detalle?