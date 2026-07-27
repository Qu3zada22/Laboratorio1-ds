# Laboratorio 1: Series de Tiempo

Análisis de los ingresos mensuales de viajeros internacionales a Guatemala entre
enero de 2009 y junio de 2026.

## Ejecución

El proyecto usa [uv](https://docs.astral.sh/uv/) para administrar Python y sus
dependencias.

```bash
uv sync
uv run jupyter nbconvert --to notebook --execute --inplace lab1.ipynb \
  --ExecutePreprocessor.timeout=1800
```

## Informe

El PDF se genera desde el notebook ejecutado, ocultando las celdas de código:

```bash
uv run jupyter nbconvert --to html --no-input lab1.ipynb --output informe.html
uv run weasyprint informe.html informe.pdf
```

El entregable de análisis es `lab1.ipynb` y el informe sin código es
`informe.pdf`.
