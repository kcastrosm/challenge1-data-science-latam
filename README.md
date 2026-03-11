# Challenge Alura Store
Este es un desafío de la formación en Data Science del programa ONE de Alura LATAM y Oracle y consiste en analizar el rendimiento de cuatro tiendas para determinar cuál debería ponerse en venta.

# Librerías utilizadas

**pandas**: manipulación y análisis de datos.

**matplotlib.pyplot**: visualización de datos.

# Extracción de datos
Los datos fueron extraídos de archivos CSV almacenados en un repositorio de GitHub, utilizando la función pd.read_csv de pandas para cargar la información en DataFrames. Se disponen de 4 archivos CSV, con los datos de cada tienda analizada.

tienda_1.csv


tienda_2.csv


tienda_3.csv


tienda_4.csv

# Limpieza de datos
No se requirió ejecutar una limpieza de datos.

# Análisis de datos
El análisis de datos se centró en los siguientes aspectos para evaluar el rendimiento de cada tienda:

1. **Análisis de facturación (Ingresos Totales)**: ae calculó la suma total de los precios de los productos vendidos en cada tienda para determinar sus ingresos brutos.
2. **Ventas por categoría**: se determinaron los productos más y menos vendidos a nivel global, consolidando los datos de todas las tiendas.
3. **Calificación promedio de la tienda**: se calculó la calificación promedio para cada tienda, ofreciendo una métrica de la satisfacción delos clientes.
4. **Productos más y menos vendidos**: se identificaron los productos individuales más y menos vendidos en cada tienda.
5. **Costo de envío promedio**: se calculó el costo de envío promedio de cada tienda.

# Cómo ejecutar el proyecto
Para ejecutar este análisis, solo se requiere abrir el notebook de Colab proporcionado y ejecuta las celdas en orden.
