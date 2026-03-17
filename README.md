# programacion-para-analitica-de-datos.
ES: Repositorio de la asignatura Programación para Analítica de Datos de la Universidad de Manizales (2026) con prácticas y proyectos de análisis de datos. EN: Repository for the Programming for Data Analytics course at the University of Manizales (2026) including assignments and data analysis projects.

### programacion-para-analitica-de-datos

---

### Descripción
**Repositorio de la asignatura Programación para Analítica de Datos** de la Universidad de Manizales. Contiene apuntes, notebooks, prácticas, proyectos y recursos para el curso 2026. El objetivo es reunir material didáctico reproducible para aprender a programar soluciones de análisis de datos con buenas prácticas.

---

### Contenido del repositorio
**Estructura sugerida**
- **`README.md`**; este archivo.
- **`docs/`**; apuntes y guías del curso.
- **`notebooks/`**; Jupyter notebooks organizados por tema y práctica.
- **`src/`**; scripts y módulos reutilizables.
- **`data/`**; datos de ejemplo (solo datos públicos o anonimizados).
- **`assignments/`**; enunciados y entregables de prácticas y proyectos.
- **`tests/`**; pruebas automatizadas si aplica.
- **`examples/`**; ejemplos de uso y demos.

---

### Instalación y uso
**Requisitos**
- **Python 3.10+** o la versión que indique el curso.
- **Entorno virtual recomendado**: `venv` o `conda`.

**Pasos rápidos**
```bash
# clonar el repositorio
git clone https://github.com/TU_USUARIO/programacion-para-analitica-de-datos.git
cd programacion-para-analitica-de-datos

# crear entorno virtual
python -m venv .venv
source .venv/bin/activate   # Linux macOS
.venv\Scripts\activate      # Windows

# instalar dependencias si existe requirements.txt
pip install -r requirements.txt
```

**Ejecutar un notebook**
```bash
jupyter lab
# o
jupyter notebook
```

**Ejecutar scripts**
```bash
python src/mi_script.py
```

---

### Buenas prácticas para contribuciones
- **README claro** para cada carpeta con instrucciones mínimas.
- **No subir datos sensibles**; usar datos sintéticos o enlaces a fuentes públicas.
- **Commits atómicos** y mensajes descriptivos.
- **Branching**: usar ramas por tarea `feature/nombre` o `assignment/nombre`.
- **Pull requests** con descripción del cambio y pasos para reproducir.
- Añadir **issues** para errores o mejoras y etiquetarlos por prioridad.

---

### Licencia y contacto
**Licencia recomendada**: MIT o Creative Commons Attribution (CC BY) si el material es docente. Añade un archivo `LICENSE` con la licencia elegida.

**Contacto**: Federico Pinzón Rubiano — añade tu correo institucional o perfil de GitHub en la sección de contacto del repositorio.

---

Si quieres, genero ahora un **README en formato listo para pegar** con tu usuario y la licencia elegida, o adapto el texto para incluir instrucciones específicas de Python, R o herramientas (conda, Docker, GitHub Actions). ¿Cuál prefieres?
