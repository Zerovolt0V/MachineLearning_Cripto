# MachineLearning_Cripto

## Descripción
Proyecto de detección de fraude en transacciones con tarjetas de crédito usando técnicas de Machine Learning.

## Flujo de Trabajo

### 1. Análisis Exploratorio de Datos (EDA)
- [ ] Estadísticas descriptivas y visualización de variables
- [ ] Identificación y tratamiento de valores atípicos y faltantes
- [ ] Análisis de la variable objetivo (`Fraud`) y balance de clases

### 2. Preprocesamiento
------
- [x] Selección de características relevantes
- [x] Codificación de variables categóricas (one-hot, label encoding)
- [x] Normalización de variables numéricas (MinMaxScaler, StandardScaler)
- [x] División del dataset: entrenamiento, validación y prueba (70-15-15)
- [x] Manejo del desbalance de clases (sobremuestreo, submuestreo, pesos de clase)

### 3. Modelado
- [ ] Implementación de Naive Bayes Gaussiano
- [ ] Diseño y entrenamiento de un Perceptrón Multicapa (MLP) con al menos una capa oculta
- [ ] Ajuste de hiperparámetros para ambos modelos. Learning rate

### 4. Evaluación
- [ ] Evaluación en el conjunto de prueba
- [ ] Métricas: Accuracy, Recall, Precisión, F1-score (para la clase `Fraude`), Matriz de Confusión
- [ ] Curvas ROC para comparar modelos

### 5. Análisis y Conclusiones
- [ ] Comparación de modelos según métricas y curva ROC
- [ ] Análisis de fortalezas y debilidades de cada enfoque
- [ ] Identificación de características más importantes (según el MLP)
- [ ] Recomendaciones para mejorar el sistema de detección de fraude

## Recursos
- Dataset: `data/credit_card_transactions.csv`
- Bibliotecas recomendadas: `pandas`, `scikit-learn`, `matplotlib`, `seaborn`

---

**Nota:** Mantener una documentación clara de las decisiones tomadas en cada etapa.



## PReguntas DS

La hora del dia se relaciona con el incremento o decremento de transacciones fraudulentas?


Hay categorias del comercio donde el fraude sea mas frecuente?

El dispositivo utlizado para la transaccion impacta en la probabilidad de fraude?

La velocidad de transaccion se encuentra asociada a la existencia de un fraude?


Pro:

Hay franjas horarias (ajustada por ubicacion), relacionadas con un incremento o decremento de fraude. (enriquecimiento)

La direccion ip de alguna forma puede darnos informacion?
    - Patron que sugiera enmascaramiento, o un numero de dispositivos conectados a la misma red

Watafa:

Existen nombres de comercio que sugieran la precencia de un fraude






# primero Naive Bayes.

Luego GAN https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/