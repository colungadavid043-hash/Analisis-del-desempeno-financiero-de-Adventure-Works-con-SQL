
# Análisis del desempeño financiero de Adventure Works con SQL✖️ ➕

>[!NOTE]
> PROYECTO REALIZADO EN TRIPLETEN

Se quiere saber en qué mercados se generan más ingresos y rentabilidad para decidir dónde invertir el próximo dólar de marketing.


### Objetivos 🎯

1. Navegar un esquema relacional y escribir JOINs para combinar tablas.

2. Extraer, filtrar y limpiar datos con SQL (manejo de NULLs, casting de tipos, estandarización de categorías).

3. Calcular indicadores financieros clave: ingresos, costos, beneficio bruto, margen y ROI.

4. Validar y controlar calidad (QA) con comprobaciones de totales y márgenes.

5. Redactar un informe ejecutivo con visualizaciones y el método Contexto → Hallazgo → Implicación (C→F→I).




### Proceso 📝

- Explorar el esquema: Diagrama de Entidades y definición de esquema de Tablas.
- Extraer y limpiar datos con consultas SQL y vistas.
- Calcular KPIs financieros y guardarlos en vistas.


### Dataset

- Ventas_2017: transacciones de líneas de pedido (2017). Grano: una línea por producto y pedido.
- Productos: catálogo con atributos, costo y precio unitario por ClaveProducto.
- Productos_categorias: jerarquía categoría/subcategoría para enriquecer productos.
- Clientes: maestro de clientes con segmento y ubicación.
- Territorios: mapa de ClaveTerritorio → país y continente.
- Campanas: gasto de marketing por territorio/campaña.


###  Principales Hallazgos  🔧

 - El país más rentable en margen de ganancia y retorno de inversión (ROI) fue Estados Unidos.
 - Canadá tiene un muy buen margen de ganancia, aunque sus ingresos sean los más bajos.
 
                                      
