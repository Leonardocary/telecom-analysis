# 📊 Análisis ConnectaTel — Sprint 7

## Objetivo
Analizar el comportamiento de clientes de ConnectaTel, empresa de telecomunicaciones con operaciones en México y Colombia, para identificar patrones de uso, detectar outliers y crear segmentos de clientes que permitan optimizar la oferta comercial.

## Datasets utilizados
| Archivo | Descripción |
|---|---|
| `plans.csv` | Planes disponibles (precio, minutos, GB, costos extra) |
| `users_latam.csv` | Información de clientes (edad, ciudad, plan, churn) |
| `usage.csv` | Uso real de servicios (llamadas y mensajes) |

## Etapas del análisis
1. Carga y exploración inicial de los tres datasets
2. Identificación de problemas de calidad (nulos, sentinels, fechas)
3. Limpieza de datos (corrección de sentinels y fechas imposibles)
4. Estadísticas descriptivas por usuario
5. Visualización de distribuciones y detección de outliers
6. Segmentación de clientes por uso y edad
7. Insights ejecutivos para stakeholders

## Cómo ejecutar el notebook
1. Abre [Google Colab](https://colab.research.google.com/)
2. Ve a **File → Open notebook → GitHub**
3. Pega la URL de este repositorio
4. Selecciona el archivo `.ipynb`
5. Ejecuta las celdas en orden con `Shift + Enter`

> ⚠️ Los datasets deben estar disponibles en `/datasets/` o ajustar las rutas en la celda de carga.


## Herramientas
- Python
- pandas, numpy, seaborn, matplotlib
