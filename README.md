Título del Proyecto: Análisis y Predicción de Ventas en una Tienda de Retail

  Descripción:
  Este proyecto analiza un dataset de 302,010 transacciones de retail para identificar patrones de comportamiento de compra y desarrollar modelos predictivos
   de machine learning. El análisis incluye exploración de datos, imputación de valores nulos, identificación de outliers, análisis de correlaciones y
  benchmarking de 6 algoritmos de ML (Logistic Regression, KNN, Decision Tree, Random Forest, XGBoost y LightGBM). La importancia radica en proporcionar
  insights accionables para optimizar inventario, mejorar la experiencia del cliente, personalizar estrategias de marketing y tomar decisiones basadas en
  datos para maximizar las ventas y la satisfacción del cliente.

  Estructura del Repositorio:

  proyecto1/
  ├── retail_data.csv                      # Dataset original con 302,010 transacciones
  ├── retail_analysis_colab.ipynb          # Notebook principal para Google Colab con análisis completo
  ├── retail_eda_analysis.ipynb            # Notebook de análisis exploratorio detallado
  ├── crear_ppt_simple.py                  # Script Python para generar presentación PowerPoint
  ├── crear_presentacion_retail_colab.py   # Versión del script adaptada para Google Colab
  ├── Analisis_Retail_Presentacion.pptx   # Presentación de resultados del proyecto
  └── README.md                            # Documentación del proyecto

  Instrucciones para Ejecutar:

  1. En Google Colab:
    - Abrir https://colab.research.google.com/
    - Subir el archivo retail_analysis_colab.ipynb
    - Ejecutar !pip install xgboost lightgbm python-pptx
    - Subir retail_data.csv cuando lo solicite
    - Ejecutar todas las celdas secuencialmente
  2. En entorno local:
    - Instalar dependencias: pip install pandas numpy matplotlib seaborn scikit-learn xgboost lightgbm python-pptx
    - Abrir Jupyter Notebook: jupyter notebook
    - Ejecutar retail_analysis_colab.ipynb
  3. Para generar presentación:
    - Ejecutar: python crear_ppt_simple.py

  Autores:

  - Carolina Melero Rojas - Rol: Analista de Datos y Desarrolladora ML Principal

  Licencia:

  Este proyecto está bajo la Licencia MIT. Esto significa que es software de código abierto y puede ser utilizado, copiado, modificado y distribuido
  libremente, siempre que se incluya el aviso de copyright original y la licencia en todas las copias del software.

