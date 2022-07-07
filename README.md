# Visualización 3D de un cráneo en OpenGL

## Dependencias

El proyecto fue desarrollado en Visual Studio. Para ejecutarlo es necesario contar con Visual Studio y haber instalado las siguientes librerias:

* GLFW
* GLAD
* OpenGL

La generación del modelo fue hecha con Python. Las librerías utilizadas en la generación se puede installar con el administrador de paquetes [Poetry](https://python-poetry.org/).

## Cómo Usar

### Generación del modelo

Para generar de nuevo el modelo `.obj` se utiliza el Jupyter Notebook de la carpeta `ModelGeneration`. El archivo resultante `skull.obj` debe ser copiado a `Triangulation/resources/models/skull/skull.obj`.

### Visualización

El proyecto de la carpeta `Triangulation` ya cuenta con todo listo para visulizar el modelo `skull.obj`, solo basta con correr la solución desde Visual Studio.