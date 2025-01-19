# Detección del Parkinson mediante la voz usando técnicas de Machine Learning
Este proyecto de grado para optar al título de Ingeniería Electrónica en la Universidad Industrial de Santander (UIS) tiene como objetivo la detección de la enfermedad de Parkinson mediante el análisis de señales de voz. Se utilizaron dos conjuntos de datos principales:

**Oxford Parkinson's Disease Detection Dataset (Parkinsons)**: Conjunto de datos desbalanceado que incluye características extraídas de 195 grabaciones de voz de 31 pacientes, de los cuales 23 tienen Parkinson y 8 son controles sanos. Este dataset es ampliamente utilizado como referencia en investigaciones relacionadas, aunque fue desarrollado con hablantes angloparlantes.

**Corpus PC-GITA**: Conjunto de datos equilibrado creado por el Grupo de Investigación en Telecomunicaciones Aplicadas (GITA) de la Universidad de Antioquia. Incluye grabaciones de 50 pacientes diagnosticados con Parkinson y 50 controles sanos, con igual distribución por género y un rango de edades representativo. Este corpus se enfoca en hablantes de español, siendo particularmente relevante para nuestro contexto lingüístico.
# Consideraciones adicionales
El proyecto está organizado en las siguientes carpetas principales:

📁 **Modelos**:
Esta carpeta contiene los notebooks desarrollados en Python, utilizando el formato de Jupyter Notebooks para organizar las etapas en celdas, lo que facilita su ejecución y comprensión.  Incluye el entrenamiento de los modelos de aprendizaje automático propuestos, como ADA Boost, Random Forest, Gradient Boosting y Bagging, entre otros. Los modelos fueron entrenados con los subconjuntos de datos generados mediante los métodos de selección de características (CHI², Matriz de Correlación y Extra Tree), aplicados a los siete conjuntos originales: Vocal A, Vocal E, Vocal I, Vocal O, Vocal U, Todas las Vocales juntas y Parkinsons. 

📁 **Recopilación de los resultados**:
En esta carpeta se encuentran recursos complementarios relacionados con el proyecto, incluyendo archivos con las características más relevantes seleccionadas para cada modelo, los hiperparámetros utilizados y los resultados obtenidos de todos los subconjuntos de datos.
