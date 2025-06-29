# Deteccion de spam

🎯 Objetivo del Proyecto
El objetivo principal de este proyecto es desarrollar y evaluar un modelo de clasificación robusto para identificar mensajes no deseados, contribuyendo a una mejor experiencia de usuario y seguridad en la comunicación digital.

✨ Características Principales
Preprocesamiento de Texto Avanzado: Incluye normalización, tokenización, eliminación de stopwords y lematización para preparar los datos de texto de manera efectiva.

Vectorización TF-IDF: Transforma el texto preprocesado en representaciones numéricas que los algoritmos de machine learning pueden entender, capturando la importancia de las palabras en el contexto de los mensajes.

Modelos SVM: Entrenamiento y evaluación de dos tipos de kernels de SVM:

Kernel Lineal: Ideal para conjuntos de datos linealmente separables, ofreciendo rapidez y buena interpretabilidad.

Kernel RBF (Radial Basis Function): Capaz de manejar relaciones no lineales en los datos, a menudo resultando en una mayor precisión.

Balanceo de Datos: Implementación de técnicas para balancear el dataset, asegurando que el modelo no se sesgue hacia la clase mayoritaria y mejorando su rendimiento general.

Evaluación Detallada: Análisis del rendimiento del modelo utilizando métricas clave como la precisión, la matriz de confusión y el informe de clasificación (precision, recall, f1-score).

Funcionalidad de Predicción: Incluye una función para clasificar nuevos mensajes en tiempo real, demostrando la aplicabilidad práctica del modelo.

🛠️ Tecnologías Utilizadas
Python 3.x

Pandas: Para manipulación y análisis de datos.

NumPy: Para operaciones numéricas eficientes.

NLTK (Natural Language Toolkit): Para el procesamiento de texto.

Scikit-learn: Para la implementación de modelos de Machine Learning (SVM, TfidfVectorizer, train_test_split, accuracy_score, confusion_matrix, classification_report).

Matplotlib: Para visualización de datos y matrices de confusión.

