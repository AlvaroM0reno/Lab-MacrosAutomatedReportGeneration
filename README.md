Laboratorio | Generación automática de informes mediante macros
En este laboratorio, utilizará el archivo deduction_import_raw.xlsx. El archivo se encuentra en la carpeta files_for_lab. Este es el archivo de datos sin procesar que se importa desde el servidor.
Guión
El equipo de nóminas de su empresa recibe información de su cliente en un formato específico. Luego, el equipo de nóminas debe manipular la información en un formato que se pueda cargar directamente en el software de procesamiento de nóminas. El software solo puede leer la información en un formato específico. Su tarea es automatizar este proceso, lo que ahorrará mucho tiempo al equipo de nóminas y hará que el proceso sea más sólido.

Aquí hay una instantánea de cómo se ve el formato inicial del archivo entregado al equipo de nómina: enlace a la imagen - Formato de datos sin procesar en excl.

Así es como debería verse el resultado final: enlace a la imagen - Resultado final

Instrucciones
No se requieren encabezados.
La primera columna consta de números de seguro social sin guiones.
La segunda columna consta de un valor constanteEE_DDUCT
La tercera columna consta de valores de la columna AG, es decir, Benefit. Solo necesitaríamos las primeras tres letras de esta columna (si hay un valor en esa columna que tenga más de tres letras)
La cuarta columna consta del valor numérico de la columna EE Costseguido de |(barra vertical repetida seis veces)
