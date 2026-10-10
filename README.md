# 🗣️ Procesamiento del Habla

Repositorio correspondiente a la materia **Procesamiento del Habla** de la Tecnicatura en Inteligencia Artificial y Ciencia de Datos.

## 📚 Trabajos Prácticos

### TP1 - Procesamiento del Habla: Web Scraping

En este trabajo práctico se aplicaron diferentes técnicas para la obtención, limpieza, procesamiento y representación de texto utilizando Python.

Se trabajó con:

- Web Scraping.
- Limpieza y normalización de texto.
- Tokenización.
- Eliminación de stopwords.
- Stemming y lematización.
- Nube de palabras (WordCloud).
- Representación de texto mediante CountVectorizer.
- One-Hot Encoding.
- TF-IDF.

### TP3 - Chatbots con TF-IDF y Embeddings

En este trabajo práctico se desarrollaron y compararon dos chatbots de atención al cliente para **Giulya**, un comercio de accesorios de moda y artículos de viaje, utilizando diferentes técnicas de Procesamiento del Lenguaje Natural.

Se trabajó con:

- Creación de un diccionario de 25 preguntas y respuestas frecuentes.
- Representación de texto mediante TF-IDF.
- Generación de embeddings utilizando el modelo preentrenado `es_core_news_md` de spaCy.
- Cálculo de similitud del coseno para seleccionar las respuestas.
- Implementación de dos chatbots interactivos en Python.
- Evaluación y comparación de los resultados obtenidos.

**Resultados de la comparación:**

Se realizaron 12 consultas a ambos chatbots, obteniendo los siguientes resultados:

| Modelo | Respuestas correctas | Porcentaje de aciertos |
|---|---|---|
| TF-IDF | 10 de 12 | 83,3 % |
| Embeddings | 8 de 12 | 66,7 % |

**Conclusión:** TF-IDF obtuvo mejores resultados para este conjunto de preguntas, demostrando que un modelo más complejo no necesariamente tiene un mejor rendimiento. La elección de una técnica de NLP depende de las características del problema, los datos utilizados y los resultados obtenidos.

## 🛠️ Tecnologías utilizadas

- Python
- Google Colab
- NumPy
- Pandas
- NLTK
- spaCy
- Gensim
- scikit-learn
- BeautifulSoup
- Selenium
- WordCloud

## 📁 Archivos

- `CARRILLO_JULIA_PH_TP1.ipynb`: notebook correspondiente al Trabajo Práctico N.º 1.
- `CARRILLO_JULIA_PH_TP3.ipynb`: notebook correspondiente al Trabajo Práctico N.º 3.

## 👩‍💻 Autora

**Julia Belén Carrillo**

Estudiante de la Tecnicatura en Inteligencia Artificial y Ciencia de Datos.



