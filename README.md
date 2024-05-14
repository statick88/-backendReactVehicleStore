# App Django Vehicle Store

## Descripcion

Este proyecto es un ejemplo de una aplicacion web desarrollada con Django, la cual permite la gestion de vehiculos, marcas y modelos.

Esta construido con la arquitectura de Cliente/Servidor donde se genera el patron de diseño Modelo Template Vista (MTV) de Django.

Tambien incluye Django Rest Framework para la creacion de una API REST que permite la gestion de los datos de la aplicacion.

El cliente de frontend se encuentra en el repositorio [https://github.com/statick88/frontendReactVehicleStore](https://github.com/statick88/frontendReactVehicleStore)

## Requerimientos

- python 3.12.3
- asgiref 3.8.0
- certifi 2024.2.2
- charset-normalizer 3.3.2
- coreapi 2.3.3
- coreschema 0.0.4
- Django 4.2.2
- django-cors-headers 4.3.1
- djangorestframework 3.15.0
- drf-yasg 1.21.7
- idna 3.7
- inflection 0.5.1
- itypes 1.2.0
- Jinja2 3.1.4
- MarkupSafe 2.1.5
- packaging 24.0
- pillow 10.2.0
- pytz 2024.1
- PyYAML 6.0.1
- requests 2.31.0
- setuptools 69.5.1
- sqlparse 0.4.4
- tzdata 2024.1
- uritemplate 4.1.1
- urllib3 2.2.1

## Instalacion

1. Clonar el repositorio

``` bash
git clone https://github.com/statick88/backendReactVehicleStore.git
```

2. Crear un entorno virtual

``` bash
python -m venv env
```

3. Activar el entorno virtual

``` bash
source env/bin/activate
```

En máquinas Windows

``` bash
env\Scripts\activate
```

4. Instalar las dependencias con 

``` bash
pip install -r requirements.txt
```

4. Crear la base de datos con el comando

``` bash
python manage.py makemigrations
```

``` bash
python manage.py migrate
```

5. Crear un superusuario con el comando

``` bash
python manage.py createsuperuser
```

6. Iniciar el servidor con el comando

``` bash
python manage.py runserver
```

7. Acceder a la aplicacion en la direccion [http://127.0.0.1:8000](http://127.0.0.1:8000)

8. Acceder al panel de administracion en la direccion [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)

## Endpoints

- /api/vehicles/
- /api/vehicles/{id}
- /api/brands/
- /api/brands/{id}
- /api/models/
- /api/models/{id}

## Documentacion

La documentacion de la API se encuentra en la direccion [http://127.0.0.1:8000/swagger](http://127.0.0.1:8000/swagger)

## Licencia

Este proyecto es de codigo abierto y se encuentra bajo la licencia MIT

