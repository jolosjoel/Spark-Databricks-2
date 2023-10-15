# Spark-Databricks-2
Utilizando Spark y Databricks

En este proyecto, hemos creado un clúster en Databricks para cargar tres bases de datos y manipularlas utilizando código Python con Spark y SQL.

### Creación del Clúster en Databricks

Primero, hemos creado un clúster en Databricks para poder cargar las tres bases de datos y manipularlas. 

![image](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/121b5f97-da99-4764-9092-250a94f541da)
![image-1](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/c5e186ee-9d1b-45f1-bb31-fd86856c024e)

Databricks:

![image-3](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/692c9b56-9047-4c01-9423-7cfb0d992c69)
![image-2](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/a9e1b256-7799-4159-95b5-66e2586228c2)


Una vez que tenemos las bases de datos en Databricks, hemos procedido a manipular las bases de datos y responder a las siguientes actividades:

### 1. Conteo de Filas

Hemos contado el número de filas de cada tabla.

![image-4](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/f817fa76-2158-4945-94e6-85e6bcbd99ce)


### 2. Estudio del Rango de Variables Numéricas

Hemos estudiado el rango (máximo y mínimo) de cada variable numérica.

![image-5](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/73c7b750-9e17-43a0-b6e0-7951955f03a9)
![image-6](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/f580b73f-0ff4-43a2-9ca7-19952f401c77)
![image-7](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/2d219224-d9a8-4ca0-bd68-557eaa2a285e)


### 3. Variables Categóricas

La principal variable categórica encontrada se refiere a los tipos de tiendas (A, B y C) en la base de datos de stores.csv. Hemos estudiado las diferentes categorías y el número de filas por cada tipo de tienda.

![image-8](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/367c8471-0de0-4183-b2f5-efa1e343a82a)


### 4. Valores Anómalos

Hemos buscado valores inexistentes o anómalos. Se encontraron valores negativos en las variables MarkDown1, MarkDown2, MarkDown3, MarkDown5 y Weekly_Sales.

![image-9](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/6766f1d7-5104-43fc-865c-e18f38707147)


### 5. Operaciones Join

Hemos realizado operaciones Join entre las tablas para obtener información en conjunto de todas las fuentes de datos y conocer la información por tiendas y años de venta. Adiconal se obtubo información promedio de la temperatura por cada año para realizar un análisis y conocer el impacto en la venta de combustible y su oscilación a lo largo de los años.

![image-13](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/d85232e6-7e73-4cca-9b68-fc3c97730318)
![image-11](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/b4e0385f-b4d0-46cf-a395-318269954df4)
![image-10](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/16fa5c7f-0653-41af-9520-f5a365f99755)


### 6. Agregaciones

Se ha realizado una agregación de ventas totales de todos los años, así como el promedio para poder comparar con los años más recientes.

![image-12](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/dba836a2-24b7-4ac9-bf37-207904ff6004)


### 7. Agrupaciones

Hemos obtenido información promedio de la temperatura por cada año para realizar un análisis y conocer el impacto en la venta de combustible y su oscilación a lo largo de los años.

