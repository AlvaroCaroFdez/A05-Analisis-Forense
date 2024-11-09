author: Álvaro Caro Fernández summary: Realizar la adquisición forense de una memoria USB empleando las siguientes herramientas: FTK Imager, GuyImager y dd id: Actividad 05 categories: codelab,markdown environments: Web status: Publicado

# Actividad 05

## Introducción

La adquisición forense de una memoria USB es un proceso crítico en la informática forense, diseñado para recopilar y preservar evidencias digitales de manera integra y auténtica. Este proceso implica crear una copia exacta del contenido de la memoria USB, incluyendo datos eliminados y espacios de memoria libres, sin modificar el dispositivo original. La integridad de la evidencia es fundamental, por lo que es esencial evitar cualquier modificación accidental durante el proceso.

Para realizar esta tarea, se utilizan herramientas especializadas como FTK Imager, GuyImager y 'dd'. FTK Imager, desarrollado por AccessData, es una herramienta poderosa que permite seleccionar el dispositivo a imagenar y elegir el formato de la imagen, como E01. GuyImager, por otro lado, es una herramienta de código abierto que ofrece opciones para la compresión y fragmentación de la imagen. dd, una herramienta de línea de comandos en sistemas Unix-like, es muy versátil y se utiliza comúnmente para crear imágenes raw de dispositivos.

## FTK Imager

FTK Imager es una herramienta forense digital desarrollada por AccessData, utilizada para adquirir, examinar y analizar datos de dispositivos de almacenamiento digital. Permite crear imágenes forenses de dispositivos como discos duros, unidades USB y tarjetas de memoria, realizando una copia bit a bit del contenido para preservar la integridad de los datos originales. También facilita la verificación de la integridad de la imagen, la búsqueda de palabras clave y la extracción de archivos específicos. Es una herramienta esencial en la informática forense para obtener evidencia digital válida en investigaciones y procesos legales

