Necesitamos construir el nombre completo de una persona, a partir de su nombre y su apellido. Parece sencillo, ¿no? El pequeño inconveniente es que el nombre completo se puede formar colocando su nombre, un espacio y su apellido, pero también se puede hacerlo al revés: el apellido, una coma, un espacio y su nombre. Por eso vamos a construir una función nombreCompleto, que tome un nombre, un apellido y un booleano que indique si debemos escribir primero el apellido o no: 

ム nombreCompleto("Feli", "Pérez", false)
"Dani Pérez"
ム nombreCompleto("Umi", "López", true) 
"López, Umi"
 
