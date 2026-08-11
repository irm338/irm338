#  Irma Yaneht Arias García 🚀

name: Generate 3D Contribution Calendar

on:
  schedule:
    - cron: "17 6 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: actions/checkout@v5
      - uses: irm338/github-profile-3d-contrib@latest
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          USERNAME: irm338
      - name: Commit generated profile assets
        uses: stefanzweifel/git-auto-commit-action@v7
        with:
          commit_message: "chore: update 3d contribution calendar"
          file_pattern: profile-3d-contrib/*.svg

¡Hola! Soy **Irma Yaneht Arias García**, estudiante de programación y desarrollo web en **Campuslands**. Este repositorio centraliza mis proyectos formativos y evidencias técnicas desarrolladas durante mi entrenamiento profesional.

---

## 🛠️ Stack Tecnológico

He enfocado mi aprendizaje en el dominio de herramientas esenciales para la creación de interfaces web y gestión de datos:

*   **Frontend:** HTML5, CSS3, JavaScript.
*   **Backend & Data:** SQL (SQLite), Python.
*   **Herramientas:** Git/GitHub, n8n (Automatizaciones).

---

## 📂 Proyectos Destacados






A continuación, presento los proyectos desarrollados durante mi formación:

| Proyecto | Descripción | Tecnologías |
| :--- | :--- | :--- |
| **CampusShop** | Maquetación estática de plataforma e-commerce. | HTML5, CSS3 |
| **CampusParking** | Interfaz para administración de estacionamiento. | HTML5, CSS3, JS |
| **EduTrack** | Landing page y dashboard educativo. | HTML5, CSS3, JS |
| **CineMax** | Base de datos relacional para cines. | SQLite, SQL |

---

## 🎓 Formación Académica

*   **Institución:** Campuslands.
*   **Enfoque:** Desarrollo Web y Programación de Sistemas.

---

## 📬 Contacto

¿Quieres conectar o colaborar? ¡Hablemos!

*   **Email:** yanehtarias12@gmail.com
*   **LinkedIn/GitHub:** [GitHub: Irm338](https://github.com/Irm338)

---
*Diseñado con pasión y rigor técnico. © 2026 Irma Yaneht Arias García.*#
