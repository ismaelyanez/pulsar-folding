# Proyecto C: Curva de luz de un púlsar
Este proyecto trata sobre la curva de luz de un púlsar, que es una estrella que emite un pulso de luz que se repite cada cierto tiempo. Los datos tienen 1000 periodos, con 1000 puntos cada uno, pero tienen tanto ruido que el pulso no se ve a simple vista.
Para poder verlo se hizo un plegado (folding): se ponen todos los periodos uno encima de otro y se saca el promedio, con lo que el ruido baja y el pulso aparece. Después, al perfil promedio se le ajustó una curva gaussiana y se hicieron los gráficos.
## Archivos
- `pulsar_folding.ipynb`: notebook con todo el análisis (se puede abrir en Google Colab).
- `pulsar_resultados.png` `pulsar_pulsos_ruido.png`: gráficos usados en el informe.
- `requirements.txt`: librerías que se usaron (numpy, scipy, matplotlib y pandas).
## Datos
El archivo `datos_C_curvaluz_pulsar.csv` es el entregado por el profesor para el proyecto.
No se incluye en este repositorio porque pesa más de 25 MB.

## Cómo ejecutarlo
1. Abrir `pulsar_folding.ipynb` en Google Colab.
2. Subir `datos_C_curvaluz_pulsar.csv`.
3. Ejecutar todas las celdas (Entorno de ejecución -> Ejecutar todo).
