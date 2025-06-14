
# Análisis de Rotación de Clientes en Telecomunicaciones

Este proyecto analiza un conjunto de datos reales de clientes de una empresa de telecomunicaciones para comprender los factores que influyen en la rotación (churn) de clientes y preparar el camino hacia modelos predictivos.

## Descripción

El análisis se centra en detectar patrones y características clave de los clientes que deciden abandonar el servicio, mediante un proceso de limpieza de datos y análisis exploratorio con visualizaciones.

## Funcionalidades Aplicadas

### Limpieza y preparación de datos

- Eliminación de duplicados
- Conversión de tipos de datos según el diccionario
- Normalización de variables categóricas (como mayúsculas/minúsculas)
- Relleno de valores faltantes con marcadores adecuados (por ejemplo, la mediana para TotalCharges)
- Corrección de inconsistencias y valores atípicos

### Análisis Exploratorio (EDA)

- Visualización univariada:
  - Distribución de clientes por género
  - Histograma de cargos mensuales
- Visualización multivariada:
  - Gráfico de caja de MonthlyCharges según Churn
  - Comparación de servicios contratados versus rotación

Cada visualización contiene una breve interpretación para facilitar la comprensión de los hallazgos.

## Tecnologías Utilizadas

- Python 3
- Pandas para manipulación de datos
- Matplotlib para visualizaciones
- Jupyter Notebook o Google Colab

## Resultados Preliminares

- Los clientes con cargos mensuales más altos tienen una mayor tasa de abandono.
- La duración del contrato es un factor relevante: clientes nuevos tienden a abandonar más rápido.
- Algunos servicios adicionales están más asociados al abandono.

## Cómo ejecutar el análisis

1. Clona el repositorio:
   git clone https://github.com/iantillanca/rotacion-clientes-telecomunicaciones.git

2. Abre el archivo:
   Analizando_la_Rotación_de_Clientes_en_Telecomunicaciones.ipynb

3. Sube el archivo de datos original (WA_Fn-UseC_-Telco-Customer-Churn.csv) a tu Google Drive.

4. Monta tu Google Drive en Google Colab para acceder al archivo y ejecutar el notebook desde allí.

## Entrega

Este repositorio incluye:
- Notebook entregable con comentarios y visualizaciones.
- TAG de entrega: entrega-final
