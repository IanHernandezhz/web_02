
# Biblioteca Universitaria

## Descripción
Aplicación web multipágina desarrollada con Python, Flask,
HTML, Jinja2 y Bootstrap para presentar la información de una
biblioteca universitaria.

## Estructura del proyecto

- **server.py:** contiene la aplicación Flask y las cuatro rutas.
- **templates/layout.html:** plantilla base con la estructura HTML,
  Bootstrap y el menú de navegación.
- **templates/index.html:** página de inicio e información general.
- **templates/catalogo.html:** presenta las categorías de materiales.
- **templates/servicios.html:** describe los servicios disponibles.
- **templates/contacto.html:** muestra los medios de contacto.
- **requirements.txt:** contiene las dependencias del proyecto.

## Tecnologías utilizadas

- Python
- Flask
- HTML
- Jinja2
- Bootstrap 5

## Funcionalidades implementadas

1. Cuatro rutas: Inicio, Catálogo, Servicios y Contacto.
2. Uso de `render_template()` para cargar las plantillas.
3. Envío de las variables `titulo` y `mensaje` desde Flask.
4. Herencia de plantillas mediante `{% extends "layout.html" %}`.
5. Bloques de contenido mediante `{% block content %}`.
6. Menú horizontal de Bootstrap compartido por todas las páginas.
7. Navegación mediante `url_for()`.
8. Organización del contenido con `container-fluid`.

## Instalación y ejecución

1. Instalar las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

2. Ejecutar la aplicación:

   ```bash
   python server.py
   ```

3. Abrir en el navegador:

   http://127.0.0.1:5000/

## Autor
Ian Hernández
