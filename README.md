# 🇨🇴 Sabores de Colombia - Restaurante Web

Un sitio web para restaurante colombiano desarrollado con Django, que celebra los auténticos sabores de Colombia con un diseño moderno y atractivo.

## 🍽️ Características

- **Página de inicio** con presentación del restaurante
- **Menú interactivo** con platos colombianos tradicionales
- **Página de información** sobre el restaurante
- **Sistema de reservas** para mesas
- **Diseño responsive** adaptado para móviles
- **Panel de administración** de Django para gestionar contenido

## 🚀 Tecnologías Utilizadas

- **Django** - Framework web de Python
- **HTML5 & CSS3** - Estructura y estilos
- **SQLite** - Base de datos
- **Python 3.13** - Lenguaje de programación

## 📋 Requisitos Previos

- Python 3.13 o superior
- pip (gestor de paquetes de Python)
- pipenv (recomendado para el entorno virtual)

## ⚡ Instalación y Configuración

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/BrayamFonck/Django-basic.git
   cd Django-basic
   ```

2. **Instalar dependencias**
   ```bash
   pipenv install
   pipenv shell
   ```

3. **Configurar la base de datos**
   ```bash
   cd DjangoBasic
   python manage.py makemigrations
   python manage.py migrate
   ```

4. **Crear superusuario (opcional)**
   ```bash
   python manage.py createsuperuser
   ```

5. **Ejecutar el servidor**
   ```bash
   python manage.py runserver
   ```

6. **Abrir en el navegador**
   ```
   http://127.0.0.1:8000/
   ```

## 📱 Páginas Disponibles

- **Inicio** (`/`) - Página principal del restaurante
- **Nosotros** (`/about/`) - Información sobre el restaurante
- **Nuestra Carta** (`/menu/`) - Menú con platos disponibles
- **Reservar Mesa** (`/book/`) - Formulario de reservas
- **Administración** (`/admin/`) - Panel de administración

## 🎨 Diseño

El sitio web utiliza una paleta de colores inspirada en la bandera colombiana:
- **Amarillo** (#FFD700) - Calidez y hospitalidad
- **Azul** (#0000FF) - Confianza y profesionalismo  
- **Rojo** (#FF0000) - Pasión por la cocina
- **Tonos tierra** - Conexión con los ingredientes naturales

## 📁 Estructura del Proyecto

```
DjangoBasic/
├── manage.py
├── DjangoBasic/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── primeraApp/
    ├── models.py          # Modelos (Menu, Booking)
    ├── views.py           # Vistas de las páginas
    ├── forms.py           # Formularios
    ├── urls.py            # URLs de la aplicación
    ├── static/            # CSS e imágenes
    └── templates/         # Plantillas HTML
```

## 🛠️ Desarrollo

Para agregar nuevos platos al menú:
1. Acceder al panel de administración en `/admin/`
2. Ir a la sección "Menus"
3. Agregar nuevo elemento con título, descripción y precio

## 📝 Licencia

Este proyecto es de uso educativo y demostrativo.

## 👨‍💻 Autor

Desarrollado por **Brayam Fonck**

---

*¡Disfruta de los auténticos sabores de Colombia! 🇨🇴*
