# Data Science Challenge
El presente repositorio contiene el desarrollo del terccer reto de Data Science para Mercado Libre. A continuación se describe la organización del repositorio.

# Estructura del repositorio 
En la carpeta notebooks se encuentran todos los cuadernos de JupyterNotebooks donde fue llevado acabo cada etapa del procesamiento de datos
1. Extraccion de Datos: (Extraccion_Datos)
Consiste en la integración de varias funciones para descargar iterativamente cierta información de los productos de las categorías ofrecidas en la base de datos de Argentina. 
2. Exploración y análisis de datos: (EDA_Categorias_SubCategorias)
Integración de diversas estrategias para comprender los datos de los productos pertenecientes a cada categoría y sub categoría 
3. Extracción y generación de caracterísiticas: (Extraccion_Caracteristicas)
A partir de las conclusiones obtenidas en los análisis anteriores se construyen funciones para generar las características de cada uno de los atributos de los productos. Se usan estrategias de vectorización de textos y extracción de características de imágenes 
4. Similitud entre productos: (Aproximacion_Similitud)
Se genera un solo set de datos que contiene todas las características construidas en el paso anterior para, posteriormente, proceder al cálculo de similitud entre productos. Se proponen diversas estrategias para identificar los productos similares según los valores de similitud calculados


