# PROYECTO GRUPAL: ANALISIS Y VISUALIZACION DE DATOS DE LIBROS 

# Descripción General
Este proyecto consiste en extraer datos de libros desde la API de Google Books, transformarlos para realizar análisis de popularidad y almacenarlos en una base de datos SQL Server. Finalmente, se visualizarán los datos utilizando Python.

# Propósito
- Extraer datos de libros desde la API de Google Books.
- Transformar los datos para categorizar la popularidad de los libros.
- Almacenar los datos en una base de datos SQL Server.
-Realizar análisis y visualización de los datos de libros.

# Características Principales
- Extraer columnas relevantes como título, autor, año de publicación, popularidad, etc.

- Almacenar los datos crudos en una tabla llamada books en SQL Server.

- Clasificar la popularidad de los libros y guardar los resultados en una tabla llamada books_popularity.

- Visualizar los datos utilizando bibliotecas de visualización en Python.

# Requisitos Previos
- Python 3.8 o superior.
- Conexión activa a Internet.
- Credenciales de acceso a la API de Google Books.
- SQL Server instalado y configurado.
- Biblioteca de Python para conectarse a SQL Server (pyodbc o pymssql).
- Bibliotecas de Python para visualización de datos (pandas, matplotlib, seaborn).
  
# Instrucciones de Configuración
- Instalar Python y Bibliotecas Necesarias:
sh
pip install requests pyodbc pandas matplotlib seaborn

# Configurar SQL Server:
- Crear una base de datos en SQL Server.
- Crear las tablas books y books_popularity.
  
# ESTRUCTURA DEL PROYECTO

# Extracción de Datos:
Utilizar requests para obtener datos de libros desde la API de Google Books.

# Transformación de Datos:
Limpiar y transformar los datos utilizando pandas.

# Carga de Datos:
- Insertar los datos en SQL Server utilizando pyodbc.

# Análisis y Visualización:
- Realizar análisis y visualizaciones utilizando pandas, matplotlib y seaborn.

  ACLARO!: Dejo la Libertad de usar otras dependencias o extensiones que consideren! incluso las mejoras que deseaban aplicar en el proyecto anterior les invito a que puedan aplicar esas mejoras en este proyecto!, suerte. 
