# Aprendiendo SQL
Práctica y aprendizaje de SQL para análisis de datos. Incluye consultas, filtros, JOINs, agregaciones, subconsultas y ejercicios prácticos.

# Funciones que se utilizan

**SELECT:** Sirve para seleccionar las columnas que queremos analizar
```
SELECT nombre, edad
FROM clientes;
```

**FROM:** Indica de que tabla queremos ver los datos
```
SELECT *
FROM clientes;
```
**WHERE:** Permite filtrar registros según una condición.
```
SELECT *
FROM clientes
WHERE edad > 30;
```
Devuelve solo los clientes mayores de 30 años.

**DISTINCT:** Elimina los valores duplicados

```
SELECT DISTINCT ciudad
FROM clientes;
```

**ORDER BY:** Sirve para ordenar los resultados. ASC --> Ascendente, DESC --> Descendente.  

```
SELECT *
FROM clientes
ORDER BY edad DESC;
```
## 📊 Funciones de agregación

Son muy importantes para análisis de datos.

**COUNT():** Cuenta la cantidad de registros.

```
SELECT COUNT(*)
FROM clientes;
```
Cuenta cuántos clientes hay.

También:

COUNT(columna)

cuenta los valores *no nulos* de esa columna.

**SUM():** Calcula la suma de los valores.

```
SELECT SUM(ventas)
FROM pedidos;
```
Obtiene el total de ventas.

**AVG():** Calcula el promedio.
```
SELECT AVG(edad)
FROM clientes;
```
Obtiene la edad promedio.

**MIN():** Obtiene el valor mínimo.

```
SELECT MIN(precio)
FROM productos;
```

**MAX():** Obtiene el valor máximo.

```
SELECT MAX(precio)
FROM productos;
```



