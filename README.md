# Análisis de Errores de Acceso por Hora: Ciencia de Datos aplicada a la Ciberseguridad

Este proyecto surge como parte de mi preparación para un máster en **Ciberseguridad**, aplicando técnicas de **Data Science** al análisis de logs de acceso. El objetivo es mostrar cómo el estudio de los errores por hora ayuda a **resguardar los sistemas** y anticipar amenazas.

## ¿Por qué es importante este análisis?

Los logs de acceso contienen información clave sobre el funcionamiento y la seguridad de cualquier sistema. Analizar los patrones de errores permite:

- **Detectar intentos sospechosos o automatizados de acceso**
- **Identificar vulnerabilidades en horarios específicos**
- **Prevenir ataques y mejorar la respuesta ante incidentes**
- **Transformar datos en conocimiento útil para blindar la infraestructura tecnológica**

## Archivos incluidos

- **logs.txt:** Registro simulado de accesos (fecha, hora, usuario, resultado).
- **analisis_logs.py / analisis_logs.ipynb:** Scripts en Python para analizar los errores por hora y visualizar los resultados.
- **grafico_errores_por_hora.png:** Gráfico generado mostrando la distribución de errores.
  
## Herramientas y librerías utilizadas

- **Python 3.8+**  
  Lenguaje principal para el análisis y procesamiento de logs.
- **Jupyter Notebook**  
  Para desarrollo interactivo y visualización de resultados.
- **matplotlib**  
  Visualización de datos y generación de gráficos de barras.
- **pandas (opcional)**  
  Manipulación eficiente de datos tabulares (puedes mencionar si lo usaste).
- **Git y GitHub**  
  Control de versiones y hospedaje del repositorio.

## Uso del proyecto

1. Clona el repositorio.
2. Instala la librería matplotlib si no la tienes:
   ```
   pip install matplotlib
   ```
3. Ejecuta el script:
   ```
   python analisis_logs.py
   ```
   o abre el notebook en Jupyter y ejecuta las celdas.
4. Analiza el gráfico para descubrir en qué horarios se concentran los errores.

## Aplicaciones en Ciberseguridad

- **Monitoreo proactivo de accesos y detección de anomalías**
- **Optimización de medidas de protección según patrones de error**
- **Base para sistemas de alerta temprana y defensa automatizada**

---

**Este proyecto refleja cómo la Ciencia de Datos potencia la Ciberseguridad: transformar datos en acciones para proteger activos y anticipar riesgos.**


