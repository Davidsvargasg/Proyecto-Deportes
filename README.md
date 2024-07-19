# Futbol de naciones

En este proyecto hablamos sobre el futbol de selecciones nacionales en las principales competiciones internacionales y en sus respectivos continentes.

Tenemos hipóteis iniciales donde creemos que la selección nacional que más valor tiene es la que mejor ranking obtiene según la organización FIFA. Otra hipótesis es que el equipo que ocupa la primera posición es el que más encuentros ha ganado. La tercera es que Brasil es la selección con mejor porcentaje de partidos ganados 

Vamos a obtener datos a través de datasets existentes y de web scraping para analizarlos y confirmar o refutar nuestras hipótesis iniciales. 

Tenemos un dataframe con los enfrentamientos históricos de las seleciones nacionales de fútbol que contiene las columnas de selecón nacional que juega en casa, selección nacional que juega fuera de casa, otra con el resultado del enfrentamiento, dentro de que competición se ha jugado el partido, en que ciudad y país fue el enfrentamiento y si es en terreno neutral.
Añadimos una columna con la selección ganadora del encuentro o si fue empate.

Filtramos la tabla eliminando competiciones menos importantes y amistosos y acotando por fecha, desde la primera celebracion de la Copa América hasta la actualidad.

Por otro lado, mediante web scraping obtenemos la tabla del ranking FIFA de selecciones, su valor total del conjunto de jugadores, la media de edad de éstos, la confederación a la que pertenece y los puntos que la FIFA le otorga a cada selección.

Después de aplicar los filtros y limpieza de las tabalas, procedemos a calcular las estadísticas para determinar si nuestras hipótesis son ciertas

Llegamos a la conclusión que la selección nacional con mayor valor no ocupa la primera posición sino la cuarta. Argentina es el equipo que lidera la clasificación aunque no es el que mayor número de partidos ha ganado. Por último, obtenemos que brasil no es la selección con mayor número de partidos ganados sino que ese ranking lo lidera Alemania.

Los principales problemas que hemos tenido ha sido al hacer web scraping, ya que la web ha sido actualizada. Lo solucionamos guardando la tabla en un csv y accediendo desde el nuevo archivo.

Otro problema que tuvimos fue la búsqueda de APIs gratuitos y de calidad por lo que nos decantamos por utilizar un dataframe predefinido donde encontramos datos amplios y concisos acerca del tema que queríamos abordar.
