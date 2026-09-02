# Optimización del proceso de empanada 

## Situación del problema
Una pequeña fábrica de empanadas presenta demoras en la entrega de pedidos durante determinados períodos del día. Se busca analizar el proceso productivo, determinar si la capacidad disponible permite satisfacer la demanda, identificar restricciones y proponer mejoras.

## 1.Objetivo 
Mejorar el proceso de producción y cumplir con la demanda.

## 2.Proceso de producción

Para conocer como funciona actualmente nuestro proceso. 

<img width="683" height="365" alt="image" src="https://github.com/user-attachments/assets/4c70d895-d987-4028-a8c4-f356eb32f84e" />

## 3.Definir las etapas y recursos

#### Tabla 1: Tiempos de procesos

<img width="471" height="179" alt="image" src="https://github.com/user-attachments/assets/13b25e46-8790-4f6d-bce7-651b29fe7e91" />

<img width="463" height="186" alt="image" src="https://github.com/user-attachments/assets/69c90da0-0192-4a88-8e02-6e8ed2b39bd4" />

*Los datos utilizados son simulados con fines académicos y fueron construidos para representar un escenario hipotético de producción.*

## 4. Calcular la capacidad de cada etapa

<img width="608" height="177" alt="image" src="https://github.com/user-attachments/assets/2265668d-41ae-40bc-a472-9d3d57360aa8" />

*Capacidad=3600 segundos/tiempo de ciclo (seg). cantidad de operarios*

❗❗ Como primera observación es que el que tiene menor capacidad es el momento de la cocción de las empanadas. Es una restricción potencial.

## 5. Incorporamos la demanda 

#### Tabla 2: Demanda

<img width="258" height="206" alt="image" src="https://github.com/user-attachments/assets/c5393895-4d4d-4018-98ab-fb0bc60553f2" />

❗❗ Acá podemos observar el comportamiento de los pedidos según la hora.

## 6. Comparación de la Capacidad y la demanda

<img width="517" height="209" alt="image" src="https://github.com/user-attachments/assets/a75d88e3-4cbd-459b-bce4-07b5b61fed19" />

### Gráfico 1: 

<img width="593" height="355" alt="image" src="https://github.com/user-attachments/assets/68d0707a-2435-4f9e-b759-09df24f00a06" />

Lo que se puede observar en el gráfico, es que la producción es constante de 72 empanadas por hora, ya que tenemos un único horno. En cambio, la demanda en ciertos momentos supera la producción. 










