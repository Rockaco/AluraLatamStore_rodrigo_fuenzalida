# Análisis de Datos de Alura Store: Identificación de la Tienda Menos Eficiente

## Propósito del Análisis

El presente análisis tiene como objetivo fundamental evaluar el desempeño operativo y financiero de las cuatro tiendas pertenecientes a la cadena Alura Store. A través de la exploración y análisis de datos de ventas, rendimiento y métricas de satisfacción del cliente, se busca identificar la tienda que exhibe la menor eficiencia en sus operaciones. Los hallazgos derivados de este estudio servirán como base para una recomendación informada al Sr. Juan respecto a la tienda que, estratégicamente, debería ser considerada para su venta, facilitando así el inicio de un nuevo emprendimiento con el menor impacto adverso posible en la estructura global de la empresa.

## Metodología y Estructura del Proyecto

El análisis se llevó a cabo utilizando un enfoque basado en datos, empleando la biblioteca Pandas para la manipulación y análisis de los conjuntos de datos, y Matplotlib y Seaborn para la visualización de los resultados clave. El proyecto se estructura en un notebook de Google Colab, lo que permite la ejecución secuencial del código y la documentación integrada del proceso analítico.

Los datos de origen para cada una de las cuatro tiendas (`tienda_1.csv`, `tienda_2.csv`, `tienda_3.csv`, y `tienda_4.csv`) fueron cargados directamente desde un repositorio público de GitHub. Se realizó un análisis exploratorio inicial para comprender la estructura de los datos, identificar posibles inconsistencias y familiarizarse con las variables disponibles, que incluyen información detallada sobre productos, categorías, precios, costos de envío, fechas y lugares de compra, calificaciones de clientes, métodos de pago, cantidad de cuotas y coordenadas geográficas.

El análisis se centró en las siguientes métricas clave para cada tienda individualmente:

*   **Ingresos Totales:** Cálculo de la suma total de los precios de venta para determinar la facturación bruta de cada establecimiento.
*   **Ventas por Categoría de Producto:** Agrupación y conteo de ventas por categoría para identificar los segmentos de productos con mayor y menor demanda en cada tienda.
*   **Calificación Promedio de Clientes:** Cálculo del promedio de las calificaciones otorgadas por los clientes para medir la satisfacción general. Se complementó con un análisis de la distribución de estas calificaciones.
*   **Productos Más y Menos Vendidos:** Identificación de los productos individuales con el mayor y menor volumen de ventas.
*   **Costo de Envío Promedio:** Determinación del costo promedio asociado al envío de productos por cada tienda.

## Visualizaciones Clave e Insights Obtenidos

Para facilitar la interpretación de los resultados y destacar los insights más relevantes, se generaron diversas visualizaciones. Se adoptó un estilo visual distintivo ("Trash Metal") para los gráficos. Las visualizaciones clave incluyeron:

*   **Gráfico de Barras Horizontales de Ingreso Total por Tienda:** Comparativa visual directa de la facturación total generada por cada una de las cuatro tiendas.
*   **Gráficos de Barras de Ventas por Categoría por Tienda:** Representación de la distribución de las ventas entre las diferentes categorías de productos para cada establecimiento, permitiendo identificar patrones de consumo específicos de cada tienda.
*   **Gráficos de Conteo de Distribución de Calificaciones por Tienda:** Visualización de la frecuencia de cada nivel de calificación (de 1 a 5 estrellas) en cada tienda, proporcionando una perspectiva detallada sobre la percepción de calidad por parte de los clientes.
*   **Gráficos de Barras Horizontales de Productos Más y Menos Vendidos por Tienda:** Resaltando los productos con desempeño de ventas excepcional (positivo y negativo) en cada localización.
*   **Gráfico de Barras de Costo de Envío Promedio por Tienda:** Comparativa del gasto promedio en logística de envío entre las tiendas.
*   **Gráfico de Torta de Distribución de Métodos de Pago (Datos Consolidados):** Proporción de la utilización de diferentes métodos de pago a nivel global de la cadena.
*   **Gráfico de Dispersión de Precio vs. Costo de Envío (Datos Consolidados):** Exploración de la relación entre el precio de los productos y el costo de envío asociado.

Un insight recurrente en el análisis fue la consistencia en las categorías de productos más vendidas ("Muebles" y "Electrónicos") y las calificaciones promedio de clientes (alrededor de 4.0 con una alta frecuencia de calificaciones de 5) en la mayoría de las tiendas, lo que sugiere una base de operación y satisfacción del cliente relativamente homogénea en estos aspectos. Sin embargo, se observaron diferencias notables en el ingreso total y el costo de envío promedio.

## Conclusión y Recomendación

Con base en la evaluación integral de las métricas analizadas, se concluye que la **Tienda 4** presenta el rendimiento financiero más bajo en términos de ingreso total. Aunque exhibe el costo de envío promedio más bajo, este factor no compensa su menor facturación general en comparación con las otras tiendas. Las métricas de satisfacción del cliente son comparables entre las tiendas, lo que minimiza su influencia como factor diferenciador para la identificación de la tienda menos eficiente.

Por lo tanto, se recomienda al Sr. Juan proceder con la venta de la **Tienda 4**. Esta recomendación se fundamenta principalmente en su menor contribución al ingreso total de la cadena, lo que indica una eficiencia operativa relativamente inferior en comparación con las Tiendas 1, 2 y 3. La desinversión en esta unidad permitiría al Sr. Juan capitalizar recursos con el impacto menos perjudicial en la facturación consolidada de Alura Store, facilitando así la financiación de su nuevo emprendimiento.

## Instrucciones para Ejecutar el Notebook

Para replicar el análisis y explorar los datos, siga los siguientes pasos:

1.  Acceda al notebook de Google Colab.
2.  Asegúrese de contar con una conexión a internet estable para la descarga de los conjuntos de datos desde el repositorio de GitHub.
3.  Ejecute cada celda del notebook secuencialmente. El código está organizado para cargar los datos, realizar los análisis paso a paso y generar las visualizaciones correspondientes.
4.  Revise las salidas de cada celda para observar los resultados de cada etapa del análisis y las visualizaciones generadas.
