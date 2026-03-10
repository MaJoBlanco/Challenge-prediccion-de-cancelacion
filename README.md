# Challenge-prediccion-de-cancelacion

## Descripción
Segunda parte del challenge de ciencia de datos de Telecom X. Se desarrollaron modelos 
de Machine Learning para predecir qué clientes tienen mayor probabilidad de cancelar 
el servicio.

---

## ecnologías
- Python 3.x, Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, Imbalanced-learn (SMOTE)

---

## Pipeline
1. **Preprocesamiento** — One-Hot Encoding, limpieza de NaN
2. **Balanceo** — SMOTE aplicado solo sobre el set de entrenamiento
3. **Modelos** — Regresión Logística (con escalado) y Random Forest (sin escalado)
4. **Evaluación** — Accuracy, F1, AUC-ROC, matriz de confusión

---

## Resultados

| Modelo | Accuracy | AUC-ROC |
|---|---|---|
| Regresión Logística | 0.8140 | 0.8991 |
| Random Forest | 0.8226 | 0.8983 |

---

## Factores Clave de Evasión
- **Cheque electrónico** — mayor predictor de riesgo
- **Contrato mes a mes** — sin compromiso a largo plazo
- **Baja antigüedad** — clientes nuevos se van más
- **Si
