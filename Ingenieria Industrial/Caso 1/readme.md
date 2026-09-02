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

#### Tabla 3
<img width="517" height="209" alt="image" src="https://github.com/user-attachments/assets/a75d88e3-4cbd-459b-bce4-07b5b61fed19" />

#### Gráfico 1: 

<img width="593" height="355" alt="image" src="https://github.com/user-attachments/assets/68d0707a-2435-4f9e-b759-09df24f00a06" />

Lo que se puede observar en el gráfico, es que la producción es constante de 72 empanadas por hora, ya que tenemos un único horno. En cambio, la demanda en ciertos momentos supera la producción. 

## 7. Análisar la utilización

#### Tabla 4:

<img width="523" height="210" alt="image" src="https://github.com/user-attachments/assets/8d93d79e-76d3-47f9-8cfa-8d72d34ea523" />

❕ Se puede observar que en la mayor parte del día se puede ver cuantitativamente que la cocción no tiene capacidad suficiente.

## 8. Análizar el trabajo en proceso (WIP)

<img width="511" height="208" alt="image" src="https://github.com/user-attachments/assets/7741a71a-392e-4efe-be60-ef5f22f9bc69" />

*Formula del trabajo en proceso: WIP final = WIP inicial + entradas − salidas*

❕ Se puede ver que el CUELLO DE BOTELLA es el horno, ya que eso genera acumulación de empanadas y genera retrasos en las entregas.

## 8. Buscamos la causa raiz del problema

### Problema: Retraso de los pedidos

Herramienta: 5 Por qué?

¿Por qué?
1. Porque se acumulan empanadas antes de cocción.
2. Porque el tiempo de ciclo es elevado y existen tiempos de carga y descarga.
3. Porque el método de trabajo no está estandarizado.
4. Porque el horno no puede procesar todo lo que llega.
5. Porque no existe un procedimiento definido para organizar las bandejas y las cargas.

## 9. Proponer alternativas de solución

Alternativa 1
* Optimizar la carga del horno

Alternativa 2 
* Reducir tiempos de carga y descarga

Alternativa 3
* Estandarizar el método de cocción.

Alternativa 4
* Agregar otro horno

#### Matriz de Impacto vs Esfuerzo

<img width="633" height="389" alt="image" src="https://github.com/user-attachments/assets/32a79d26-c2f0-4bb1-bc9e-f39bedc12568" />


   











