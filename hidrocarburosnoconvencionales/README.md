# Hidrocarburos No Convencionales

Este proyecto está diseñado para analizar y predecir la producción de pozos de gas y petróleo no convencional. Utiliza técnicas avanzadas de Machine Learning y Big Data para optimizar los procesos y generar predicciones sobre la producción de hidrocarburos.

## Estructura del Proyecto

Este proyecto sigue la estructura recomendada por [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/) para proyectos de ciencia de datos. A continuación se describen los principales directorios y archivos del proyecto:

- `data/`: Carpeta para almacenar los datos crudos y procesados.
  - `raw/`: Datos crudos que se recopilan del origen.
  - `processed/`: Datos procesados listos para ser utilizados en el modelo.
- `notebooks/`: Carpeta para almacenar los notebooks de Jupyter usados en el análisis exploratorio y pruebas.
- `src/`: Carpeta para el código fuente del proyecto.
  - `data/`: Código relacionado con la obtención y procesamiento de datos.
  - `features/`: Código para la creación de características.
  - `models/`: Código para la construcción y evaluación de modelos de Machine Learning.
  - `visualization/`: Código para la visualización de resultados.
- `requirements.txt`: Archivo con las dependencias del proyecto.
- `README.md`: Este archivo con la documentación general del proyecto.

## Requisitos

Para instalar las dependencias del proyecto, asegúrate de tener `pip` instalado y luego ejecuta el siguiente comando:

```bash
pip install -r requirements.txt

## Contribuciones
Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (git checkout -b feature/nueva-caracteristica).
3. Realiza los cambios y haz commit (git commit -am 'Agregada nueva característica').
4. Haz push a tu rama (git push origin feature/nueva-caracteristica).
5. Crea un pull request.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT - consulta el archivo LICENSE para más detalles.