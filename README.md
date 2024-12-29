# Random Forest Project

Este proyecto implementa un modelo de Random Forest para la clasificación de datos. El objetivo es proporcionar una herramienta eficiente y precisa para la toma de decisiones basada en datos.

## Descripción

El modelo de Random Forest es un conjunto de árboles de decisión que se utilizan para mejorar la precisión y reducir el sobreajuste. Este proyecto incluye:

- Preprocesamiento de datos
- Entrenamiento del modelo
- Evaluación del modelo
- Visualización de resultados

## Requisitos

### Instalación

1. Clona el repositorio:
    ```bash
    git clone https://github.com/Eduard088/Random_Forest_Tesis_ML.git
    ```

### instalar el entorno virtual:
```bash
conda env create -f environment.yml
```

### Replicar Utilizando Cookiecutter:

```bash
pip install cookiecutter
cookiecutter
```

o usando conda:

```bash
conda install -c conda-forge cookiecutter
```

por ejemplo:

```bash
cookiecutter https://github.com/Eduard088/Random_Forest_Tesis_ML
```

## Estructura de Carpetas

La estructura de carpetas del proyecto es la siguiente:

```
Random_Forest_Project/
├── {{cookiecutter.project_slug}}/
│   ├── data/               # Conjunto de Datos
│   ├── notebooks/          # Datos procesados
├── docs/                   # Renderizados en Quarto
├── environment.yml         # Archivo de configuración del entorno
├── README.md               # Documentación del proyecto
└── LICENSE                 # Licencia del proyecto
```

Esta estructura permite organizar el proyecto de manera clara y facilita la colaboración y el mantenimiento del código.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request para discutir cualquier cambio.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## Contacto

Para cualquier consulta, puedes contactarme en [eduardobareapoot@outlook.com](mailto:tu_email@example.com).
