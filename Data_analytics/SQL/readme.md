# Aprendiendo SQL
Práctica y aprendizaje de SQL para análisis de datos. Incluye consultas, filtros, JOINs, agregaciones, subconsultas y ejercicios prácticos.

# Funciones que se utilizan

**SELECT:** Sirve para seleccionar las columnas que queremos analizar

**FROM:** Indica de que tabla queremos ver los datos

**WHERE:** Permite filtrar registros según una condición.
`SELECT *`

`FROM clientes`

`WHERE edad > 30;`

## Prácticas con Big Query Google
1. Analizar la información con SELECT

<img width="1192" height="486" alt="image" src="https://github.com/user-attachments/assets/ebf7e493-f6b3-414c-b43b-639a6d5992da" />

2. Obtener una lista de los distintos productos disponibles (id y nombre)

Se seleccionan las columnas de interes de la tabla productos.

<img width="913" height="478" alt="image" src="https://github.com/user-attachments/assets/3f0d02c4-c575-43cc-abc9-537b80b9ab20" />

3. Obtener una lista de los distintos clientes disponibles (id y nombre).

Se seleccionan las columnas de interes de la tabla clientes.

<img width="915" height="464" alt="image" src="https://github.com/user-attachments/assets/4156ebe8-400f-41f1-a0d0-f5644fab8b7d" />

4. Obtener una lista de productos, id y nombre, que fueron entregados (‘Delivered’).

Solo muestra los productos que tienen como condición "Delivered" o sea cruza dos tablas que van a coincidir con el ID de productos

<img width="911" height="460" alt="image" src="https://github.com/user-attachments/assets/e80f77b3-e03c-48f1-b3f1-b407b35d2a32" />

5. Obtener una lista de clientes, nombre y dirección, cuyos pedidos están pendientes (‘Pending’).

Solo muestra la lista de clientes, nombre y dirección cuyo pedido esta en "Pending", acá cruzamos clientes con entregas.

<img width="916" height="498" alt="image" src="https://github.com/user-attachments/assets/77583226-9e1d-48e2-aced-822220b7d4f9" />

6. Obtener una lista de cliente, id y nombre, junto con los productos que compraron.

<img width="913" height="481" alt="image" src="https://github.com/user-attachments/assets/b48d5881-d3fb-4624-87c3-14077176a9aa" />
