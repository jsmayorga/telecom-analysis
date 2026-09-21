# Análisis de Comportamiento de Clientes — ConnectaTel

## Objetivo
Evaluar el comportamiento de los clientes de ConnectaTel, empresa de telecomunicaciones 
en Latinoamérica, mediante limpieza de datos, análisis exploratorio y segmentación de 
clientes por edad y nivel de uso, para identificar oportunidades comerciales.

## Datasets utilizados
- `plans.csv`: información de los planes (precio, minutos y GB incluidos, costo por extra).
- `users_latam.csv`: datos demográficos y de registro de los usuarios.
- `usage.csv`: registro detallado de llamadas y mensajes por usuario.

## Etapas del análisis
1. Carga y exploración inicial de los datasets.
2. Identificación de problemas de calidad de datos (nulos, sentinels, fechas inválidas).
3. Limpieza básica de datos.
4. Cálculo de estadísticas de uso agregadas por usuario.
5. Visualización de distribuciones y detección de outliers.
6. Segmentación de clientes por nivel de uso y por edad.
7. Insight ejecutivo con recomendaciones de negocio.

## Cómo ejecutar
1. Abre el notebook `S7_Version-Estudiante-Project-ConnectaTel.ipynb` en Google Colab 
   o Jupyter Notebook.
2. Asegúrate de tener instaladas las librerías: `pandas`, `seaborn`, `matplotlib`, `numpy`.
3. Coloca los archivos `plans.csv`, `users_latam.csv` y `usage.csv` en la carpeta `/datasets/`.
4. Ejecuta las celdas en orden de arriba hacia abajo.

## Autor
Johan Sebastian Mayorga
