<<<<<<< HEAD
# Práctica: Análisis de Errores de Acceso por Hora

Este proyecto simula y analiza un registro de intentos de acceso al sistema de una empresa, enfocándose en los **errores por hora**.

## Archivos

- **logs.txt**  
  Contiene registros simulados de accesos, indicando fecha y hora, usuario y resultado (`OK` o `ERROR`).

- **analisis_logs.py**  
  Script en Python que lee el archivo de logs, cuenta los errores de acceso por hora y genera un gráfico de barras.

- **grafico_errores_por_hora.png**  
  Imagen del gráfico generado por el script (se crea al ejecutar el script).

## Uso

1. Clona el repositorio.
2. Instala la librería matplotlib si no la tienes:
   ```
   pip install matplotlib
   ```
3. Ejecuta el script:
   ```
   python analisis_logs.py
   ```
4. Observa la gráfica `grafico_errores_por_hora.png` y analiza en qué horas ocurren más errores de acceso.

## Explicación del caso

- El archivo `logs.txt` simula accesos de varios usuarios en diferentes horas y días.
- El script analiza en qué horas se concentran los errores de acceso, útil para identificar posibles intentos sospechosos o problemas recurrentes en horarios concretos.

## ¿Cómo funciona el código?

1. Lee cada línea del archivo de registro.
2. Extrae la hora y verifica si el estado es `ERROR`.
3. Cuenta cuántos errores hay en cada hora.
4. Muestra un gráfico de barras con los resultados.

## Ampliaciones posibles

- Analizar errores por usuario.
- Analizar errores por día.
- Detectar patrones de actividad fuera del horario laboral.

---

**¡Comparte tu análisis y gráfica en la práctica de ciberseguridad!**
=======
# analisis_errores_por_hora
Práctico de análisis de errores de acceso por hora en logs de sistemas
>>>>>>> 56ca0c22c437a9eaffd918f212fac0b1444bc951
