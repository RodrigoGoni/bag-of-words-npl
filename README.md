# Bag of Words - NLP

Proyecto de procesamiento de lenguaje natural utilizando técnicas de Bag of Words y vectorización TF-IDF sobre el dataset 20 Newsgroups.

## Descripción

Este proyecto implementa y analiza diferentes técnicas de NLP:

1. **Vectorización de documentos** - Cálculo de similaridad entre documentos usando TF-IDF
2. **Clasificación por prototipos** - Modelo zero-shot basado en vecino más cercano
3. **Modelos Naïve Bayes** - Clasificación optimizada con MultinomialNB y ComplementNB
4. **Similaridad entre palabras** - Análisis de co-ocurrencia mediante matriz término-documento

## Requisitos

```bash
pip install -r requirements.txt
```

## Dataset

20 Newsgroups: conjunto de documentos clasificados en 20 categorías temáticas (religión, deportes, tecnología, política, etc.)

## Resultados Principales

- **F1-Score Macro (Clasificación por prototipos)**: 0.5050
- **F1-Score Macro (MultinomialNB)**: 0.6833
- **F1-Score Macro (ComplementNB)**: 0.6950

ComplementNB demuestra el mejor rendimiento en este dataset multiclase.

## Uso

Abrir y ejecutar `main.ipynb` en Jupyter Notebook o VS Code.

## Licencia

Ver archivo LICENSE
