# Spark-Databricks-2

Utilizando Spark y Databricks

En este proyecto, se creó un clúster en Databricks para cargar tres bases de datos y manipularlas utilizando código Python con Spark y SQL.

## Creación del Clúster en Databricks

Primero, se crea un clúster en Databricks para poder cargar las tres bases de datos y manipularlas.

![image](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/121b5f97-da99-4764-9092-250a94f541da)
![image-1](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/c5e186ee-9d1b-45f1-bb31-fd86856c024e)

**Databricks:**

![image-3](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/692c9b56-9047-4c01-9423-7cfb0d992c69)
![image-2](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/a9e1b256-7799-4159-95b5-66e2586228c2)

Una vez que tenemos las bases de datos en Databricks, se procedió a manipular las bases de datos y responder a las siguientes actividades:

## 1. Conteo de Filas

Se contó el número de filas de cada tabla.

![image-4](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/f817fa76-2158-4945-94e6-85e6bcbd99ce)

## 2. Estudio de Rangos de Variables Numéricas

Se estudió el rango (máximo y mínimo) de cada variable numérica.

![image-5](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/73c7b750-9e17-43a0-b6e0-7951955f03a9)
![image-6](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/f580b73f-0ff4-43a2-9ca7-19952f401c77)
![image-7](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/2d219224-d9a8-4ca0-bd68-557eaa2a285e)

## 3. Variables Categóricas

La principal variable categórica encontrada se refiere a los tipos de tiendas (A, B y C) en la base de datos de stores.csv. Se estudiaron las diferentes categorías y el número de filas por cada tipo de tienda.

![image-8](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/367c8471-0de0-4183-b2f5-efa1e343a82a)

## 4. Valores Anómalos

Se buscaron valores inexistentes o anómalos. Se encontraron valores negativos en las variables MarkDown1, MarkDown2, MarkDown3 y MarkDown5.

![image-9](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/6766f1d7-5104-43fc-865c-e18f38707147)

## 5. Operaciones Join

Se realizaron operaciones Join entre las tablas para obtener información en conjunto de todas las fuentes de datos y conocer la información por tienda y ventas.

- **Join 1:** Stores con Sales.
- **Join 2:** Stores con features.
- **Join 3:** Sales con features


## 6. Agregaciones

Se obtiene la suma del total de las ventas del periodo analizado y el promedio de las ventas semanales en el periodo analizado:

![image-12](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/5c971518-2f49-42e2-aa4d-dcdd10ea2cf4)


Se crea vista gráfica para conocer por tienda y departamento la veta semanal, obteniendo que el departamento 2 de la tienda 12 es la que más venta semanal tiene.

![image-10](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/5ab8c149-9a53-46aa-b2bc-4e02e5cd02c1)
![image](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/8d526287-bc75-4924-adb9-2a5a851f2af4)

## 7. Agrupaciones

Se genera vista gráfica para conocer el fuel_price por fecha, obteniendo que el mayor fuel_price fue en abril del 2012.

![image-11](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/018962ab-7a0f-4f63-9089-d6d3fa5cce68)

Se obtiene información promedio de la temperatura por cada año para realizar un análisis y conocer el impacto en la venta de combustible y su oscilación a lo largo de los años.

![image-13](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/4fb6ca9a-8f40-4461-a115-f07310416ebe)


