![Banner](docs/images/JS_banner.png)
![HidrocarburosArg](docs/images/hidrocarburosarggrey.png)

# Análisis de Producción de Pozos de Gas y Petróleo No Convencional
Este proyecto explora y analiza la **producción de gas y petróleo en pozos no convencionales de Argentina**, basándose en datos proporcionados por la [Secretaría de Gobierno de Energía](http://datos.energia.gob.ar/dataset/produccion-de-petroleo-y-gas-por-pozo). Estos datos ofrecen un detallado registro mensual de producción, incluyendo petróleo (en m³), gas (en miles de m³), y agua (en m³), entre otras variables relevantes.

## 🎯 Objetivo del Proyecto
El objetivo principal es aplicar técnicas avanzadas de Machine Learning y análisis de datos para entender mejor los patrones de producción y desarrollar herramientas predictivas que contribuyan a la toma de decisiones en la industria de hidrocarburos.

## ❓ Preguntas Clave a Resolver
* ¿Qué factores impactan más en la producción de gas y petróleo no convencional?
* ¿Es posible predecir la producción futura de un pozo basado en su historial y características?
* ¿Se pueden identificar pozos con alto potencial de producción utilizando modelos de clasificación?
* ¿Qué insights podemos obtener sobre la evolución temporal de los recursos y su relación con factores geográficos y técnicos?
* ¿Cuáles son los pozos más productivos? ¿Qué tienen en común?
* ¿Qué relación existe entre la producción y las variables de inyección (`iny_agua`, `iny_gas`, `iny_co2`)?
* ¿Cómo varía la producción según la geografía (provincia, cuenca)?
* ¿Existen outliers en las variables de producción?


## 📊 Alcances del Análisis
Este análisis se enfoca en:

* **Regresión:** Predecir la cantidad de petróleo, gas o agua producida en un periodo específico.
* **Clasificación:** Identificar y categorizar pozos según su rendimiento o características específicas.
* **Segmentación:** Agrupar pozos basados en patrones comunes, como rendimiento o ubicación geográfica.
* **Visualización de Datos:** Crear gráficos avanzados para comprender tendencias y relaciones en los datos.

## 📁 Estructura de Datos
Los datos provienen de un CSV delimitado por comas codificado en UTF-8, actualizado por última vez el 23 de Mayo de 2024. Entre las características más relevantes del dataset se incluyen:

| Categoría              | Detalles                                                      |
|------------------------|--------------------------------------------------------------|
| Identificación del Pozo| Código único, sigla y nombre asignados.                      |
| Ubicación Geográfica   | Coordenadas (latitud y longitud), provincia, cuenca, etc.    |
| Producción Mensual     | Volúmenes de petróleo, gas, agua e inyecciones.              |
| Características Técnicas| Profundidad, tipo de reservorio, vida útil estimada, etc.   |
| Temporalidad           | Fechas de perforación, inicio y fin de producción.           |

## 🛠️ Enfoque Técnico
El análisis utiliza herramientas de ciencia de datos y Machine Learning para:

* Limpiar y explorar datos para detectar patrones o anomalías.
* Diseñar modelos de predicción y clasificación usando algoritmos como regresión lineal, árboles de decisión, redes neuronales y otros métodos avanzados.
* Evaluar la precisión y utilidad de los modelos mediante métricas estándar.
* Visualizar resultados para facilitar la interpretación por parte de stakeholders.


## 📂 Estructura del Proyecto

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

## 🛠️ Requisitos

Para instalar las dependencias del proyecto, asegúrate de tener `pip` instalado y luego ejecuta el siguiente comando:
* pip install -r requirements.txt
 
## 💡 Contribuir
Si deseas contribuir a este proyecto, por favor sigue estos pasos:

* Haz un fork del repositorio.
* Crea una nueva rama (git checkout -b feature/nueva-caracteristica).
* Realiza los cambios y haz commit (git commit -am 'Agregada nueva característica').
* Haz push a tu rama (git push origin feature/nueva-caracteristica).
* Crea un pull request.

## 📜 Licencia
Este proyecto está licenciado bajo la [Licencia MIT](./LICENSE).
