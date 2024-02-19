# Trabajo Práctico 2 - NLP

Este repositorio contiene los archivos necesario para correr el desarrollo del Trabajo Práctico 2 de la materia Procesamiento del Lenguaje Natural. 

## **Ejercicio 1 - RAG**
**Crear un chatbot experto en un tema a elección, usando la técnica RAG. Como fuentes de conocimiento se utilizarán al menos las siguientes fuentes:**

* **Documentos de texto**
*  **Datos numéricos en formato tabular (por ej., Dataframes, CSV, sqlite, etc.)**
*  **Base de datos de grafos (Online o local)**


**`El chatbot se especializa en historia de la Segunda Guerra Mundial`**

## **Ejercicio 2 - Agentes:**
**Realice una investigación respecto al estado del arte de las aplicaciones actuales de agentes inteligentes usando modelos LLM libres.**

**Plantee una problemática a solucionar con un sistema multiagente. Defina cada uno de los agentes involucrados en la tarea. Es importante destacar con ejemplos de conversación, la interacción entre los agentes.**

**Realice un esquema del sistema multiagente.**

**Opcional: Resolución con código de dicho escenario.**

## Archivos
- `nlp_tp2.py` : Código Python del ejercicio 1
- `NLP_TP2.ipynb` : Notebook con resolución del ejercicio 1
- `InformeNLP-TP2.pdf` : Informe del ejercicio 1 y resolución del ejercicio 2
- `Datos` : Carpeta con los archivos PDFs y los datos tabulares utilizados como fuentes de datos

## Indicaciones
Para correr el programa es necesario contar con las siguientes dependencias instaladas en el enotorno de trabajo:
- `wikipedia-api`
- `pdfminer.six`
- `gdown`
- `llama_index==0.10.0`
- `sentence-transformers`
- `pypdf`
- `langchain`
- `python-decouple`
- `langchain_community`
- `pydantic==1.10.8`
- `typing_extensions==4.4.0`
- `chromadb`
  
