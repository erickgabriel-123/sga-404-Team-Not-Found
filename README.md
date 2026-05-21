
# Sistema de Gestión Académica (SGA)

## Sprint 0 Goal
El equipo tiene el entorno configurado, el repositorio Git Flow activo,
el SRS en borrador (IEEE 830) y el Product Backlog en GitHub Projects.

## Equipo — 404-Team-Not-Found
| Rol | Integrante | GitHub |
|---|---|---|
| Product Owner | [Erick] | @usuario |
| Scrum Master  | [Sebastian] | @usuario |
| Backend Dev   | [Noe] | @usuario |
| Frontend Dev  | [Carlos] | @usuario |
| QA / DevOps   | [Nombre] | @usuario |

## Stack Tecnológico
- Python 3.12+ | Django 5.x | DRF 3.15+
- Bootstrap 5 | SQLite (dev) | PostgreSQL (prod)

## Cómo ejecutar el proyecto localmente
```bash
git clone https://github.com/erickgabriel-123/sga-404-Team-Not-Found.git
cd sga-404-Team-Not-Found
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
Navegar a http://127.0.0.1:8000/