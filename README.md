# Clasificación de la cobertura del suelo en Chimborazo

Recursos del trabajo final de **Maestría en Software** de la Universidad Técnica de Machala:
**"Clasificación de la cobertura del suelo en la provincia de Chimborazo mediante imágenes satelitales y aprendizaje automático"** (diciembre de 2022).

## Resumen

Clasificación supervisada en **Google Earth Engine** de imágenes satelitales en 7 clases de cobertura,
comparando tres algoritmos: **CART**, **Random Forest** y **SVM**.

**Clases:** agua · urbano · forestal · cultivo · suelo desnudo · arbustivo · nieve

## Contenido

| Archivo | Descripción |
|---|---|
| `chim_composicion.txt` | Composición de la imagen de la región |
| `chim_puntos_entrenamiento.txt` | Puntos de entrenamiento |
| `chim_puntos_prueba.txt` | Puntos de prueba |
| `chim_algoritmo_cart_completo.txt` | Clasificación con CART |
| `chim_algoritmo_rf_completo.txt` | Clasificación con Random Forest |
| `chim_algoritmo_svm_completo.txt` | Clasificación con SVM |
| `validacion.xlsx` | Matrices de confusión y validación de los casos de prueba |
| `link_codigo_fuentes.txt` | Enlaces a los scripts en Earth Engine |

## Uso

1. Necesitas una cuenta de Google con acceso a [Google Earth Engine](https://code.earthengine.google.com/).
2. Abre los enlaces de `link_codigo_fuentes.txt`, o copia el código de los `.txt` en el editor de Earth Engine.

## Autores

- Luis Efraín Quingue Guaminga
- Jennifer Katherin Célleri Pacheco
- Eduardo Alejandro Tusa Jumbo
- Wilmer Braulio Rivas Asanza
