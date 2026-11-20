# Generador de Informes de Laboratorio - UNJBG (APA 7.ª Edición)

Aplicación web interactiva desarrollada en **Python y Streamlit** para elaborar, importar y exportar informes de **Laboratorio de Física** de la **Universidad Nacional Jorge Basadre Grohmann (Tacna, Perú)** cumpliendo las normas **APA 7.ª Edición**.

## Funcionalidades Principales

- **Importador Inteligente desde Word (`.docx`):** Sube cualquier avance, guía resuelta o informe previo en formato `.docx` y la aplicación detecta automáticamente la carátula, autores, tablas, figuras y cada apartado para rellenar el formulario con un solo clic.
- **Autocompletado con Advertencia Visible:** Si apartados importantes como **1. Resumen**, **2. Introducción**, **4. Resultados y Discusión**, **5. Conclusiones** o **6. Reflexión Argumentada** se dejan en blanco, el sistema redacta automáticamente un borrador académico contextualizado colocando un recuadro de advertencia visible al inicio.
- **Omisión de Apartados Opcionales Vacíos:** Cuestionario (Opcional), Apéndices (Opcional), Fuentes de error (opcional), tablas sin datos y figuras sin imagen desaparecen automáticamente en el archivo Word final.
- **Generador Integrado de Gráficos APA 7 (300 DPI):** Crea gráficos de dispersión con ajuste lineal por mínimos cuadrados ($y = mx + b$, $R^2$), líneas comparativas o barras, e insértalos directamente en el informe.
