# CRUD de cursos

![crud_posts](/aplicacion1.jpg)

### Herramientas utilizadas

- Django 4
- Pillow (manejador de imagenes) 
- psycopg2 (conexión con bd postgres) 
- HTML + CSS + JS


### Video de referencia

[link](https://www.youtube.com/watch?v=ezIj71CX944)


#### Prueba

Para poder probar el proyecto localmente 

1. Asegurar tener un entorno virtual (virtualenv) 
2. descargar y descomprimir el proyecto
3. ingresar a la carpeta principal del proyecto y ejecutar el comando `pip install -r requirements.txt -v`
4. realizar la migración de la base de datos con `python manage.py migrate`
5. levantar el servidor local `python manange.py runserver`
6. ingresar a la ruta `http://127.0.0.1:8000/libros`
