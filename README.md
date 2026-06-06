# Análisis de Churn de Clientes 📊

## Descripción
Análisis exploratorio de datos sobre el abandono de clientes (churn) en una empresa 
de telecomunicaciones. El objetivo es identificar los factores que llevan a los clientes 
a cancelar el servicio y extraer insights accionables para mejorar la retención.

## Dataset
Telco Customer Churn — IBM/Kaggle
- 7.043 clientes
- 21 variables (demográficas, de servicio y de contrato)

## Herramientas
- **Python** — Análisis de datos
- **pandas** — Manipulación del dataset
- **matplotlib / seaborn** — Visualizaciones
- **Jupyter Lab** — Entorno de desarrollo

## Hallazgos principales
- Tasa de churn general: **26.5%** (1 de cada 4 clientes se va)
- Contrato month-to-month: **42.7% de churn** vs 2.8% en contratos bianuales
- Los clientes que se van llevan solo **18 meses** promedio vs 37 los que se quedan
- Los clientes que se van pagan más: **$74.44/mes** vs $61.27
- Fibra óptica: **41.9% de churn** vs 19% DSL y 7.4% sin internet
- La antigüedad (tenure) es el predictor más fuerte de churn (correlación -0.35)

## Análisis realizados
1. Distribución de la variable objetivo (Churn)
2. Churn por tipo de contrato
3. Churn por antigüedad del cliente (tenure)
4. Churn por cargos mensuales
5. Heatmap de correlaciones entre variables numéricas
6. Churn por tipo de servicio de internet

## Estructura del proyecto
## Estructura del proyecto
- `cuadernos/` — Notebook principal del análisis
- `imágenes/` — Visualizaciones generadas

## Contacto
**Lucas Espinosa** - Data Analyst  
[LinkedIn](https://linkedin.com/in/lucasespinosaa) · lucaseespinosa93@gmail.com · [github.com/lucasees](https://github.com/lucasees)
