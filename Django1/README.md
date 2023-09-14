# Backend RedRegister

## Como ejecutar en desarrollo?
1. Descargar el repositorio y ubicarnos en la rama de backend.

#### `git clone https://github.com/URSScript/RedRegister.git`

2. Ingresar a la carpeta del backend.

#### `cd ./backend`

3. Instalar el entorno virtual en python.

#### `pip install virtualenv`

4. Crear el entorno virtual.

#### `virtualenv venv`

5. Activar el entorno virtual

#### `.\venv\Scripts\activate`

6. Instalar los siguientes paquetes.

#### `pip install django`
#### `pip install djangorestframework`
#### `pip install django-cors-headers`
#### `pip install djangorestframework-simplejwt`

## Los cuatro paquetes anteriores en un solo comando

#### `pip install django && pip install djangorestframework && pip install django-cors-headers && pip install djangorestframework-simplejwt`

7. Ejecutar el servidor

#### `python manage.py runserver`




