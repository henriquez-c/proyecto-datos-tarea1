# Mediciones horarias de temperatura y humedad de un sensor ambiental

Conjunto de datos simulados y programa mínimo de lectura, preparados como actividad del curso Tópicos Avanzados del Análisis de Datos del Doctorado en Ingeniería Aplicada. Este registro será actualizado al final del curso con los datos y el código del trabajo final.
Los archivos incluidos permiten reproducir la generación, lectura y resumen de los datos.

## Contenido

- `data/ejemplo.csv`: 720 mediciones horarias simuladas, correspondientes al período entre el 1 y el 30 de marzo de 2026.
- `data/diccionario_de_datos.md`: descripción de cada columna, sus unidades y los valores faltantes.
- `src/generar_datos.py`: programa que genera los datos simulados utilizando una semilla fija.
- `src/leer_datos.py`: programa que lee los datos, calcula un resumen diario y produce una figura.
- `resultados/`: contiene el resumen y la figura producidos por `leer_datos.py`.

## Procedencia de los datos

Los datos fueron generados sintéticamente mediante `src/generar_datos.py`, utilizando una semilla fija con valor 2026. Simulan mediciones horarias de temperatura y humedad relativa de un sensor ambiental durante 30 días.

## Cómo ejecutar

Requisitos: Python 3.9 o superior.

1. Descargar o clonar este repositorio.
2. Instalar las dependencias: `python -m pip install -r requirements.txt`
3. Desde la carpeta raíz del proyecto, ejecutar: `python src/leer_datos.py`

El programa muestra un resumen en pantalla y guarda los archivos `resultados/resumen.csv` y `resultados/figura_1.png`.

## Licencia

- Código (`src/`): licencia MIT (ver archivo `LICENSE`).
- Datos y documentación (`data/` y este archivo): Creative Commons Atribución 4.0 Internacional (CC BY 4.0), https://creativecommons.org/licenses/by/4.0/

## Cómo citar

Henríquez-Manríquez, C. (2026). Mediciones horarias de temperatura y humedad de un sensor ambiental (datos de ejemplo) (Versión 1.0.0) [Conjunto de datos]. Zenodo. https://doi.org/10.5281/zenodo.XXXXXXX

El DOI se completará después de publicar en Zenodo.

## Contacto

Cristian Henríquez-Manríquez, c.henriquezma@udd.cl, ORCID: https://orcid.org/0000-0002-8411-9548