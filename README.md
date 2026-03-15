# Caso de Estudio: Optimización de Membresías en Cyclistic

## Resumen del Proyecto
Este proyecto es un análisis de Business Intelligence (BI) para **Cyclistic**, una empresa ficticia de bicicletas compartidas en Chicago. El objetivo principal es identificar patrones de uso entre los "ciclistas ocasionales" (usuarios de pases diarios) y los "miembros anuales" para diseñar una estrategia de marketing orientada a la conversión.

*Nota: Aunque Cyclistic es una empresa ficticia, el análisis se basa en datos reales de viajes de la red **Divvy** de Chicago, proporcionados por Motivate International Inc*

## Proceso de Análisis (Metodología)
Para abordar este caso, seguí el proceso estándar de análisis de datos[cite: 7]:

1.  **Preguntar (Ask):** Definición del problema: entender cómo los miembros y ocasionales usan el servicio de manera diferente.
2.  **Preparar (Prepare):** Descarga y revisión de los datos históricos de 2020 para asegurar su credibilidad y cumplimiento con los estándares ROCCC.
3.  **Procesar (Process):** Limpieza y transformación de datos en Google Sheets, Power Bi, Gemini IA. Se crearon las columnas calculadas `ride_length` y `day_of_week`.
4.  **Analizar (Analyze):** Agregación de datos y cálculos estadísticos (media, moda) para identificar tendencias.
5.  **Compartir (Share):** Creación de un dashboard en **Power BI** para visualizar los hallazgos clave.
6.  **Actuar (Act):** Elaboración de 3 recomendaciones estratégicas para el equipo de marketing.

7.  

## Hallazgos Clave
* **Comportamiento Utilitario vs. Recreativo:** Mediante la georreferenciación de las estaciones más concurridas, se identificó que los miembros anuales utilizan el servicio cerca de centros de transporte y oficinas, mientras que los ocasionales se concentran en zonas turísticas.
* **Diferenciación de uso:** Los datos muestran una clara diferencia en la duración del viaje y la frecuencia de uso según el tipo de cliente.

## Recomendaciones Estratégicas
1. **Campaña de Proximidad:** Vincular la membresía anual con beneficios en puntos de interés turístico identificados.
2. **Incentivos por Duración:** Programa de conversión para usuarios de viajes largos (>15 min).
3. **Estrategia Estacional:** Promoción del servicio como transporte anual, incluyendo el uso en invierno.

## Herramientas Utilizadas
* **Análisis y Limpieza:** Google Sheets
* **Visualización:** Power BI
* **Documentación:** Google Docs / GitHub

---
*Este proyecto fue desarrollado como parte de un caso de estudio universitario de Inteligencia de Negocios.*
