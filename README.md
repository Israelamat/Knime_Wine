# Proyecto KNIME: Clasificación de Vinos

Este proyecto en KNIME utiliza un dataset con características químicas de diferentes vinos para predecir la clase (variedad) a la que pertenecen.

## Dataset

El dataset contiene las siguientes columnas:

| Columna                      | Descripción                         |
|-----------------------------|-----------------------------------|
| Class                       | Clase objetivo a predecir          |
| Alcohol                     | Contenido de alcohol               |
| Malic acid                  | Ácido málico                      |
| Ash                         | Cenizas                          |
| Alcalinity of ash           | Alcalinidad de cenizas            |
| Magnesium                   | Magnesio                         |
| Total phenols               | Fenoles totales                  |
| Flavanoids                  | Flavonoides                     |
| Nonflavanoid phenols        | Fenoles no flavonoides           |
| Proanthocyanins             | Proantocianinas                 |
| Color intensity             | Intensidad del color              |
| Hue                         | Matiz                            |
| OD280/OD315 of diluted wines| Ratio OD280/OD315 de vinos diluidos |
| Proline                     | Prolina                         |

## Objetivo

Construir un modelo que, a partir de las características químicas de un vino, pueda predecir a qué clase (variedad) pertenece.

## Metodología

- Procesamiento y preparación de datos con KNIME.  
- Conversión de la columna `Class` a nominal para usarla como variable objetivo.  
- Entrenamiento del modelo usando el nodo K Nearest Neighbor (KNN).  
- Evaluación del modelo con el nodo Scorer para obtener métricas como matriz de confusión y precisión.

## Uso

1. Abrir el workflow en KNIME.  
2. Ejecutar los nodos en orden para preparar los datos, entrenar el modelo y evaluar resultados.  
3. Analizar la matriz de confusión para evaluar el desempeño del modelo.

[![Captura-de-pantalla-2025-06-24-141720.jpg](https://i.postimg.cc/43vnW2BP/Captura-de-pantalla-2025-06-24-141720.jpg)](https://postimg.cc/gwJYJs9L)
