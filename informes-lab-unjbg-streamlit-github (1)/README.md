# Generador de Informes de Laboratorio - UNJBG (APA 7.ª Edición)

Aplicación web interactiva desarrollada en **Python y Streamlit** para elaborar y exportar informes de **Laboratorio de Física** de la **Universidad Nacional Jorge Basadre Grohmann (Tacna, Perú)** cumpliendo las normas **APA 7.ª Edición**.

---

## Características Principales

- **100 % Autocontenido para GitHub y Streamlit Cloud:** `streamlit_app.py` integra el escudo institucional UNJBG tanto en carpeta (`assets/logo-unjbg.png`) como embebido en código, garantizando que funcione sin errores incluso si subes los archivos desde la interfaz web de GitHub.
- **Carátula Oficial UNJBG:** Escudo institucional centrado inmediatamente después de **Escuela Profesional** y antes de **Laboratorio de: FÍSICA**.
- **Normativa APA 7.ª Edición Completa:**
  - Exportación directa a **Word (`.docx`)** con fuente *Times New Roman* 12 pt, interlineado doble (`2.0`), márgenes de `2.54 cm`, numeración superior derecha, tablas únicamente con bordes horizontales, figuras con título en cursiva y *Nota.* al pie, y referencias ordenadas alfabéticamente con **sangría francesa** (`1.27 cm`).
  - Exportación también disponible en **LaTeX (`.tex`)**, **Markdown (`.md`)** y respaldo editable **JSON (`.json`)**.
- **Calculadora Integrada de Regresión Lineal:** Ajuste por mínimos cuadrados ($y = mx + b$) con cálculo automático de pendiente, intercepto, incertezas estándar y coeficiente $R^2$.

---

## Cómo Subirlo a un Repositorio Nuevo en GitHub y Compartirlo en Streamlit

1. Crea un **repositorio nuevo** (público) en [github.com/new](https://github.com/new).
2. Descomprime este archivo `.zip` y sube los archivos directamente a la **raíz** del repositorio (`streamlit_app.py`, `requirements.txt`, `assets/`, `.streamlit/`, `README.md`).
3. Ingresa a [share.streamlit.io](https://share.streamlit.io/), inicia sesión con tu cuenta de GitHub y haz clic en **Create app** -> **Deploy a public app from GitHub**.
4. Selecciona tu nuevo repositorio, deja la rama `main` y verifica que **Main file path** sea `streamlit_app.py`.
5. Haz clic en **Deploy** y obtendrás tu enlace público listo para compartir.
