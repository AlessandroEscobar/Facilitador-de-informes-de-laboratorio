# Generador de Informes de Laboratorio - UNJBG (APA 7.ª Edición)

Aplicación web interactiva desarrollada en **Python y Streamlit** para elaborar y exportar informes de **Laboratorio de Física** de la **Universidad Nacional Jorge Basadre Grohmann (Tacna, Perú)** cumpliendo las normas **APA 7.ª Edición**.

## Novedades de esta Versión

- **Limpieza Inteligente del Word Final (`.docx`):** Todo campo, tabla sin datos, figura sin imagen, opción marcada como *(opcional)* o sección completa que no sea llenada desaparece automáticamente del documento Word exportado.
- **Generador Integrado de Gráficos APA 7 (300 DPI):** Crea gráficos de dispersión con ajuste lineal por mínimos cuadrados ($y = mx + b$, $R^2$), líneas comparativas o barras, e insértalos directamente en el informe con un clic.
- **Numeración Correlativa Automática:** Las tablas (`Tabla 1`, `Tabla 2`...) y figuras (`Figura 1`, `Figura 2`...) se numeran automáticamente según las que realmente contengan información, sin saltos ni títulos huérfanos.
- **Prevención de Doble Numeración:** Limpia prefijos escritos manualmente (`1.`, `2.`, `-`) en listas de objetivos y conclusiones antes de aplicar la numeración nativa de Word.
