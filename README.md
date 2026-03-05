# Challege-telecom-X-1
El objetivo de este proyecto es analizar la evasión de clientes (Churn) en TelecomX para identificar los factores que influyen en que los clientes cancelen el servicio.
Mediante técnicas de análisis de datos con Python, se exploraron variables como tipo de contrato, método de pago, servicios contratados y cargos mensuales para detectar patrones que ayuden a mejorar la retención de clientes.

Estructura del proyecto
TelecomX-Churn
│
├── README.md
├── Analisis_Churn.ipynb
└── TelecomX_Data.json

Analisis_Churn.ipynb: Notebook con todo el proceso de análisis (extracción, limpieza, transformación y análisis exploratorio).

TelecomX_Data.json: Dataset utilizado para el análisis.

README.md: Descripción del proyecto.

Ejemplos de insights obtenidos

Algunos hallazgos importantes del análisis:

Los clientes con contratos mensuales (Month-to-Month) tienen mayor probabilidad de cancelar.

El método de pago Electronic Check presenta una tasa de evasión más alta.

Los clientes que cancelan suelen tener menos tiempo con la empresa.

Los clientes con churn tienen en promedio cargos mensuales más altos.

Estos patrones pueden ayudar a la empresa a desarrollar estrategias de retención de clientes.

Cómo ejecutar el proyecto

Abrir el archivo Analisis_Churn.ipynb en:

Jupyter Notebook

Google Colab

Instalar las librerías necesarias:

pip install pandas requests numpy

Ejecutar las celdas del notebook en orden para reproducir el análisis.
