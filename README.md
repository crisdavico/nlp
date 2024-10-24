# Repositorio de Desafíos de NLP

¡Bienvenido al **Repositorio de Desafíos de NLP**! Este repositorio contiene una colección de desafíos de Procesamiento de Lenguaje Natural (NLP) diseñados para ayudarte a practicar y mejorar tus habilidades en este campo.

## Tabla de Contenidos

- [Descripción General](#descripción-general)
- [Desafíos](#desafíos)
- [Cómo Empezar](#cómo-empezar)
- [Requerimientos](#requerimientos)
- [Cómo Contribuir](#cómo-contribuir)
- [Licencia](#licencia)
- [Contacto](#contacto)

## Descripción General

El Procesamiento de Lenguaje Natural (NLP, por sus siglas en inglés) es un campo de la inteligencia artificial que se enfoca en la interacción entre las computadoras y el lenguaje humano. NLP involucra diversas tareas como la comprensión del lenguaje, la traducción automática, el análisis de sentimientos, entre otros. Este repositorio es una colección de desafíos prácticos que cubren varios aspectos del NLP, diseñados para ayudar a los entusiastas y profesionales a mejorar sus habilidades.

## Desafíos

### Desafío 1: Vectorización TF-IDF y Similitud de Textos

- **Descripción:** En este desafío, trabajarás con técnicas de vectorización utilizando TF-IDF (Term Frequency-Inverse Document Frequency) para medir la similitud entre categorías de textos. También explorarás la similitud entre palabras, la creación de matrices documento-término y término-documento.
- **Dificultad:** Medio

### Desafío 2: Word2Vec y Test de Analogías

- **Descripción:** Este desafío se enfoca en el uso de la librería Word2Vec de Gensim para entrenar un modelo de vectores de palabras y realizar pruebas de analogía basadas en el texto de *Historia del Tiempo* de Stephen Hawking. Utilizarás un conjunto de datos basado en el libro para analizar las relaciones semánticas entre palabras y construir pruebas de analogía (por ejemplo, `rey - hombre + mujer = reina`).
- **Dificultad:** Medio
- **Objetivos:**
   1. Entrenar un modelo Word2Vec utilizando el texto procesado de *Historia del Tiempo*.
   2. Realizar tests de analogías para encontrar relaciones entre conceptos científicos y no científicos presentes en el texto.
   3. Explorar la precisión del modelo y ajustar sus parámetros para mejorar los resultados.
   
### Desafío 3: Predicción de Palabras con LSTM

- **Descripción:** En este desafío, implementarás un modelo de red neuronal LSTM (Long Short-Term Memory) para predecir la próxima palabra en una secuencia de texto. El objetivo es entrenar el modelo para comprender patrones y relaciones contextuales en el texto y utilizar diferentes métodos de búsqueda, como greedy search y beam search, para mejorar la predicción. Además, explorarás diferentes formas de tokenización, tanto a nivel de palabra como de carácter.
- **Dificultad:** Avanzado
- **Objetivos:**
   1. Entrenar un modelo LSTM que prediga la próxima palabra en una secuencia de texto.
   2. Implementar técnicas de búsqueda para mejorar la predicción, comparando greedy search y beam search.
   3. Explorar la tokenización por palabra y por carácter para observar cómo afectan al rendimiento del modelo.
   4. Evaluar el modelo en términos de precisión y ajuste de hiperparámetros para mejorar los resultados.

Con este desafío, podrás profundizar en las arquitecturas de redes neuronales recurrentes (RNNs) y sus aplicaciones en procesamiento de lenguaje natural (NLP).

### Desafío 4: Chatbot con Modelos Seq2Seq

- **Descripción:** En este desafío, implementarás un chatbot utilizando un modelo de red neuronal Seq2Seq basado en la arquitectura Encoder-Decoder. El objetivo es entrenar el modelo para que pueda generar respuestas coherentes en un entorno de conversación, entendiendo los patrones y el contexto del diálogo.

- **Dificultad:** Avanzado

- **Objetivos:**
   1. Entrenar un modelo Seq2Seq con codificador y decodificador que pueda generar respuestas coherentes a partir de entradas de conversación.
   2. Evaluar el chatbot en términos de coherencia de las respuestas y precision.

### Desafío 5: Análisis de Sentimientos con BERT
- **Descripción:** Este desafío se enfoca en la implementación de un modelo de análisis de sentimientos utilizando el modelo preentrenado BERT (Bidirectional Encoder Representations from Transformers) para clasificar textos en cinco categorías de sentimientos. Se entrenará el modelo en un conjunto de datos etiquetado en cinco clases y se evaluará su desempeño a través de métricas de precisión, F1-score y matrices de confusión.

- **Dificultad:** Avanzado

- **Objetivos:**
   1. Entrenar un modelo de BERT sobre un conjunto de datos de análisis de sentimientos con 5 clases.
   2. Evaluar el rendimiento del modelo utilizando métricas clave como precisión, F1-score, y una matriz de confusión.
   3. Identificar y aplicar técnicas de optimización para mitigar el overfitting.
   4. Visualizar y analizar la evolución del entrenamiento y la validación a lo largo de las épocas.


Cada desafío incluye una descripción de las consignas, datos de ejemplo, y su resolución.

## Cómo Empezar

Para comenzar con los desafíos:

1. **Clona el repositorio:**

   ```bash
   git clone https://github.com/crisdavico/nlp.git
   cd nlp
   ```

2. **Navega al directorio del desafío:**

   Cada desafío tiene su propia carpeta. Navega a la carpeta del desafío deseado para ver la descripción del problema y comenzar a trabajar en la solución.

3. **Ejecuta los scripts proporcionados:**

   Algunos desafíos pueden incluir scripts de inicio o notebooks de Jupyter. Sigue las instrucciones proporcionadas en la carpeta del desafío para ejecutar estos scripts.

## Requerimientos

Este repositorio incluye un archivo `requirements.txt` que contiene las dependencias necesarias para ejecutar los desafíos. Para instalar las dependencias, utiliza el siguiente comando:

```bash
pip install -r requirements.txt
```

El archivo `requirements.txt` incluye librerías esenciales como:

- **Gensim**: Para el entrenamiento de modelos Word2Vec.
- **Scikit-learn**: Para operaciones de procesamiento de datos y métricas de similitud.
- **Numpy**: Utilizado para operaciones matemáticas y manipulación de matrices.
- **Pandas**: Para la gestión de estructuras de datos.
- **Matplotlib**: Para visualización de resultados.

Es importante tener estas librerías correctamente instaladas para garantizar que los notebooks y scripts se ejecuten sin problemas.

## Cómo Contribuir

¡Las contribuciones son bienvenidas! Si tienes una idea para un nuevo desafío o deseas mejorar los existentes, siéntete libre de bifurcar este repositorio y enviar una solicitud de pull. Por favor, asegúrate de que tus contribuciones sigan las siguientes pautas:

- Proporciona una descripción clara del problema y una guía de solución.
- Asegúrate de que tu desafío esté bien documentado y sea fácil de entender.
- Prueba tus scripts o notebooks para asegurarte de que se ejecuten sin errores.

## Licencia

Este repositorio está licenciado bajo la [Licencia Creative Commons Atribución-NoComercial-CompartirIgual 4.0 Internacional](LICENSE). Puedes utilizar los desafíos para fines personales o educativos, pero no para fines comerciales.

## Contacto

Si tienes alguna pregunta o comentario, no dudes en abrir un issue o contactarme directamente en [crisdavico95@gmail.com].