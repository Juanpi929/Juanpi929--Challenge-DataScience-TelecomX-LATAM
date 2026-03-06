📊 TelecomX LATAM – Análisis de Evasión de Clientes

Python • Pandas • Matplotlib • Data Analysis

📌 Descripción del Proyecto

Este proyecto desarrolla un análisis exploratorio de datos (EDA) sobre el comportamiento de clientes de TelecomX, con el objetivo de identificar factores asociados a la evasión de clientes.

La evasión de clientes representa uno de los mayores desafíos para las empresas de telecomunicaciones, ya que impacta directamente en los ingresos y en la estabilidad del negocio.

A través del análisis de datos, visualizaciones y evaluación de variables demográficas, contractuales y de consumo, este proyecto busca descubrir patrones que expliquen por qué los clientes cancelan el servicio.

🎯 Objetivo del Análisis

Analizar el comportamiento de los clientes de TelecomX para identificar factores asociados con la cancelación del servicio.

El análisis evalúa variables como:

📈 Distribución de clientes que cancelan el servicio
📑 Tipo de contrato
💳 Método de pago
🌐 Tipo de servicio de internet
⏳ Tiempo de permanencia del cliente
💰 Cargos mensuales y gasto total

El propósito final es generar insights estratégicos que permitan mejorar la retención de clientes.

🗂️ Estructura del Proyecto
📦 TelecomX-Churn-Analysis
 ┣ 📊 TelecomX_Data.json
 ┣ 📓 Challenge_TelecomX_LATAM.ipynb
 ┣ 📓 TelecomX_LATAM.ipynb
 ┣ 📜 README.md

Archivos principales

TelecomX_Data.json → Dataset con información de clientes

TelecomX_LATAM.ipynb → Notebook con la plantilla que se uso para el análisis

Challenge_TelecomX_LATAM.ipynb → Notebook con el análisis completo

README.md → Documentación del proyecto

📊 Principales Hallazgos
📉 1. Distribución de evaión

El análisis muestra que aproximadamente:

Estado del Cliente	Proporción
Permanecen	~73%
Cancelan servicio	~27%

Esto indica que existe una tasa significativa de evasión que requiere atención estratégica.

📑 2. Tipo de Contrato

Los clientes con contrato Month-to-Month presentan la mayor tasa de cancelación.

Tipo de contrato	Tendencia de churn
Month-to-Month	Alta
One Year	Media
Two Year	Baja

💡 Insight:
Los contratos a largo plazo reducen significativamente la evasión de clientes.

💳 3. Método de Pago

Se observó que los clientes que utilizan:

Electronic Check

presentan una mayor tasa de cancelación en comparación con:

Tarjeta de crédito

Transferencia bancaria

Cheque por correo

Esto puede indicar menor fidelización o menor automatización de pagos.

🌐 4. Tipo de Servicio de Internet

El análisis muestra que los clientes con fibra óptica presentan una tendencia ligeramente mayor a cancelar el servicio.

Posibles causas:

costos más elevados

expectativas de servicio más altas

⏳ 5. Tiempo de Permanencia (Tenure)

Uno de los patrones más claros encontrados fue que:

Los clientes que cancelan el servicio suelen tener menos tiempo en la empresa

Los clientes con mayor antigüedad presentan mayor estabilidad

💡 Insight:
La evasión ocurre principalmente durante los primeros meses del servicio.

💰 6. Cargos Mensuales y Gasto Total

El análisis también muestra que:

Algunos clientes con cargos mensuales elevados presentan mayor probabilidad de cancelar

Los clientes que permanecen tienen mayor gasto total acumulado

Esto es consistente con su mayor tiempo de permanencia en la empresa.

🏆 Conclusión Estratégica

El análisis indica que los factores más asociados a la evasión de clientes son:

1️⃣ Tipo de contrato
2️⃣ Tiempo de permanencia del cliente
3️⃣ Método de pago
4️⃣ Nivel de cargos mensuales

En particular, los clientes con contratos Month-to-Month y menor tiempo en la empresa presentan mayor riesgo de cancelación.

✅ Recomendaciones Estratégicas

A partir de los hallazgos se proponen las siguientes acciones:

📌 Incentivar contratos de largo plazo mediante descuentos o beneficios.

📌 Implementar programas de fidelización para clientes nuevos durante los primeros meses.

📌 Revisar la relación entre precio y valor percibido del servicio.

📌 Promover métodos de pago automáticos que reduzcan la probabilidad de cancelación.

📌 Implementar en el futuro modelos predictivos de churn utilizando Machine Learning.

🛠️ Tecnologías Utilizadas

Python 3
Pandas
Matplotlib
Google Colab / Jupyter Notebook

▶️ Cómo Ejecutar el Proyecto

Este proyecto fue desarrollado en Google Colab.

Pasos para ejecutarlo

1️⃣ Abrir el archivo .ipynb

2️⃣ Subirlo a Google Colab o abrirlo desde GitHub con la opción:

Open in Colab

3️⃣ Ejecutar las celdas en orden

Google Colab ya incluye las dependencias necesarias (pandas y matplotlib).

🚀 Posibles Mejoras Futuras

Este proyecto puede ampliarse con:

Modelos de Machine Learning para predicción de evasión

Análisis de correlaciones

Segmentación de clientes

Dashboard interactivo con Power BI o Tableau

Visualizaciones avanzadas con Seaborn o Plotly

👨‍💻 Autor

Juan Pablo Quispe Carhuancota

Interesado en Data Science, análisis de datos y desarrollo tecnológico.

📧 Correo: j18081247@gmail.com

🔗 GitHub
https://github.com/Juanpi929

🔗 LinkedIn
https://linkedin.com/in/juan-pablo-quispe-917b8a355/

Proyecto desarrollado como parte del Challenge de Data Science – Alura Latam.
