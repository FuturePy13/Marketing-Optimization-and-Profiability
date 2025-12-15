# Showz-Analytics
Este proyecto simula un caso real en el que trabajo como analista de datos en Showz, una empresa de venta de entradas para eventos.
El objetivo principal es optimizar los gastos de marketing mediante el análisis del comportamiento de los usuarios, las ventas y la rentabilidad de las distintas fuentes de adquisición.

A lo largo del proyecto analizo datos reales de visitas, pedidos y costos de marketing para responder preguntas clave del negocio y apoyar la toma de decisiones del equipo de marketing.

Objetivos del Análisis

En este proyecto busco responder las siguientes preguntas estratégicas:

Uso del servicio

* ¿Cuántos usuarios activos hay por día, semana y mes?

* ¿Cuántas sesiones se generan diariamente?

* ¿Cuál es la duración promedio de las sesiones?

* ¿Con qué frecuencia regresan los usuarios?

Ventas

* ¿Cuánto tiempo pasa desde la primera visita hasta la primera compra?

* ¿Cuántos pedidos realiza un cliente en un período determinado?

* ¿Cuál es el valor promedio de los pedidos?

* ¿Cuánto ingreso genera cada cliente (LTV)?

Marketing

* ¿Cuánto dinero se invierte en marketing en total y por fuente?

* ¿Cuál es el costo de adquisición de clientes (CAC) por fuente?

* ¿Qué tan rentables son las campañas (ROMI)?

* ¿Qué dispositivos y fuentes generan mejores resultados a lo largo del tiempo?

El análisis se realiza con tres datasets:

visits_log_us.csv

Registros de visitas al sitio web (2017–2018):

* Uid: identificador único del usuario

* Device: dispositivo utilizado

* Start Ts: inicio de la sesión

* End Ts: fin de la sesión

* Source Id: fuente de adquisición

orders_log_us.csv

Información sobre pedidos:

* Uid: identificador del usuario

* Buy Ts: fecha y hora del pedido

* Revenue: ingresos generados

costs_us.csv

Gastos de marketing:

* source_id: fuente de anuncios

* dt: fecha

* costs: gasto 

Herramientas y Tecnologias

* Python

* Pandas y NumPy para manipulación de datos

* Matplotlib y Seaborn para visualización

* Jupyter Notebook para análisis y documentación

Metodología

1. Carga y limpieza de datos

* Conversión de tipos de datos

* Corrección de formatos de fecha

* Preparación de tablas para análisis temporal y por cohortes

2. Cálculo de métricas clave (KPIs)

* DAU, WAU, MAU

* Sesiones por usuario

* Duración de sesiones

* Conversión por cohortes

* LTV, CAC y ROMI

Análisis visual

* Comparación por dispositivo y fuente de tráfico

* Evolución de métricas a lo largo del tiempo

Conclusiones y recomendaciones

* Identificación de fuentes más rentables

* Propuestas de optimización del presupuesto de marketing