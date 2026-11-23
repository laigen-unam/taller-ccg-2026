# Taller: Clasificación de secuencias de nucleótidos usando modelos de lenguaje genómicos basados en _transformers_

## Objetivo
**¡Bienvenidos a nuestro Taller!**

En este taller usted afinará (_fine-tuning_) un **Modelo de Lenguaje Genómico de DNA** basado en un _transformer_
pre-entrenado. Este Modelo de Lenguaje se llama **DNABERT-2** ([Zhou et al., 2024](https://github.com/laigen-unam/taller-ccg-2026/tree/main/referencias)) y 
será afinado para predecir si una secuencia de 
nucleótidos es o no es un promotor de _E. coli_.

## Descripción de la tarea
El modelo debe clasificar secuencias de 57 nucleótidos de longitud en dos categorías:
* no promotor: 0
* promotor: 1

## Datos
Usaremos el conjunto de datos llamado Promoter gene sequences con 106 secuencias de 57 nucleótidos de longitud formadas con los símbolos {a, g, t, c}.

* En este enlace, usted puede descargar el [archivo con secuencias de promotores](https://github.com/laigen-unam/taller-ccg-2026/tree/main/datos).

## Cuaderno de trabajo (notebook)
Para el Taller usaremos un cuaderno de trabajo que contiene las instrucciones litas para su desarrollo.

* En este enlace, usted puede descargar el [cuaderno de trabajo](https://github.com/laigen-unam/taller-ccg-2026/tree/main/notebook).

## Referencias
* Zhou, Zhihan, et al. "DNABERT-2: Efficient foundation model and benchmark for multi-species genomes." International Conference on Learning Representations. Vol. 2024. 2024.

---
## Conferencia
**El camino de la IA en la genómica: de Turing a AlphaGenome**

Si no tuvo oportunidad de asistir a la conferencia previa al taller, en este enlace puede descargar [la presentación](https://github.com/laigen-unam/taller-ccg-2026/tree/main/conferencia).
