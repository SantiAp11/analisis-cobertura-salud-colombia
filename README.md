# Análisis de Cobertura en Salud Pública en Colombia (2025)

Este proyecto analiza la distribución institucional del sistema de salud colombiano en 2025, con enfoque en el número de Instituciones Prestadoras de Servicios (IPS) por cada 100.000 habitantes.

## Objetivo
Identificar brechas de cobertura institucional departamental con base en datos del REPS y proyecciones poblacionales.

## Herramientas utilizadas
- Python (Pandas, GeoPandas, Matplotlib)
- Google Colab
- Google Looker Studio
- GitHub

## Visualizaciones
- Mapa coroplético de cobertura institucional
- Gráfico de barras por departamento
- Gráfico de dispersión población vs IPS
- Tabla resumen dinámica

## Archivos incluidos
- `analisis_cobertura_salud_colombia.ipynb` – Notebook con análisis completo
- `cobertura_ips_colombia_2025.csv` – Datos procesados
- `assets/` – Imágenes del dashboard en Looker Studio

## Dashboard interactivo
[Ver en Looker Studio](https://lookerstudio.google.com/reporting/1d6f384e-38a2-4434-9df1-88faeb653e8f)

## Conclusiones clave
- Desigualdad territorial en la cobertura institucional: Aunque el país cuenta con miles de Instituciones Prestadoras de Servicios de Salud (IPS), su distribución no es homogénea. Departamentos rurales como Vaupés, Guainía y Vichada tienen una cobertura significativamente menor en comparación con regiones más desarrolladas.

- Alta concentración urbana: En departamentos como Cundinamarca y Antioquia, la mayoría de las IPS se concentran en sus capitales (Bogotá y Medellín, respectivamente), lo que genera una falsa percepción de cobertura uniforme. Las zonas rurales dentro de estos departamentos muestran una menor relación de IPS por habitante.

- Brechas en acceso a servicios de salud: El análisis evidencia que los departamentos con baja densidad poblacional también enfrentan una escasa oferta institucional de salud. Esto plantea desafíos logísticos para el acceso a servicios básicos, especialmente en regiones amazónicas y de frontera.

- Relación no lineal entre población e infraestructura de salud: Aunque existe cierta correlación entre el tamaño poblacional y el número total de IPS, esta relación no es proporcional. Algunos departamentos con poblaciones intermedias presentan buena cobertura relativa, mientras que otros con poblaciones grandes aún muestran rezagos.

- Necesidad de políticas regionales diferenciadas: Los resultados sugieren que la planificación de infraestructura de salud no puede basarse únicamente en cifras agregadas. Se requieren estrategias específicas por territorio, priorizando zonas con baja cobertura relativa, alta dispersión geográfica o condiciones de difícil acceso.
