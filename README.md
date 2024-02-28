"Frame marker" es una herramienta en python que permite automatizar el etiquetado de fecha, hora, coordenadas geográficas y el estacionamiento PKM. Esto se logra calculando la distancia acumulada entre cada fotografía (distancia entre 2 puntos), es indispensable que las imágenes sean secuenciadas (preferible a cada segundo) y contengan coordenadas geográficas. Los resultados son responsabilidad del usuario.

La herramienta se enfoca en el manejo y procesamiento de imágenes, especialmente aquellas capturadas con información de telemetría incrustada. "Frame maker", ofrece varias funcionalidades útiles para organizar, manipular y visualizar las imágenes. Para crear esta herramienta fue valioso contar con el apoyo del modelo IA de código abierto conocido como "LLAMA" desarrollada por META (facebook), lanzado a mediados del año 2023 con más de 13 billones de parámetros.

A continuación, se presenta un resumen de las principales características y funcionalidades:

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

El uso de la información asi como los resultados de la herramienta, son responsabilidad del usuario. 

La comunidad de Python se rige por el principio "open source". En este sentido, el uso de "Frame-Maker" no debe ser destinado con fines comerciales.

