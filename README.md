# Clasificación - Calidad de Vinos
En primera instancia se descargaron los datos referentes para calificar la calidad de los
diferentes vinos, para luego integrar el archivo al proyecto. Una vez que el archivo se
cargó, se mostraron sus diferentes valores para tener una leve idea sobre lo que se debía
trabajar. Se crearon dos variables para estandarizar los valores seleccionados para la 
predicción, en este caso fueron elegidos: acido cítrico, sulfatos y alcohol. Estos valores
derivan en un solo resultado, la calidad del vino. Se creó el modelo clasificador
para evaluar estos. Dichos valores fueron seleccionados a partir de un mapa de calor
(heatmap) que resultó de gran ayuda para la tarea. Finalmente, se creó un mapa de dispersión
2D a fin de graficar la calidad de los vinos a partir del alcohol y los sulfatos.

## Valores de ejemplo utilizados y su respectivo resultado
Ácido cítrico | Sulfatos | Alcohol | Resultado
--- | --- | --- | ---
0.0 | 0.0 | 0.0 | 4
--- | --- | --- | ---
0.05 | 0.67 | 9.2 | 5
--- | --- | --- | ---
0.003 | 0.88 | 9.0 | 6
--- | --- | --- | ---
