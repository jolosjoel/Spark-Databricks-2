# Spark-Databricks-2
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