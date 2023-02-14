## Práctica en la que realizaremos un ensamblado del genoma de la bacteria *E. coli*.

- Las lecturas (secuencias pareadas) las descargaremos de servidores públicos en forma de archivos fastq.

- Comprobaremos mediante instrucciones bash de Linux de qué tipo de lecturas se corresponden, si son pareadas o no. Al mismo tiempo descubriremos cuál es el numero de secuencias que tiene y calcularemos la cobertura que tiene comparándola con el genoma de otras *E.coli* que se hayan publicado en Internet.

- Tras hacer un control de calidad con FastQC, valoraremos si es necesario realizar un filtrado o no.

- Tras el filtrado o no de las lecturas, realizaremos el ensamblado del genoma con el programa Velvet usando varios valores de kmer para elaborar las graficas de De Bruijn.

- Evaluaremos las diferentes opciones para ejecutar el programa Velveth y Velvetg. EL primero de ellos crea los kmers con las lecturas, y el segundo las gráficas de Bruijn y el borrador del genoma, generando un archivo de estadísticas y de contigs.

- Con ayuda de Linux, hay que averiguar el número de contigs que se crean con el programa Velvet. Discutiremos el clase el por qué a cada alumno le sale un número diferente de contigs en el ensamblado.

- A continuación compararemos los diferentes ensamblados con otro genoma de referencia de *E. coli* del que se tiene cierta certeza que es correcto con ayuda del programa Mauve, y decidiremos que ensamblado es el más valoraremos.

- La práctica implica que el alumno instala los programas necesarios, descarga los archivos adecuados y realiza todo el proceso hasta culminar con el proceso desde el principio hasta el final.

- El procedimiento está desarrollado en [ENLACE](http://www.uco.es/users/bb1rofra/BiologiaSistemas/Tema6_Genomica/practicas/TutorialGenomicaBacteriana_archivos/Tutorial_Velvet_Ecoli.html). Abridlo y seguir las instrucciones. 

**Debéis incorporar toda la información obtenida y resultados en vuestra pagina WEB**
