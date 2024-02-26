Frame marker es una herramienta en python para etiquetar fotografías y posteriormente cargarlas en GIS o Google Earth generando un archivo formato kmz desde el ambiente de Google Colab. Forma parte de la recopilación de comandos con el objetivo de desarrolar habilidades en lo que considero "las macros modernas". 

Con esta herramienta se automatiza el etiquetado de fecha, hora, coordenadas geográficas y el estacionamiento PKM. Esto se logra calculando la distancia acumulada entre cada fotografía (ecuación de distancia entre 2 puntos), es indispensable que las imágenes sean tomadas con coordenadas con el menor espaciamiento posible.

Los resultados son responsabilidad del usuario.

Este proyecto de Python se enfoca en el manejo y procesamiento de imágenes, especialmente aquellas capturadas con información de telemetría incrustada, como coordenadas GPS, fecha y hora. La aplicación ofrece varias funcionalidades útiles para organizar, manipular y visualizar este tipo de imágenes. A continuación, se presenta un resumen de las principales características y funcionalidades de la aplicación:

### Características Principales:

**I. Instalación de Librerías:**
Se instalan las librerías necesarias para el procesamiento de imágenes, incluyendo exifread, piexif, geopy, rarfile, y Pillow.

**II. Configuración de Carpetas de Trabajo:**
Se configuran las carpetas donde se almacenarán las imágenes originales y las imágenes procesadas.

**III. Redimensionamiento y Preservación de Datos EXIF:**
Las imágenes se redimensionan a un tamaño específico mientras se preservan los datos EXIF, como la información de la cámara y la fecha de captura.

**IV. Ordenamiento de Imágenes por Fecha y Hora:**
Las imágenes se renombran secuencialmente basándose en su fecha y hora de captura para facilitar su ordenamiento.

**V. Generación de Información y Distancias en Excel:**
Se crea un archivo Excel que contiene información detallada de cada imagen, incluyendo coordenadas geográficas, altitud, fecha y hora de captura, así como distancias acumuladas.

**VI. Marcado de Fotografías:**
Se agrega información adicional a las imágenes procesadas, como coordenadas geográficas, fecha y hora de captura, y referencia kilométrica.

**VII. Generación de Mapas GIS:**
Se crea un mapa interactivo con marcadores para visualizar las imágenes en función de sus coordenadas geográficas, utilizando la biblioteca Folium.

**VIII. Creación de KMZ con Imágenes Incrustadas:**
Se genera un archivo KMZ que contiene las imágenes junto con su información geográfica incrustada, permitiendo su visualización en programas como Google Earth.

