# Customer Segmentation

Este proyecto tiene como objetivo segmentar a los clientes de un sitio web de comercio electrónico en grupos distintos en base a su comportamiento y características. La segmentación permitirá a la empresa diseñar campañas de marketing más efectivas y mejorar la retención de clientes.

## Instalación

1. **Crear un entorno virtual:**

```bash
python3 -m venv env
source env/bin/activate
```

2. **Instalar dependencias:**

```bash
pip install -r requirements.txt
```

## Ejecución

1. **Análisis EDA:**

Abra el notebook `EDA.ipynb` y ejecute las celdas para realizar el análisis exploratorio de datos.

2. **Clustering:**

Abra el notebook `Clustering.ipynb` y ejecute las celdas para realizar el clustering de clientes.

3. **Informe de Segmentación:**

El informe detallado de la segmentación se encuentra en la carpeta `informe` en formato PDF y Markdown:

* `informe/informe.pdf`
* `informe/informe.md`

## Estructura del Proyecto

```
customer_segmentation/
├── README.md
├── data/
│   ├── datos_clientes.csv
├── informe/
│   ├── segmentacion.pdf
|   ├── segmentacion.md
├── N_EDA.ipynb
├── N_Clustering.ipynb
├── env/
└── requirements.txt
```

**Consideraciones:**

* El dataset `data_customers.csv` es la infromacion en raw mientras que `data_customers_pre.csv` es la infromacion limpia lista para el preprocesamiento.
* Los notebooks `EDA.ipynb` y `Clustering.ipynb` contienen el código para el análisis EDA y el clustering, respectivamente.
* El informe de segmentación en formato PDF y Markdown se genera en la carpeta `informe`.
