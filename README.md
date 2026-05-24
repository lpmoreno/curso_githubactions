# Curso Github actions
# Laura Paneque Moreno

# Workflow para el ejecutar el CI del proyecto de frontend

En primer lugar creamos el archivo ci hangman-front.yaml con el siguiente contenido:

![Imagen 1.](Capturas/Captura2.png)

Lanzamos el CI desde Github y comprobamos que se ha producido un error.

![Imagen 2.](Capturas/Captura1.png)

Consultamos el detalle del error y podemos observar que ha fallado uno de los tests:

![Imagen 3.](Capturas/Captura3.png)

Corregimos el código, y volvemos a lanzar el ci, que finaliza correctamente:

![Imagen 4.](Capturas/Captura4.png)
![Imagen 5.](Capturas/Captura5.png)

# Workflow para el ejecutar el CD del proyecto de frontend

Pasamos ahora al continuous delivery.

Creamos el archivo que realizará el despliegue:


