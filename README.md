# Proyecto C: Curva de luz de un púlsar

Análisis de la curva de luz de un púlsar (1000 periodos de 1000 puntos cada uno).
Se hace el folding (plegado) de los datos con NumPy, se ajusta una gaussiana al perfil
promedio con SciPy y se grafican los resultados.

## Archivos
- `pulsar_folding.ipynb`: notebook con todo el análisis (se puede abrir en Google Colab).
- `figuras/`: gráficos usados en el informe.
- `requirements.txt`: librerías necesarias.

## Datos
El archivo `datos_C_curvaluz_pulsar.csv` es el entregado por el profesor para el proyecto.
No se incluye en este repositorio porque pesa más de 25 MB. Para ejecutar el notebook,
se debe dejar ese archivo en la misma carpeta (en Colab, subirlo desde el ícono de la carpeta).

## Cómo ejecutarlo
1. Abrir `pulsar_folding.ipynb` en Google Colab.
2. Subir `datos_C_curvaluz_pulsar.csv`.
3. Ejecutar todas las celdas (Entorno de ejecución -> Ejecutar todo).
