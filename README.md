# RESUMEN
Resumen de proyectos

1) Customer_support_data

https://www.kaggle.com/datasets/ddosad/ecommerce-customer-service-satisfaction

GITHUB

https://github.com/DavidGN2016GFS/ecommerce-consumer-behavior/releases/tag/v1.0.0
Description: Se evaluaron tres modelos de clasificación —SVM, Random Forest y Redes Neuronales (ANN)— para predecir la insatisfacción del cliente a partir de variables estructuradas y comentarios de texto. Los resultados muestran que no existe un modelo óptimo, pero cada uno destaca en distintos aspectos: Random Forest obtiene el mayor recall general, mientras que SVM y ANN logran un mejor equilibrio entre precisión y recall para la clase minoritaria (clientes insatisfechos). El análisis de texto reveló que la mayoría de comentarios son neutros y que existen grandes desbalances de clase, lo que afecta el rendimiento de los modelos. Se identificó que términos positivos como “good” y “nice” dominan en comentarios satisfactorios, mientras que palabras como “not”, “issue” y “pathetic service” caracterizan los negativos. Para mejorar el desempeño, se recomienda ajustar hiperparámetros, reforzar técnicas de balanceo y ampliar el conjunto de datos para capturar mejor los patrones de insatisfacción.

2)Pakistan's Largest E-Commerce Dataset

https://www.kaggle.com/datasets/zusmani/pakistans-largest-ecommerce-dataset

GITHUB

https://github.com/DavidGN2016GFS/pakistan-ecommerce-dataset/releases/tag/v1.0.0
Descripción: Se analizó un conjunto de datos de ventas minoristas que incluía información sobre clientes, productos, métodos de envío y satisfacción. Se realizaron estadísticas descriptivas, correlaciones, series temporales, análisis de texto y varios modelos de clasificación para predecir la insatisfacción del cliente. Las ventas muestran variaciones claras por mes y categoría, aunque ninguna variable numérica correlaciona fuertemente con la insatisfacción. Los comentarios negativos contienen palabras asociadas a problemas de servicio, mientras que los positivos muestran términos de buena experiencia. Los modelos SVM, Random Forest y Red Neuronal tuvieron desempeños débiles debido al fuerte desbalance de clases y a la falta de patrones claros en los datos; aun así, el Random Forest obtuvo el mejor recall general. Se recomienda mejorar el balanceo, ajustar hiperparámetros e incrementar los datos para lograr predicciones más confiables.
3)Google Analytics EDA + LightGBM + Screenshots



https://www.kaggle.com/code/erikbruin/google-analytics-eda-lightgbm-screenshots/input 

GITHUB

https://github.com/DavidGN2016GFS/fitness-tracker-analysis
Descripción:El análisis comparó dos modelos de regresión (SVR y Random Forest) para predecir el ancho del producto usando sus dimensiones físicas y precio.
Random Forest obtuvo el mejor rendimiento, con R² = 0.91 y MAE ≈ 1 cm, superando al SVR. Su capacidad para capturar relaciones no lineales lo hizo más efectivo.
Las variables más correlacionadas con el ancho fueron: largo, peso, alto y precio, lo que es coherente con la lógica del producto.
La validación cruzada confirmó la estabilidad del Random Forest (R² promedio ≈ 0.895).
Se recomienda optimizar hiperparámetros, generar nuevas características (como volumen), probar redes neuronales y usar interpretabilidad (SHAP) para mejorar el modelo.

4)Github: https://github.com/DavidGN2016GFS/ecommerce-order-analysis 
Kaggle: https://www.kaggle.com/datasets/bytadit/ecommerce-order-dataset
Se procesó y limpió el dataset, se generaron variables numéricas y de texto (TF-IDF) y se aplicó balanceo con SMOTE. Luego se entrenaron tres modelos de clasificación: Random Forest, SVM y Red Neuronal (MLP).
El mejor desempeño lo obtuvo Random Forest, con la mayor precisión y F1-score, por lo que se seleccionó como modelo final para predecir la probabilidad de compra.
Finalmente, se guardó el modelo y puede usarse para predecir nuevas observaciones con model.predict() después de aplicar el mismo preprocesamiento.
5) github
   https://github.com/DavidGN2016GFS/ecommerce-width-prediction/releases/tag/v1.0.0
   Kaggle
   https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store/data
Se limpió y procesó el dataset, se creó la variable objetivo is_purchase y se aplicó SMOTE para balancear las clases.
Luego se entrenaron tres modelos: Random Forest, SVM y MLP.
El Random Forest obtuvo el mejor rendimiento (Accuracy ≈ 0.96 y Recall ≈ 0.96), por lo que se seleccionó como modelo final.
Este modelo puede usarse directamente para predecir compras nuevas
 6) github: https://github.com/DavidGN2016GFS/ecommerce-purchase-prediction
   Kaggle: https://www.kaggle.com/datasets/bytadit/transactional-ecommerce?select=click_stream.csv
   El proyecto identificó patrones clave en las ventas del e-commerce UK Retail, logrando diferenciar con eficacia entre transacciones de alto y bajo valor mediante modelos de machine learning. Variables como TotalAmount, Customer_freq, Items_per_invoice y el mes de compra fueron las más influyentes.

Los modelos con mejor desempeño fueron Random Forest y la Red Neuronal (MLP), destacando por su precisión y estabilidad tras aplicar técnicas de balanceo como SMOTEENN y buen feature engineering.

Entre las principales mejoras se reconoce la necesidad de optimizar hiperparámetros (por GridSearch o métodos avanzados), incorporar nuevas variables y probar modelos más avanzados como XGBoost o AutoML.

Finalmente, los resultados permiten a la empresa identificar clientes con alta probabilidad de generar compras de alto valor, facilitando estrategias comerciales más eficientes y orientadas al retorno.
7)  kaggle :https://www.kaggle.com/datasets/kuldeeppatel08/ecommerce-uk-retailer.  github. https://github.com/DavidGN2016GFS/analisis_ventas_online_retail
Resumen de Conclusiones y Trabajo Futuro

El proyecto logró identificar patrones clave en los datos de ventas del e-commerce UK Retail, permitiendo diferenciar con efectividad entre transacciones de alto y bajo valor. Variables como TotalAmount, Customer_freq, Items_per_invoice y el mes de compra resultaron ser determinantes en el comportamiento de los clientes. Entre los modelos implementados, el Random Forest y la Red Neuronal MLP destacaron por su mayor precisión y estabilidad.

En cuanto al rendimiento de los modelos, las principales fortalezas fueron el uso de SMOTEENN para balancear las clases, la incorporación de variables derivadas para mejorar el poder predictivo y la validación cruzada aplicada al modelo MLP. No obstante, se identificaron debilidades como la alta demanda computacional del SVM RBF, la sensibilidad al ruido de datos de clientes con pocas transacciones y la falta de una optimización más exhaustiva para la red neuronal.

Para mejorar el proyecto, se propone añadir nuevas variables temporales y demográficas, aplicar métodos avanzados de optimización de hiperparámetros, probar modelos más potentes como XGBoost o LightGBM, y considerar el uso de herramientas AutoML.

Los resultados obtenidos son relevantes para el problema planteado, ya que permiten orientar estrategias de marketing y fidelización hacia clientes con mayor probabilidad de generar transacciones de alto valor. Esto convierte a los modelos desarrollados en herramientas útiles para la toma de decisiones comerciales y la optimización de campañas.
8)  https://datosabiertos.mef.gob.pe/dataset/comparacion-de-presupuesto-ejecucion-gasto
   GitHub?  https://github.com/DavidGN2016GFS/comparativo-gastos-peru-2012-2025
