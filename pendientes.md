# Pendientes — Laboratorio 1: Series de Tiempo

Categorías seleccionadas: **Fronteras (top 3)** y **Países de residencia (top 3)**.

## Completado

- Punto 1. Análisis exploratorio completo.
- Punto 2. División entrenamiento/prueba (70/30).
- Punto 3. Construcción de series mensuales: total, 3 fronteras, 3 países.
- Punto 4 (a-k) — Total mensual de viajeros.
- Punto 4 (a-k) — Fronteras: 01 La Aurora, 07 Valle Nuevo, 09 San Cristóbal.

## Falta por hacer

### Punto 4 (a-k) — Países de residencia (top 3)

Para cada uno de los 3 países (Guatemala, El Salvador, Estados Unidos), reutilizando `analizar_serie` y `modelar_serie` (construyendo antes `series_pais_test` igual que se hizo con fronteras):

- [ ] a. Inicio, fin y frecuencia de la serie.
- [ ] b. Gráfico de la serie e interpretación a primera vista.
- [ ] c. Descomposición (tendencia/estacionalidad/residuo) y discusión de estacionariedad en media y varianza.
- [ ] d. Decisión sobre transformación (log u otra) con su justificación.
- [ ] e. ACF + prueba de Dickey-Fuller Aumentada; diferenciaciones necesarias.
- [ ] f. Elección de p, d, q (ACF/PACF y/o `auto_arima`), explicando si el modelo automático tiene sentido.
- [ ] g. Comparación de varios modelos ARIMA (residuos, AIC/BIC) y selección del mejor.
- [ ] h. Modelos con Prophet, Holt-Winters, suavizamiento exponencial y seasonal naive.
- [ ] i. Predicción del mejor modelo sobre el conjunto de prueba.
- [ ] j. Comparación de todos los modelos con MAE, RMSE, AIC y BIC.
- [ ] k. Selección del mejor modelo para cada país.

### Punto 5. Análisis comparativo

**a. Para cada categoría seleccionada (Fronteras y Países), con evidencia estadística:**

- [ ] i. ¿Cuál serie presenta mayor estacionalidad?
- [ ] ii. ¿Cuál presenta mayor tendencia de crecimiento?
- [ ] iii. ¿Cuál presenta mayor volatilidad?
- [ ] iv. ¿Cuál fue la más afectada por la pandemia?

**b. En general:**

- [ ] i. Descubrimientos del análisis que serían útiles para que INGUAT tome decisiones.

### Entrega final

- [ ] Armar el informe en **PDF** con los resultados y explicaciones (sin código, según instrucciones).
- [ ] Confirmar que el script/notebook final (.ipynb o .py) esté completo y sin errores.
- [ ] Verificar el link del repositorio de versionamiento esté actualizado.

## Fecha límite

**26 de julio de 2026, 23:59** — documento completo + archivos de código.
