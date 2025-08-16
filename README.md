# Django + ProcessMaker Reports

Este proyecto es una integración de **Django** con **ProcessMaker Community Edition** con el objetivo de **mejorar y extender el módulo de reportes estándar** que ofrece ProcessMaker.

## 🚀 Propósito del proyecto

El propósito de este desarrollo es ofrecer a los usuarios de negocio un sistema de reportes más **flexible, claro y seguro**, superando las limitaciones de la versión comunitaria de ProcessMaker.  

Las principales mejoras que introduce son:

- 🔎 **Filtros de búsqueda avanzados** para acceder rápidamente a la información.
- 📊 **Visualización Optimizada** datos presentados de forma clara y comprensible.
- 👥 **Control de accesos por grupos y sucursales**, asegurando que cada usuario solo vea la información que le corresponde.
- 🖨️ **Exportación de casos a PDF** para impresión y archivo.
- 🌐 **Interfaz web en Django** más amigable y adaptable a las necesidades de la empresa.

## ⚙️ Tecnologías utilizadas

- **Backend:** Django 4.0.4
- **Base de datos:** MySQL
- **Integración:** Conexión directa a la base de datos de ProcessMaker Community 3.2.3
- **Infraestructura:** Despliegue en IIS (Windows Server 2016)
- **Utilidades:** `xhtml2pdf`, `weasyprint`, `django-crispy-forms`, `django-admin-interface`, `python-decouple`, `django-import-export`, `wfastcgi`.

## 📂 Estructura del proyecto

```django-pm-demo/
│── backend/
│ ├── manage.py
│ ├── requirements.txt
│ ├── demo_project/
│ │ ├── settings.py
│ │ ├── urls.py
│ │ └── wsgi.py
│ └── pm_integration/
│ ├── client.py
│ ├── services.py
│ └── views.py
│
│── README.md
│── docker-compose.yml
│── .env.example```