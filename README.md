# MachineLearning_Cripto

## Descripción
Proyecto de detección de fraude en transacciones con tarjetas de crédito usando técnicas de Machine Learning.

## Flujo de Trabajo

### 1. Análisis Exploratorio de Datos (EDA)
- [ ] Estadísticas descriptivas y visualización de variables
- [ ] Identificación y tratamiento de valores atípicos y faltantes
- [ ] Análisis de la variable objetivo (`Fraud`) y balance de clases

### 2. Preprocesamiento
- [ ] Selección de características relevantes
- [ ] Codificación de variables categóricas (one-hot, label encoding)
- [ ] Normalización de variables numéricas (MinMaxScaler, StandardScaler)
- [ ] División del dataset: entrenamiento, validación y prueba (70-15-15)
- [ ] Manejo del desbalance de clases (sobremuestreo, submuestreo, pesos de clase)

### 3. Modelado
- [ ] Implementación de Naive Bayes Gaussiano
- [ ] Diseño y entrenamiento de un Perceptrón Multicapa (MLP) con al menos una capa oculta
- [ ] Ajuste de hiperparámetros para ambos modelos

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