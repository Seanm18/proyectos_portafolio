# Predictor de Precios de Casas

Modelo de Machine Learning que predice el precio de una vivienda en California a partir de características del vecindario, usando Random Forest.

## Resultados

- **Precisión (R²):** 80.5%
- **Error promedio:** $32,754

## Tecnologías

- Python
- pandas / numpy
- matplotlib
- scikit-learn (RandomForestRegressor)

## Dataset

California Housing Dataset (incluido en scikit-learn) — 20,640 viviendas con variables como ingreso del vecindario, antigüedad, número de cuartos, población y ubicación geográfica.

## Proceso

1. **Exploración de datos** — análisis estadístico y visualización de relaciones entre variables.
2. **Visualización** — gráficas de dispersión para identificar correlaciones (el ingreso del vecindario es el factor con mayor relación con el precio).
3. **Entrenamiento** — modelo Random Forest con 100 árboles, dividiendo los datos en 80% entrenamiento / 20% prueba.
4. **Evaluación** — métricas de error absoluto medio (MAE) y R².
5. **Predicción** — el modelo estima el precio de una vivienda nueva a partir de sus características.

## próximos pasos

- Probar con datos reales de Utah (Wasatch Front)
- Agregar interfaz interactiva con Streamlit
- Comparar con otros modelos (XGBoost, regresión lineal)

---
*Proyecto desarrollado como parte de mi preparación para trabajar en ML/Data en EE.UU.*
