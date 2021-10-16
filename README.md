# ApiRestConDjango
1. se crea el entorno virtual con 
# python -m venv env
2. se activa el entorno virtual con
# .\env\Scripts\activate
3. Se configura el archivo setting.py para la conexion a la base de datos
4. en el archivo model.py se crear el modelo de las tablas de la base de datos
5. se debe instalar las librerias
# pip install mysqlclient 
# pip install pymysql
6. se utiliza el comando 
# python manage.py migrate 
para migrar las tablas
7. se crea un acceso de administrador como super usuario
#python manage.py createsuperuser
8.Se realiza la migración del modelo
#python manage.py makemigrations
con este comando se crea una carpeta llamada migrations, en el archivo 0001_initial.py se encuentran los modelos 
9. Volvemos a ejecutar el comando de migrate
# python manage.py migrate
Con este comando se crea las tablas en nuestra base de datos
10. Ejecutamos el servidor con el comando
# python manage.py runserver
11. Se crea en view.py las vistas de las tablas con los metodos get, post, put y delete
12. Dentro de la carpeta api se crea un archivo url.py que contendra las rutas de nuestro proyecto


