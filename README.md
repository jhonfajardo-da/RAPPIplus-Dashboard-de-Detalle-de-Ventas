# 📊 RAPPIplus — Dashboard de Detalle de Ventas

Proyecto final de Análisis de Datos — TripleTen
Estado: ✅ Proyecto aprobado por el tutor

📌 Descripción

Proyecto de desarrollo de un dashboard interactivo en Power BI para RAPPIplus, orientado al análisis detallado del desempeño de ventas.

La solución permite explorar los datos desde una visión general hasta el detalle de cada producto y orden, facilitando la identificación de productos con mayor volumen, evolución mensual y resultados de rentabilidad.

🎯 Objetivos

Analizar unidades vendidas y desempeño comercial.

Identificar los productos con mayor volumen de ventas.

Analizar la evolución mensual de unidades vendidas.

Consultar el detalle de cada producto y orden.

Analizar Revenue, Cost y Profit Operativo.

Identificar visualmente profit positivo y negativo.

Filtrar por fecha, país, categoría y canal.

Implementar Drill-through para profundizar en un producto.

🗂️ Modelo de datos

orders_clean

Tabla principal de órdenes con información de pedido, usuario, fecha, país, dispositivo, producto, categoría, cantidad, precio, descuento y monto total.

Medidas principales:

Cantidad Total Vendida

Cantidad Promedio por Orden

Revenue Total

Costo Total

Profit Total

Profit Operativo

Ticket Promedio

Dimensiones y tablas complementarias

catalog_clean — catálogo de productos.

Dim_Fecha — dimensión temporal.

Dim_Pais — dimensión geográfica.

Dim_Canal — canales.

marketing_clean — información de marketing.

🧹 Limpieza y preparación

Se realizaron procesos de:

Revisión y corrección de tipos de datos.

Eliminación de registros duplicados.

Revisión de consistencia numérica.

Tratamiento de valores atípicos.

Preparación de tablas para el modelo.

Creación y revisión de relaciones.

🔎 Corrección de valor atípico

Se detectó un valor anómalo asociado a Laptop-Gaming-16GB que provocaba que el gráfico mostrara aproximadamente 1.439 millones de unidades.

Después del tratamiento del registro, el producto pasó a mostrar aproximadamente 39 mil unidades, evitando que el dato distorsionara el análisis.

📊 Páginas del dashboard

1. Overview Ejecutivo

Vista general del desempeño comercial y de los principales indicadores.

2. Detalle de Ventas

Incluye:

Filtro por fecha.

Filtro por país.

Filtro por categoría.

Filtro por canal.

Tabla detallada de órdenes.

Revenue Total.

Costo Total.

Profit Operativo.

Formato condicional para profit positivo/negativo.

Gráfico de barras de cantidad vendida por producto.

Gráfico de evolución mensual.

Pregunta del gráfico de productos:

¿Qué productos concentran el mayor volumen de unidades vendidas?

Pregunta del gráfico mensual:

¿Cómo evoluciona mensualmente la cantidad vendida y qué meses se alejan del promedio?

3. Drill-through | Producto

Permite seleccionar un producto y pasar desde el análisis general a sus órdenes relacionadas.

Incluye:

Producto.

ID de pedido.

Cantidad.

Revenue Total.

Costo Total.

Profit Operativo.

Cantidad total vendida.

También incorpora navegación de regreso a la página anterior.

📈 Principales hallazgos

Vacuum-Pro-Black concentra aproximadamente 60 mil unidades vendidas.

Blender-XL-Red registra aproximadamente 59 mil unidades.

Jacket-Winter-M y Sneakers-Urban-42 presentan alrededor de 58 mil unidades cada uno.

Laptop-Gaming-16GB, Phone-Pro-128GB y Tablet-Standard-64GB presentan aproximadamente 39 mil unidades cada uno después del tratamiento del dato atípico.

Febrero presenta el menor volumen mensual observado, con aproximadamente 53,1 mil unidades.

Enero, marzo y mayo presentan niveles superiores al promedio mostrado en el dashboard.

El formato condicional facilita la identificación de órdenes con Profit Operativo positivo y negativo.

🛠️ Herramientas

Herramienta

Uso

Power BI

Modelado, DAX, visualizaciones y dashboard

Power Query

Limpieza y transformación

DAX

Medidas y cálculos

Excel / CSV

Fuentes y preparación de datos

GitHub

Documentación y publicación

🧠 Competencias desarrolladas

Limpieza y transformación de datos.

Análisis exploratorio.

Tratamiento de valores atípicos.

Modelado de datos.

Relaciones entre tablas.

Creación de medidas DAX.

Diseño de dashboards.

Visualización de datos.

Análisis de KPIs.

Filtros e interacción entre visualizaciones.

Drill-through.

Comunicación de insights de negocio.

💡 Conclusión

El dashboard de RAPPIplus transforma datos transaccionales en una herramienta orientada a la toma de decisiones.

La solución permite identificar los productos con mayor volumen, analizar la evolución mensual, revisar el desempeño de las órdenes y detectar resultados positivos o negativos.

La implementación del Drill-through permite pasar de una visión general al detalle de un producto y sus órdenes relacionadas, demostrando cómo la limpieza, transformación, modelado y visualización pueden convertirse en una herramienta útil para el análisis comercial.

📁 Estructura sugerida

📦 RAPPIplus-Dashboard
 ┣ 📂 data
 ┣ 📂 dashboard
 ┣ 📂 images
 ┗ 📄 README.md

Nota: No publiques datos sensibles o restringidos. Si los archivos pertenecen a una plataforma educativa, puedes incluir el .pbix cuando sea permitido y acompañarlo con capturas y documentación.

🎓 Formación

Programa de Análisis de Datos — TripleTen

Proyecto final desarrollado durante el proceso de formación en análisis de datos.

Estado: ✅ Aprobado por el tutor

👤 Autor

Jhon Fajardo
Analista de Datos Junior
