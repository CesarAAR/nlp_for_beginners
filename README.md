# 🧠 Introducción al Procesamiento de Lenguaje Natural (NLP)

Este cuaderno (`.ipynb`) contiene una introducción práctica a los conceptos fundamentales del **Procesamiento de Lenguaje Natural (NLP)**, un área de la inteligencia artificial que busca permitir que las computadoras comprendan, interpreten y generen lenguaje humano.

El objetivo de este notebook es servir como material de referencia y práctica para comprender los principios básicos detrás de las técnicas más comunes en NLP, desde la **tokenización** hasta la **similitud de vectores**.

---

## 📘 Contenido del cuaderno

### 1️⃣ Tokenización
La **tokenización** es el primer paso en la mayoría de los procesos de NLP.  
Consiste en dividir un texto en unidades más pequeñas llamadas *tokens* (palabras, frases o incluso caracteres).  
Esto permite que el texto sea analizado y procesado de forma estructurada.

📍 *Ejemplo:* dividir `"El lenguaje natural es fascinante"` en `["El", "lenguaje", "natural", "es", "fascinante"]`.

---

### 2️⃣ Stop Words
Las **stop words** son palabras comunes (como *el, la, de, en, y*) que generalmente se eliminan porque no aportan valor semántico relevante al análisis.  
El objetivo es reducir el ruido en el procesamiento de texto.

📍 *Ejemplo:* eliminar “el” o “de” de un texto antes del análisis.

---

### 3️⃣ Stemming y Lemmatización
Ambas técnicas buscan reducir las palabras a su forma base:

- **Stemming:** recorta palabras eliminando sufijos y prefijos, sin considerar el contexto gramatical.  
  📍 *Ejemplo:* “corriendo”, “corrió” → “corr”.

- **Lematización:** transforma las palabras a su forma raíz (*lema*), considerando su estructura y significado.  
  📍 *Ejemplo:* “corriendo”, “corrió” → “correr”.

Estas técnicas ayudan a normalizar el texto y mejorar la precisión de los modelos.

---

### 4️⃣ Introducción a la Similitud de Vectores
En NLP, los textos se representan como **vectores numéricos**, lo que permite medir su similitud.  
Se utilizan métricas como el **cosine similarity** para determinar qué tan parecidos son dos documentos o frases.

📍 *Ejemplo:* comparar la similitud entre  
> “El perro corre rápido”  
> “El gato corre veloz”

---

### 5️⃣ Introducción al Método TF-IDF
El **TF-IDF (Term Frequency – Inverse Document Frequency)** es una técnica estadística que evalúa la importancia de una palabra dentro de un documento en relación con una colección de documentos.

- **TF (Frecuencia de término):** mide cuántas veces aparece una palabra en un documento.  
- **IDF (Frecuencia inversa de documentos):** mide la relevancia global de la palabra en el conjunto de textos.

📍 *Ejemplo:* Palabras como *“de”* o *“el”* tienen bajo peso TF-IDF, mientras que términos más específicos como *“machine learning”* tienen alto peso.

---

### 6️⃣ TF-IDF Práctico y Word Embeddings Neuronales  
Esta nueva sección amplía las notas anteriores con:

#### 🧩 Parte Práctica de TF-IDF  
Aplicación práctica del método TF-IDF con un conjunto de textos para comparar su rendimiento frente a la representación basada en frecuencia de palabras.  
Se analizan los resultados y se visualizan las puntuaciones TF-IDF más relevantes.

#### 🧠 Introducción a Word Embeddings Neuronales  
Introducción teórica a los **word embeddings neuronales**, un enfoque más avanzado que permite capturar relaciones semánticas entre palabras mediante representaciones vectoriales densas.  
Se explican conceptos como:
- Espacios vectoriales semánticos  
- Analogías de palabras (por ejemplo, “Rey - Hombre + Mujer = Reina”)  
- Modelos populares como **Word2Vec** y **GloVe**

---
## 🧩 Tecnologías y librerías utilizadas
- **Python 3**
- **NLTK**
- **spaCy**
- **scikit-learn**
- **NumPy / Pandas**
- **Word2Vec**
- **pymupdf**

---

## 🎯 Objetivo del proyecto
Este notebook tiene fines educativos y de autoaprendizaje.  
Permite comprender los conceptos básicos de procesamiento de texto y sirve como base para avanzar hacia temas más complejos, como:

- Modelos de lenguaje (Word2Vec, GloVe, BERT)
- Clasificación de texto
- Análisis de sentimiento
- Extracción de entidades
- Chatbots y generación de texto

---

## 📂 Estructura sugerida del repositorio
📦 NLP_TESTING

┣ 📜 README.md

┣ 📓 nlp_introduction.ipynb
<<<<<<< HEAD

=======
┣ 📓 nlp_introduction_part2.ipynb
┣ texto_text.txt
>>>>>>> 1fa53bc (Nlp part 2)
┗ df_total.csv (ejemplo)

---

## 🧠 Próximos pasos
Se realizaran más publicaciones tocando temas desde intermedios hasta avanzados.

---

✍️ **Autor:** *César Álvarez*  
📅 **Año:** 2025  
📘 **Fuente de aprendizaje:** Apuntes personales sobre [Curso Completo de Procesamiento de Lenguaje Natural (NLP) con Python](https://youtu.be/9x1QtYNLJRY?si=lSJt37JcyXwNNBKk) del canal [Código Espinoza - IA y Machine Learning](https://www.youtube.com/@codigoespinozaIA)
