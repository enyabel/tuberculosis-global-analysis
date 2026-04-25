# Análisis Exploratorio de Tuberculosis Global

La tuberculosis sigue siendo una de las enfermedades infecciosas con mayor impacto en la salud pública global, concentrándose desproporcionadamente en países de ingresos bajos y medios. Este proyecto presenta un análisis exploratorio de datos a nivel mundial, integrando registros de casos de la Organización Mundial de la Salud con datos de población por país y año.

A través de un proceso riguroso de limpieza, transformación e integración de datasets, se construyó un conjunto de datos estructurado que permite analizar la evolución de la enfermedad desde múltiples dimensiones: género, grupo de edad, método de diagnóstico y cobertura geográfica. El indicador central del análisis es la tasa de incidencia por cada 100,000 habitantes, métrica estándar para comparar la magnitud del problema entre países con distintos tamaños poblacionales.

## Datos utilizados

- **Organización Mundial de la Salud (OMS)** — Casos de tuberculosis por país, año, género, grupo de edad y método de diagnóstico.
- **Datos de población** — Población por país y año para el cálculo de tasas de incidencia.

## Estructura del análisis

1. **Limpieza de datos** — Manejo de valores faltantes, corrección del código ISO de Namibia y reestructuración del dataset con `melt`
2. **Transformación de variables** — Extracción de género, método de diagnóstico y grupo de edad a partir de los códigos de columna originales
3. **Integración de datasets** — Cruce entre datos de casos y población por paí
