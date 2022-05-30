# COLORIZACIÓN

**Proyecto Creado por:**<br />
Miguel Vizcaíno, Sebastián Rodríguez e Itzel Acosta<br />

**Para la clase de:**<br />
Robótica Industrial, Enero-Mayo 2022<br />

**Del profesor:**<br />
Dr. Michel Emanuel López Franco<br />

![image](https://user-images.githubusercontent.com/75276451/119406751-d6405500-bca8-11eb-8dd3-9c66b2d0cb48.png)

## Acerca De

El objetivo de este proyecto es agregar color a imágenes en blanco y negro mediante una aplicación de machine learning.
Esto puede aplicarse a fotografía profesional, trayendo color a fotos que se tomaron originalmente en blanco y negro, por ejemplo fotografías antiguas.<br />

## Desarrollo del proyecto
Para realizar este proyecto, utilizamos la biblioteca de código abierto de OpenCV para el aprendizaje automático y nos basamos en un modelo preentrenado.<br />

En el script se descarga el modelo preentrenado y se configura para solamente esperar a ingresar una imagen, al ingresarla se hace el procesamiento con base en el modelo preentrenado y se obtiene una imagen a color, a diferencia de la insertada en blanco y negro.

##  Configuración y Ejecución:
Para correr este script se deben seguir los pasos descritos a continuación:<br />
1. Descargar el siguiente archivo: https://drive.google.com/u/0/uc?id=18oCbYziNsml5JE5yptxO7PHJao_aaFol&export=download y ponerlo en la carpeta de "models" dentro del repositorio.<br />
2. Instalar las librerías "numpy" y "opencv" en caso de no tenerlas. Esto se consigue ejecutando los siguientes códigos en la terminal:<br />
pip install numpy<br />
pip install opencv-python<br />
3. Cambiar el path de la imagen en la variable "image_path".<br />
4. Ejecutar el código.<br />
5. ¡Listo! La imagen ahora tiene color.<br />

##  Ejemplos de uso:
![image](https://github.com/Henoven/colorize/blob/main/Resultados/Res_Africa1.png) ![image](https://github.com/Henoven/colorize/blob/main/Resultados/Paisaje.png) ![image](https://github.com/Henoven/colorize/blob/main/Resultados/Res_Villa.png)
