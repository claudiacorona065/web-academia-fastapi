# web-academia-fastapi

# Plataforma Web de Cursos Online – FastAPI + HTML/CSS

Este proyecto es una **plataforma web completa** desarrollada como ejercicio final de la asignatura **Ingeniería Web II**. Simula el funcionamiento de una academia online de programación, permitiendo gestionar cursos, usuarios y solicitudes mediante una API-REST en **FastAPI** y una interfaz web responsive construida con HTML/CSS/JS.

El desarrollo completo explicado esta en el pdf

---

##  Objetivo

- Diseñar una **API-REST funcional** conectada a una base de datos MySQL.
- Construir una **APP-WEB responsive** que consuma dicha API.
- Implementar diferentes **roles de usuario** con permisos diferenciados (super, admin, user).

---
## Roles y permisos

- **user**: puede registrarse, ver sus cursos, editar perfil y solicitar inscripción.
- **admin**: puede crear y editar cursos, ver usuarios.
- **super**: puede hacer todo lo anterior + habilitar/deshabilitar usuarios y crear administradores.

---

##  Funcionalidades implementadas

- Registro y login de usuarios
- Listado de cursos con filtro de disponibilidad
- Creación, edición y solicitud de cursos
- Paneles diferenciados por rol
- Menú responsive y navegación condicional
- Validación de sesiones con tokens
- Backend modular y profesional con FastAPI

---

##  Tecnologías usadas

- **Backend**: Python + FastAPI + SQLAlchemy + Pydantic
- **Frontend**: HTML5, CSS3, JavaScript
- **Base de datos**: MySQL (local)
- **Gestión de entorno**: `.env`, `requirements.txt`
- **Estilo responsive**: Media queries + barra de navegación adaptativa

---


