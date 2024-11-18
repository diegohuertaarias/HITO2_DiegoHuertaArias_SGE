Requisitos 
- Python 3.x
- Tkinter
- pymysql
- openpyxl
1. Instalación de Python Asegúrate de tener instalado Python 3. (Puedes descargarlo desde (https://www.python.org/)).
2. Instalación de Tkinter Tkinter generalmente viene preinstalado con Python. Si no lo esta podrias tratar de poner Import Tkinter y dejar el puntero sobre el import y te saldra install package Tkinterº
3. Instalación de pymysql: Para instalar pymysql podrias hacer lo mismo que el caso anterior Import Tkinter y dejar el puntero sobre el import y te saldra install package pymysql
4. Instalación de openpyxl: Para instalar openpyxl podrias hacer lo mismo que el caso anterior Import Tkinter y dejar el puntero sobre el import y te saldra install package openpyxl
5. Instalación de MySQL
Descarga e instala MySQL desde MySQL.com  Sigue las instrucciones de instalación para tu sistema operativo.
Conexión de la Aplicación con MySQL
Configura la base de datos:

Abre MySQL y ejecuta la base de datos llamada encuestas que te he proporcionado en el github.

Despues de haber abierto todo abre el archivo de codigo que te pasé en el github y una vez ejecutado el sql en mysql deberias de cambiar esta fila de codigo que te paso ahora:
def obtener_conexion_db():
    # Establecer conexión con la base de datos
    return pymysql.connect(host="localhost", user="tu_usuario", password="tu_contraseña", database="encuestas")
personaliza esta parte a tu usuario de mysql y a tu contraseña del mismo.
Con esto estas listo para usar la aplicacion correctamente
