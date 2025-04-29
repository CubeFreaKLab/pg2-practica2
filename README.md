# PG2: PRÁCTICA 2

## Descripción General de la Práctica

En esta practica aprendemos el uso de Django, en donde creamos un modelo para la gestión de libros y autores

## Requisitos

- Python 3.8 o superior
- Django 5.2

## Configuración del Entorno y Ejecución

### Crear entorno virtual
```bash
python -m venv venv
```

### Activar entorno virtual
```bash
# Windows
.\venv\Scripts\activate
# Linux/Mac
source venv/bin/activate
```

### Instalar dependencias
```bash
pip install -r requirements.txt
```

## Configuración del Proyecto

### Aplicar migraciones
```bash
python manage.py migrate
```

### Crear superusuario
```bash
python manage.py createsuperuser
```

### Iniciar servidor
```bash
python manage.py runserver
```

### Acceder al panel de administración
Abre tu navegador y ve a `http://localhost:8000/admin/`. Inicia sesión con el
superusuario que creaste anteriormente. Desde allí podrás administrar autores y libros.
