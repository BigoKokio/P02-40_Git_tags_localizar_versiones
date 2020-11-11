# P02-40_Git_tags_localizar_versiones
Creo un tag en carpetaCasa desde el apartado "Log" de la sección "Git" de IntelliJ con el nombre "Primer_tag".
Hago dos "commit and push", ambos comentarios, uno con el contenido "Primer comentario después de primer tag" y otro con el contenido "Segundo comentario".
Desde el apartado "Log" de la sección "Git" hago clic derecho en el commit al que quiero volver y selecciono "Reset current branch to here" (checkout). 
A continuación, me pregunta qué tipo de checkout quiero hacer. Marco "Hard" y el fichero vuelve al commit seleccionado. 
Añado otro comentario con el contenido "Tercer comentario después del checkout" y hago "commit and push". 
Al hacer esto, me salta el error del ejercicio anterior (P02-30), en donde escojo la opción de unir ambas ramas. 
Con esto, hago un pull (update project) en carpetaInstituto para tener los commit de carpetaCasa, y hago un checkout al mismo commit de carpetaCasa.
