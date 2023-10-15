# Spark-Databricks-2
<<<<<<< HEAD
Utilizando spark y databricks

Se crea un  cluester en data bricks para poder cargar las 3 vaces de datos y poder manipularlas con codigo python utilizando spark y SQL.

![Alt text](image.png)
![Alt text](image-1.png)

Databricks

![Alt text](image-2.png)
![Alt text](image-3.png)

Una vez teniendo la base de datos en databricks, se procedio a manipular la base de datos y responder las siguientes actividades
1. Contar el número de filas de cada tabla
2. Estudiar el rango (máximo y mínimo) de cada variable numérica. 
3. Estudiar las diferentes categorías de las principales variables categóricas y el número de filas 
4. Buscar valores inexistentes o anómalos 
5. Realizar operaciones Join entre las tablas 
6. Obtener alguna agregación que sea relevante a la perspectiva del negocio
7. Obtener alguna agrupacion que sea relevante a la perspectiva del negocio


Punto 1:

![Alt text](image-4.png)

Punto 2:

![Alt text](image-5.png)
![Alt text](image-6.png)
![Alt text](image-7.png)

Punto 3:

La principal variable categórica encontrada fue en la base de datos de stores.csv y es la de type en la cual se puede observar en número de filas por cada tipo de tienda (A, B y C) 

![Alt text](image-8.png)

Punto 4:

Entre los valores anómalos que se encontraron en las variables categóricas de cada base de datos tenemos los siguientes:
MarkDown1, MarkDown2, MarkDown3, MarkDown5 y Weekly_Sales presentan valores negativos. 

![Alt text](image-9.png)

Punto 5:
Se realizaron 3 joins con la finalidad de poder obtener información en conjunto de todas las fuentes de datos, con estos joins pudimos conocer la información por tiendas y en especial por año de venta.

![Alt text](image-10.png)
![Alt text](image-11.png)

Punto 6:
Se realizo se agregagacion de ventas totales de todos los años, así como el promedio para poder comparar con los años más recientes.

![Alt text](image-12.png)


Punto 7:
información promedio de la temperatura por cada año para realizar un análisis y saber el impacto que se ha tenido en la venta del combustible y su oscilación a través de los años.

i![Alt text](image-13.png)
=======
Utilizando Spark y Databricks

En este proyecto, se creo un clúster en Databricks para cargar tres bases de datos y manipularlas utilizando código Python con Spark y SQL.

### Creación del Clúster en Databricks

Primero, se crea un clúster en Databricks para poder cargar las tres bases de datos y manipularlas. 

![image](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/121b5f97-da99-4764-9092-250a94f541da)
![image-1](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/c5e186ee-9d1b-45f1-bb31-fd86856c024e)

Databricks:

![image-3](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/692c9b56-9047-4c01-9423-7cfb0d992c69)
![image-2](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/a9e1b256-7799-4159-95b5-66e2586228c2)


Una vez que tenemos las bases de datos en Databricks, se procedio a manipular las bases de datos y responder a las siguientes actividades:

### 1. Conteo de Filas

Número de filas de cada tabla.

![image-4](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/f817fa76-2158-4945-94e6-85e6bcbd99ce)


### 2. Estudio de Rangos de Variables Numéricas

Rangos (máximo y mínimo) de cada variable numérica.

![image-5](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/73c7b750-9e17-43a0-b6e0-7951955f03a9)
![image-6](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/f580b73f-0ff4-43a2-9ca7-19952f401c77)
![image-7](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/2d219224-d9a8-4ca0-bd68-557eaa2a285e)


### 3. Variables Categóricas

La principal variable categórica encontrada se refiere a los tipos de tiendas (A, B y C) en la base de datos de stores.csv. Se estudian las diferentes categorías y el número de filas por cada tipo de tienda.

![image-8](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/367c8471-0de0-4183-b2f5-efa1e343a82a)


### 4. Valores Anómalos

Valores inexistentes o anómalos. Se encuentran valores negativos en las variables MarkDown1, MarkDown2, MarkDown3, MarkDown5 y Weekly_Sales.

![image-9](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/6766f1d7-5104-43fc-865c-e18f38707147)


### 5. Operaciones Join

Operaciones Join entre las tablas para obtener información en conjunto de todas las fuentes de datos y conocer la información por tiendas y años de venta.
Join 1: Stores con Sales.
Join 2: Stores con features.
Join 3: Sales con la base creada donde es posible obtener el año de la fecha.

### 6. Agregaciones

Se ha realizado una agregación 

![image-10](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/5ab8c149-9a53-46aa-b2bc-4e02e5cd02c1)

Esta peude ser otra

![image-12](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/5c971518-2f49-42e2-aa4d-dcdd10ea2cf4)


### 7. Agrupaciones

Se obtiene información promedio de la temperatura por cada año para realizar un análisis y conocer el impacto en la venta de combustible y su oscilación a lo largo de los años.

![image-13](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/4fb6ca9a-8f40-4461-a115-f07310416ebe)

esta es otra 

![image-11](https://github.com/jolosjoel/Spark-Databricks-2/assets/45809759/018962ab-7a0f-4f63-9089-d6d3fa5cce68)

>>>>>>> 7856d853ec914a61435dcd8df21b08e34d62afb6
