# Clasificador-de-Codigo-Python-con-IA
Sistema basado en Inteligencia Artificial para la detección y clasificación de código seguro y malicioso en Python. Implementa tres enfoques de modelado (Binario, Multiclase e Híbrido) para analizar código fuente y categorizar posibles amenazas de seguridad.

## Arquitectura del Proyecto

El sistema aborda la clasificación de código a través de tres aproximaciones:

* **Modelo Binario:** Clasificación fundamental entre código totalmente seguro y código malicioso.
* **Modelo Multiclase:** Identificación y categorización del tipo específico de amenaza o vulnerabilidad en el código.
* **Modelo Híbrido:** Combinación de técnicas (o modelos) para maximizar la precisión y reducir los falsos positivos en el análisis.

## Requisitos Previos (Prerequisites)

Para ejecutar los notebooks de este proyecto, necesitarás contar con las siguientes cuentas y configuraciones:

1. **Cuenta de Google (Google Colab):**
   * Los modelos están desarrollados en formato `.ipynb` optimizados para correr en [Google Colab](https://colab.research.google.com/). 
   * Se recomienda activar el entorno de ejecución con **T4 GPU** (o superior) en Colab para acelerar el entrenamiento y la inferencia de los modelos.

2. **Cuenta de Hugging Face:**
   * Es necesaria para descargar los tokenizadores, modelos base de lenguaje (como CodeBERT, StarCoder, etc., si los usas) o datasets.
   * **Token de Acceso (HF Token):** Deberás generar un *Access Token* (con permisos de lectura/Write según corresponda) desde tu perfil de Hugging Face e ingresarlo en el notebook cuando se te solicite (`notebook_login()`).
