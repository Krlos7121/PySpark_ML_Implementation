PySpark implementation for Natural Language Processing

# Prediciendo score de reseñas en Amazon a través del Natural Language Proccesing (NLP)

## Carlos Iván Fonseca Mondragón

## A01771689

Este proyecto busca, a través de una cadena de texto, deducir si corresponde a una reseña de tipo **negativa** (0) o **postiva** (1)

# Uso de la notebook

Esta notebook se ejecutó en un entorno de Google Colab, es necesario descargar el archivo comprimido .tgz del sitio de Kaggle [https://www.kaggle.com/datasets/kritanjalijain/amazon-reviews], agregarlo al mismo directorio en el que se ejecute el notebook, y descomentar la línea que extrae el .tgz. Si ya se tiene el dataset extraido en la carpeta **amazon_review_polarity_csv**, se puede omitir este paso.

Al final de la ejecución, el notebook arroja dos archivos en .csv, listos para ser interpretados en Tableau.

# Resultados obtenidos

El modelo actual logra un Accuracy cercano al 80%, además, imprime algunas de las estadísticas más importantes como el F1-Score, se pueden observar más detalles en la notebook.
