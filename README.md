# MLS Labs

Prácticas y laboratorios del módulo **Sistemas de Aprendizaje Automático** (curso de IA y Big Data).

## Prácticas

| # | Práctica | Contenido |
|---|---|---|
| 01 | [Regresión: consumo eléctrico de viviendas](practicas/01-regresion-consumo) | Predicción de `consumo_mensual_kwh` con 4 modelos de scikit-learn y evaluación por MAE |

Cada práctica tiene su carpeta con el enunciado, los datos, el notebook y la presentación (memoria):

```text
practicas/NN-nombre/
├── enunciado.pdf
├── dataset.csv
├── notebook.ipynb
├── presentacion.html   # memoria; se exporta a PDF con Imprimir → Guardar como PDF
└── img/                # capturas de Google Colab
```

## Ejecución

### Local

Requisitos: Python 3.11 o superior.

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

JupyterLab: http://localhost:8888

### Google Colab

1. Archivo → Subir cuaderno → el `.ipynb` de la práctica.
2. Entorno de ejecución → Ejecutar todas.
3. Subir el dataset cuando lo pida la celda de carga.
