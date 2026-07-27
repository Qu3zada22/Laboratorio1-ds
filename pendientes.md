# Pendientes — Laboratorio 1: Series de Tiempo

Categorías seleccionadas: **Fronteras (top 3)** y **Países de residencia (top 3)**.

## Completado

- Punto 1. Análisis exploratorio completo.
- Punto 2. División entrenamiento/prueba (70/30).
- Punto 3. Construcción de series mensuales: total, 3 fronteras, 3 países.
- Punto 4 (a-k) — Total mensual de viajeros.
- Punto 4 (a-k) — Fronteras: 01 La Aurora, 07 Valle Nuevo, 09 San Cristóbal.

## Completado y verificado

### Punto 4 (a-k) — Países de residencia (top 3)

Se analizaron El Salvador, Guatemala y Estados Unidos de América, seleccionados por acumulado en todo el período:

- [x] a. Inicio, fin y frecuencia de la serie.
- [x] b. Gráfico de la serie e interpretación a primera vista.
- [x] c. Descomposición (tendencia/estacionalidad/residuo) y discusión de estacionariedad en media y varianza.
- [x] d. Decisión sobre transformación (`log1p`) con justificación y soporte para ceros.
- [x] e. ACF + prueba de Dickey-Fuller Aumentada; diferenciaciones necesarias.
- [x] f. Elección de p, d, q con ACF/PACF y `auto_arima`.
- [x] g. Comparación de modelos ARIMA con residuos, AIC/BIC y Ljung-Box.
- [x] h. Modelos con Prophet, Holt-Winters, suavizamiento exponencial y seasonal naive.
- [x] i. Predicción del mejor modelo sobre el conjunto de prueba.
- [x] j. Comparación con MAE, RMSE, AIC y BIC donde corresponden.
- [x] k. Selección: Prophet (El Salvador), Holt-Winters (Guatemala, no válido operativamente después de 2022 por falta de cobertura) y ARIMA (Estados Unidos de América).

### Punto 5. Análisis comparativo

**a. Para cada categoría seleccionada (Fronteras y Países), con evidencia estadística:**

- [x] i. Mayor estacionalidad cuantificada con fuerza estacional.
- [x] ii. Mayor tendencia de crecimiento cuantificada con pendiente relativa prepandemia.
- [x] iii. Mayor volatilidad cuantificada con residuo relativo a la media.
- [x] iv. Mayor impacto pandémico cuantificado con la caída de 2020 frente a 2019.

**b. En general:**

- [x] i. Descubrimientos y limitaciones de cobertura útiles para la toma de decisiones.

### Entrega final

- [x] Informe generado en `informe.pdf` sin mostrar celdas de código.
- [x] `lab1.ipynb` ejecutado completamente con `uv`, sin celdas con error ni celdas pendientes.
- [x] Repositorio remoto verificado: `git@github.com:Qu3zada22/Laboratorio1-ds.git` (`main`).

### Observación metodológica

Guatemala deja de aparecer en la variable `País` desde 2023. Los ceros posteriores representan falta de cobertura y no una caída real de viajeros; por ello, sus métricas de prueba y el modelo ganador deben interpretarse con cautela.

## Fecha límite

**26 de julio de 2026, 23:59** — documento completo + archivos de código.
