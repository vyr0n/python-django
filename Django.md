# Django

#### Instalación del Enviroment

 - > pip install virtualenv
 - De ahí creamos la carpeta donde estará el proyecto
 - Para ver la ruta dónde esta instalado python
   - > which python
 - Para crear el ambiente virtual se hace lo siguiente:
   - > virtualenv -p /usr/bin/python pages
     - dónde /usr/bin/python es la dirección donde se encuentra python
     - pages es la carpeta que va a crear.
- Para activar
  - > source ./pages/bin/activate
- Para crear el proyecto
  - Nos ubicamos junto al entorno, (la carpeta pages del ejemplo de arriba)
  - > django-admin startproject pages
- Para levantar el servidor - (el proyecto)
  - Entramos a la carpeta pare_project y corremos lo siguiente:
    - > python3 manage.py runserver
    - En mi caso es así porque estoy en macOS
- Lección: empaquetar:
  - Crear una carpeta al mismo nivel de manage.py
  - > mkdir Apps
  - Dentro de esta carpeta y agregar:
    - > django-admin startapp pages
