# Taller: Clasificación de secuencias de nucleótidos usando modelos de lenguaje genómicos basados en _transformers_

## Objetivo
¡Bienvenidos a nuestro Taller!

En este taller afinarás (_fine-tuning_) un Modelo de Lenguaje Genómico de DNA basado en un _ttransformer_
pre-entrenado llamado DNABERT-2 ([Zhou et al., 2024](../referencias/2024_Zhou_DNABERT-2EfficientFoundationModelBenchmarkForMulti-SpeciesGenome.pdf)) para predecir si una secuencia de 
nucleótidos es o no es un promotor de _E. coli_.

* Zhou, Zhihan, et al. "DNABERT-2: Efficient foundation model and benchmark for multi-species genomes." International Conference on Learning Representations. Vol. 2024. 2024.

## Descripción de la tarea
El modelo debe clasificar secuencias de 57 nucleótidos de longitud en dos categorías:
* no promotor: 0
* promotor: 1

## Conjunto de datos
Usaremos el conjunto de datos llamado [Promoter gene sequences](https://archive.ics.uci.edu/dataset/67/molecular+biology+promoter+gene+sequences) con 106 secuencias de 57 nucleótidos de longitud formadas con los símbolos {a, g, t, c}.

## Datos
## [Archivo con secuencias de promotores](../datos/promoters.csv)
