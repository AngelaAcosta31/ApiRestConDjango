# ApiRestConDjango
1. se crea el entorno virtual con 
# python -m venv env
2. se activa el entorno virtual con
# .\env\Scripts\activate
3.se instala Django
# pip install Django==3.2.8
4. Se crea el proyecto Django con el comando
# django-admin startproject apiRest
5. Se accede a la ruta del proyecyo que acabamos de crear
6. Se crea una aplicacion con el comando
# django-admin startapp api 
8. En el archivo setting.py en INSTALLED_APPS se agrega la aplicacion, en este caso se llama api
9. Se configura el archivo setting.py para la conexion a la base de datos, en DATABASES
10. en el archivo model.py se crear el modelo de las tablas de la base de datos
11. se debe instalar las librerias
# pip install mysqlclient 
# pip install pymysql
12. se utiliza el comando 
# python manage.py migrate 
para migrar las tablas
13. se crea un acceso de administrador como super usuario
#python manage.py createsuperuser
14.Se realiza la migración del modelo
#python manage.py makemigrations
con este comando se crea una carpeta llamada migrations, en el archivo 0001_initial.py se encuentran los modelos 
15. Volvemos a ejecutar el comando de migrate
# python manage.py migrate
Con este comando se crea las tablas en nuestra base de datos
16. Ejecutamos el servidor con el comando
# python manage.py runserver
17. Se crea en view.py las vistas de las tablas con los metodos get, post, put y delete
18. Dentro de la carpeta api se crea un archivo url.py que contendra las rutas de nuestro proyecto


