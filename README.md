  # Muestreo en Redes Sociales
Repositorio de respaldo para el informe "Muestreo en redes sociales" presentado en el marco de la carrera de Sociología en la Universidad de Buenos Aires.

## MRS - construccion de red
Aquí se encuentra el prototipo de función utilizado para, con una lista inicial de usuarios (llamados "referentes"), traer el dato de sus seguidores. Además, se crean funciones ad-hoc para guardar esa información en tablas de un archivo tipo SQL, una extensión de base de datos para poder manejar grandes volúmenes. Si bien en este ejemplo nos manejamos con cantidades modestas, se prepara la función para poder ampliar. 

## MRS - análisis estructura y remuestreo
Aquí se encuentra la parte más extensa. A partir de la base creada con las funciones anteriores, se crea una estructura de grafo. Una vez obtenida la estructura, se crean funciones para realizar una descripción rápida de la topología del grafo, enumerando distintas métricas para describir la red. Luego, se preparan funciones de remuestreo, para simular extracciones de usuarios -similar a la primera notebook, utilizando referentes y sus seguidores-. Así, podemos analizar cómo varía la estructura de la muestra obtenida en función de los diferentes remuestreos realizados. Por último, se realiza un análisis escueto de los últimos tweets de los usuarios participantes para conocer un poco más el sector con el que estamos trabajando. 
