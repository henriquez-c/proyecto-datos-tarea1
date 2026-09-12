# Diccionario de datos: ejemplo.csv

## Descripción general

Conjunto de 720 mediciones horarias simuladas de temperatura y humedad relativa de un sensor ambiental, correspondientes al período comprendido entre el 1 y el 30 de marzo de 2026.

## Columnas

| Columna | Tipo | Unidad | Descripción |
|---|---|---|---|
| fecha_hora | fecha y hora | - | Fecha y hora de la medición, en formato AAAA-MM-DD HH:MM:SS, hora local |
| sensor_id | texto | - | Identificador del sensor |
| temperatura_c | decimal | grados Celsius | Temperatura simulada del aire |
| humedad_pct | decimal | % | Humedad relativa simulada |

## Valores faltantes

Los valores faltantes se representan como celdas vacías. En la columna `humedad_pct` se simuló aproximadamente un 2 % de valores faltantes.

## Procedencia

Datos generados sintéticamente mediante el programa `src/generar_datos.py`, utilizando una semilla fija con valor 2026.