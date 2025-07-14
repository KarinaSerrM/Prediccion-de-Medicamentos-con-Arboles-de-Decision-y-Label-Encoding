# Predicción de Medicamentos con Árboles de Decisión y Label Encoding

Este repositorio contiene un proyecto de ciencia de datos enfocado en predecir el tipo de medicamento que debe recomendarse a un paciente, utilizando técnicas de clasificación supervisada con árboles de decisión.

## Objetivos del proyecto

- Cargar y preparar el conjunto de datos `drugs.csv`.
- Convertir variables categóricas en valores numéricos con `LabelEncoder()`.
- Entrenar modelos de Árboles de Decisión usando criterios Gini y Entropía.
- Evaluar el rendimiento del modelo a través de métricas y reportes de clasificación.
- Aplicar reglas del modelo para realizar predicciones en nuevos casos.

## Estructura del análisis

1. **Carga de datos:** Importación del archivo `drugs.csv` y verificación del contenido.
2. **Preprocesamiento:**  
   - Codificación de variables cualitativas (`Sex`, `BP`, `Cholesterol`).  
   - Separación entre variables predictoras y variable objetivo.  
   - Normalización de datos.

3. **Modelado con Árboles de Decisión:**  
   - Implementación de modelos con criterios Gini y Entropía.  
   - Comparación entre profundidades (3 y 5).  
   - Generación de reportes de clasificación detallados.

4. **Evaluación y visualización:**  
   - Matriz de confusión.  
   - Reglas del árbol interpretadas verbalmente.  
   - Determinación del modelo óptimo según métricas.  

5. **Predicción práctica:**  
   - Aplicación del modelo para recomendar medicamentos basados en características del paciente.

## Herramientas utilizadas

- Python 3.x  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

## Conclusiones

- Ambos criterios (Gini y Entropía) presentan resultados competitivos, pero el rendimiento óptimo depende de la profundidad del árbol.
- La codificación correcta de variables cualitativas mejora la precisión del modelo.
- El árbol seleccionado permite interpretar decisiones clínicas de forma clara y aplicable.

## Recomendación

Este proyecto es ideal para comenzar con modelos de clasificación en machine learning aplicados a salud y farmacia. Puede expandirse usando otros clasificadores como Random Forest o con técnicas como validación cruzada para mayor robustez.
