# **🕵️‍♂️ Proyecto: Detector de Anomalías con Python**

Este es un proyecto de ciencia de datos que se enfoca en la **detección de valores atípicos (anomalías)** utilizando técnicas de aprendizaje no supervisado. El código implementa el algoritmo **Isolation Forest** de la biblioteca scikit-learn para identificar puntos de datos inusuales que se desvían de la norma.

## **Propósito y Aplicación**

El objetivo principal de este proyecto es demostrar la capacidad de **identificar patrones inusuales** en grandes conjuntos de datos. En el contexto del marketing digital, esta técnica tiene un valor inmenso:

* **Detección de fraude:** Identificar clics o interacciones fraudulentas en campañas publicitarias.  
* **Análisis de rendimiento:** Detectar caídas o picos repentinos en métricas clave (tráfico, conversiones, etc.).  
* **Segmentación de clientes:** Encontrar clientes con un comportamiento de compra inusual que podría indicar una oportunidad o un problema.

## **Tecnologías y Librerías**

* **Python:** El lenguaje de programación principal.  
* **Pandas:** Usado para la manipulación y estructuración de los datos.  
* **NumPy:** Para operaciones numéricas de alto rendimiento.  
* **Matplotlib:** Para la visualización de datos, incluyendo gráficos 2D y 3D.  
* **scikit-learn:** La biblioteca clave que contiene el algoritmo **Isolation Forest** para la detección de anomalías.

## **Código y Estructura del Proyecto**

El repositorio contiene el siguiente archivo principal:

* **detector.py**: El script de Python que genera datos de ejemplo, entrena el modelo Isolation Forest y visualiza los resultados para mostrar la detección de anomalías.

El código está diseñado para ser claro y fácil de seguir, con comentarios que explican cada paso del proceso.

## **Resultados y Visualizaciones**

El proyecto genera dos gráficos principales:

* **Gráfico de Dispersión 2D**: Muestra la distribución de los datos originales, permitiendo una inspección visual de las anomalías.  
* **Gráfico de Detección**: Un gráfico de dispersión que usa diferentes colores y marcadores para diferenciar claramente los datos "normales" de las anomalías detectadas por el modelo.

El código también incluye una visualización en 3D para ilustrar cómo el modelo puede trabajar con datos más complejos.

## **Cómo ejecutar el proyecto**

Para ejecutar el código, necesitas tener Python y las librerías mencionadas instaladas. Puedes ejecutar el archivo detector.py desde tu terminal o un entorno de desarrollo.

python detector.py  
