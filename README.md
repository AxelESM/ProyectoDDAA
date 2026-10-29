A.1- Descripción de la Fase de Desarrollo (Rama Descendente)


- Análisis de Requisitos (Requirement Gathering):
  - Se definen las necesidades funcionales y no funcionales del sistema, así como los requerimientos del usuario (registro, inicio de sesión, control de roles y panel de administración).

- Análisis del Sistema (System Analysis):
  - Se especifica el comportamiento general del software, el flujo de navegación entre las vistas y la arquitectura funcional basada en el patrón MTV de Django.

- Diseño de Software / Arquitectura (Software Design): 
  - Se determinan los componentes principales, la estructura de directorios del proyecto (`config/`, `cuentas/`), las interfaces de usuario y las tecnologías del stack (Python, Django, SQLite/MySQL, HTML y CSS).

- Diseño de Módulos (Module Design):
  - Se detallan la lógica interna, el enrutamiento (`urls.py`), las vistas (`views.py`), los formularios de autenticación predeterminados (`UserCreationForm`, `AuthenticationForm`) y el manejo de permisos por roles.

- Punto de Inflexión:
  - Es el hito crítico de transición donde se valida que el diseño y los requerimientos están listos antes de pasar a la codificación masiva.

- Codificación (Coding):

  - Construcción e implementación efectiva del código fuente (vistas, URLs, plantillas HTML condicionales y control de versiones con Git/GitHub).