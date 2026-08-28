# Optimización del proceso de empanada 

## Situación del problema
Una fábrica de empanadas presenta retrasos en la entrega de pedidos durante los períodos de mayor demanda. Se busca analizar el proceso productivo, identificar el cuello de botella y proponer mejoras que permitan aumentar la capacidad sin incrementar significativamente los costos.
### Información 
#### Tabla 1: Tiempos de procesos

<img width="626" height="189" alt="image" src="https://github.com/user-attachments/assets/bd574885-3a82-42b0-b9a3-ebdfa640b5bf" />

*Capacidad=3600 segundos/tiempo de ciclo (seg). cantidad de operarios*

#### Tabla 2: Producción

<img width="751" height="188" alt="image" src="https://github.com/user-attachments/assets/31785a93-02bd-4c6f-87fc-ff0645f1f010" />

** Definición: ** WIP → cuántas empanadas están dentro del sistema esperando/procesándose.

** Definición: ** Tiempo de espera → cuánto tiempo tiene que esperar una empanada antes de ser procesada.

*WIP acumulado= WIP anterior + entrada - salida* 

! Vamos a suponer que el horno produce 72 unidades/hora

#### Gráfico 1: Demanda vs Producción 

<img width="596" height="367" alt="image" src="https://github.com/user-attachments/assets/ff3ae3fe-a210-4e5a-9b1a-271bfd9f3cf5" />




