En la carpeta data se encuentran datos de 19 imágenes con su respectivo conteo y 50 imágenes cuyo conteo se encuentra inconcluso. 
Los datos fueron truncados para acomodarse a las necesidades del modelo. Las imágenes se encuentran en formato .jpg y cuadradas. 
Los nombres se corresponden con el id identificado en el csv para data_19 y con el nombre escrito arriba de cada girasol en su respectiva imagen para data_50. 
Los nombres de las imágenes como archivo deben contener el id con el que se las identifica en los csv y estar en formato cuadrado, captando la totalidad de la torta.

En la carpeta análsis se identifican las inconsistencias que hay entre las carpetas de imágenes y archivos de conteo.

En la carpeta modelo se guardará el modelo luego de ser ejecutado.

En la carpeta resultados se verán los resultados arrojados por el modelo en comparación con los datos contados a mano proporcionados en los archivos csv.

El desarrollo del modelo se encuentra en el archivo count_total_seeds.ipynb.

El modelo utiliza el dataset de 19 imágenes con su conteo correspondiente para entrenar la red convolucional. El 'mae' ronda los 90. 
El modelo solo cuenta las semillas totales, aún no diferencia entre blancas, negras o marrones. Falta el dataset de conteo correspondiente a las 50 nuevas imágenes.
El código se entrena únicamente con set de training y test por la escasez de datos. 
Cuando se cuente con una mayor cantidad de datos, los datos deberían dividirse en training set, validation set, y test set.

