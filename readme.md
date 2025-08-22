## 📊 Proyecto CDP II - Ciencia de Datos en Producción

Este proyecto corresponde al Entregable 2 (15%) del curso Ciencia de Datos en Producción, en el cual se realiza un proceso de ETL, análisis exploratorio de datos (EDA) y transformaciones sobre una base de datos de créditos de una entidad financiera.

El objetivo principal es analizar la información de los créditos, los usuarios y el comportamiento de pago (mora o cumplimiento), generando insights de valor para la organización y preparando los datos para etapas posteriores de modelado.

## 📂 Estructura del Proyecto  

```bash
PYTHON_ETL/
├── codigoproyecto-venv/            # Entorno virtual (puede excluirse del repo)
├── etl_scripts/
│   └── src/
│       ├── desarrollo/
│       │   ├── __pycache__/        # Archivos compilados de Python
│       │   └── transformacion_eda.ipynb  # Notebook con el EDA y transformaciones
│       └── config.json             # Configuración del proyecto
│
├── Base_de_datos.csv               # Datos del resultado del EDA
├── requirements.txt                # Dependencias del proyecto
├── .gitignore                      # Exclusiones para Git
├── readme.md                       # Documentación del proyecto (este archivo)
└── set_up.bat                      # Script de configuración inicial



