📊 Andes Retail Group – Dashboard de Desempeño Comercial (2024–2025)
📌 Descripción General
Este repositorio contiene el diseño, el flujo de datos (data pipeline) y las visualizaciones interactivas del Dashboard Comercial de Andes Retail Group. Desarrollado en Power BI / Tableau, este proyecto ofrece un análisis exhaustivo del rendimiento de ventas, tendencias de ingresos y segmentación de clientes en las principales regiones objetivo.

El objetivo de este proyecto es transformar datos transaccionales crudos en insights estratégicos accionables, ayudando a las partes interesadas a identificar los motores de rentabilidad y diagnosticar las variaciones de ingresos a lo largo del tiempo.

🛠️ Funcionalidades Clave y Arquitectura
1. Preparación y Transformación de Datos
Fuentes de Datos: Dataset estructurado y depurado (Andes_Retail_Group_2024_2025).

Jerarquía Temporal: Configuración de inteligencia de tiempo dinámica (Año > Trimestre > Mes).

Métricas Personalizadas: Lógica aplicada para categorías personalizadas, incluyendo la regla condicional de Nivel_Venta (Alto / Bajo).

2. Dashboard Ejecutivo (Nivel Directivo)
KPIs Principales: Visibilidad inmediata de Ingresos Totales, Margen de Ganancia y Unidades Vendidas con indicadores de tendencia.

Filtros Interactivos (Slicers): Filtrado dinámico por año, categoría de producto y región geográfica.

Desglose Geográfico y por Categoría: Comparación visual de la distribución de ingresos entre países y líneas de productos.

3. Dashboard de Detalle y Diagnóstico
Desglose Temporal: Profundización detallada (drill-down) en el rendimiento trimestre a trimestre y mes a mes.

Análisis de Segmentos: Distribución de ingresos desglosada por tipo de cliente (por ejemplo: Premium vs. Estándar).

Vista Granular de Datos: Tabla interactiva de métricas con el detalle del volumen de pedidos, alcance de clientes y valor promedio de pedido (AOV).

💡 Insights Clave de Negocio (Marco SCQA)
Aplicando la metodología Situación-Complicación-Pregunta-Respuesta (SCQA), el análisis reveló:

Situación: Las ventas se expandieron a través de los canales minoristas principales durante 2024 y 2025.

Complicación: Se detectaron caídas significativas en los ingresos interanuales específicamente durante el primer (Q1) y cuarto trimestre (Q4).

Pregunta: ¿Qué provocó la caída estacional en el rendimiento durante estos periodos?

Respuesta: El filtrado de diagnóstico mostró que la disminución del gasto por parte del Segmento de Clientes Premium en las regiones del sur fue el principal factor determinante de las caídas de ingresos en Q1 y Q4.
