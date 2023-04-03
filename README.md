# hiperonimos


Este código abre un archivo llamado "datos.csv" y lo lee usando la función csv.DictReader. Luego, crea un nuevo archivo llamado "archivo_salida.csv" y escribe los datos en él. La nueva tabla tendrá solo dos columnas: "vocablo" y "hiperonimo".

El código busca filas que contengan la palabra "que" en la segunda posición de la columna "definición". Si una fila cumple con este criterio, la palabra a la izquierda de "que" se almacena en la variable "hiperonimo". Luego, se escribe una nueva fila en el archivo de salida que contiene el valor de "vocablo" de la fila original y el valor de "hiperonimo" que se encontró en la columna "definición". 

Para que exista una relación de hiperonimia hay que asegurarse de que el  archivo CSV contiene un "vocablo" asociado con la definición.
