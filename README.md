# UniReview - Base de Datos | Database

Este repositorio contiene los scripts SQL y la estructura de base de datos utilizada por **UniReview**, una plataforma colaborativa donde estudiantes y postulantes pueden buscar y compartir reseñas sobre carreras universitarias en México.

This repository contains the SQL scripts and database schema used by **UniReview**, a collaborative platform where students and applicants in Mexico can search for and share reviews about university degrees.

---

## 🛠️ Tecnologías utilizadas | Technologies Used

- MySQL 8.x
- SQL (DDL y DML)
- Workbench

---

## 🧱 Estructura de la base de datos | Database Structure

```bash
/
├── schema.sql       # Script con la estructura (tablas, claves, relaciones)
├── data.sql         # Datos de prueba opcionales (insert)
└── diagram.png      # (Opcional) Diagrama ER o relacional

---

🔑 Tablas principales | Main Tables
usuarios — Información de usuarios registrados

roles — Tipos de roles en la plataforma

carreras — Carreras universitarias disponibles

reseñas — Opiniones y valoraciones de los usuarios

universidades — Instituciones asociadas a las carreras

---

⚠️ Notas
Este proyecto está pensado para uso académico.

Asegúrate de ejecutar schema.sql antes que cualquier script de datos (data.sql).

---

📄 Licencia | License
Uso académico y personal únicamente.
Academic and personal use only.
