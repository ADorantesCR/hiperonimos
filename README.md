# hiperonimos


Este código abre un archivo llamado "datos.csv" y lo lee usando la función csv.DictReader. Luego, crea un nuevo archivo llamado "archivo_salida.csv" y escribe los datos en él. La nueva tabla tendrá solo dos columnas: "vocablo" y "hiperonimo".

El código busca filas que contengan un pronombre relativo en la segunda posición de la columna "definición". Si una fila cumple con este criterio, la palabra a la izquierda del relativo se almacena en la variable "hiperonimo". Luego, se escribe una nueva fila en el archivo de salida que contiene el valor de "vocablo" de la fila original y el valor de "hiperonimo" que se encontró en la columna "definición". 

Para que exista una relación de hiperonimia hay que asegurarse de que el  archivo CSV contiene un "vocablo" asociado con la definición.

La relación de hiperonimia es una relación semántica que establece que un término (llamado hiperónimo o superorden) es más general que otro término (llamado hipónimo o suborden). En otras palabras, un término hiperónimo es una categoría que incluye a uno o varios términos hipónimos.

Por ejemplo, en la relación "animal-mamífero", "animal" es el hiperónimo y "mamífero" es el hipónimo. Esto significa que "mamífero" es una subcategoría de "animal", ya que todos los mamíferos son animales, pero no todos los animales son mamíferos.

La relación de hiperonimia es importante en el procesamiento del lenguaje natural y la construcción de ontologías, ya que permite establecer jerarquías de términos y categorías. Además, la relación de hiperonimia es una de las relaciones semánticas más comunes en el lenguaje, y se puede encontrar en una gran variedad de campos del conocimiento.
