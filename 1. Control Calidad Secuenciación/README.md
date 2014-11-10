##Instrucciones para el Control de Calidad de lecturas NGS

1. Comprueba abriendo una ventana de comando en tu ordenador (una terminal en Linux o con "inicio" y cmd en tu Windows) si tienes instalado Java. Si no sabes como hacerlo, mira el documento **Instalar Java.md**
2. Instala el programa [**FastQC**](http://www.bioinformatics.babraham.ac.uk/projects/fastqc/), que funcionando bajo JAVA, puede ser usado en cualquier plataforma (Windows, Linux y Macintoh). Lee el manual que se incluye dentro de los documentos que te descargas para ver cómo se ejecuta en tu ordenador. El programa se inicia de forma distinta dependiendo de si la plataforma el Linux o es Windows
3. Busca e Instala el paquete de herramientas [**FastX-Toolkit**](http://hannonlab.cshl.edu/fastx_toolkit/). Este programa solo funciona bajo sistemas Linux o Macintosh. Si dispones de Windows, deberás ser capaz de instalar Linux.
4. En la página de FastX-Toolkit accede al enlace que pone **Command-Line Usage** para encontrar aquella utilidad que consideres más oportuna para hacer el recorte (trimming) por calidad de las secuencias. Descubrirás que también hay utilidades para el recorte por longitud, y otras utilidades más. Describelas en tu documento

#####Respecto a la secuencia *Sec_RNA.fastq*
5. Analiza la calidad del archivo ***Sec_RNA.fastq*** con el programa FastQC. Guarda los resultados con ayuda del propio programa (lo hará en un archivo zip que contiene páginas WEB)
6. Realiza un trimming con ayuda del programa adecuado de los contenido en FastX-Toolkit con valores de calidad superiores a un valor de Q igual o superior a 20. Comenta los resultados
7. Idem sobre el archivo original con un valor de calidad igual o superior a 28. Ahora analiza los resultados y responde qué ha mejorado o empeorado con este trimming.
8. Ahora trata de hacer un trimming mixto, en el que se hace un filtrado doble de los datos. Elimina aquellas secuencias que no tengan una calidad Q mínima de Q28, pero tambíen elimina aquellas lecturas que tengan una longitud inferior a 30 bases como consecuencia del filtrado anterior
9. Indica que porcentaje de secuencias son eliminadas y conservadas en cada caso

#####Respecto a la secuencia *Sec_SOLid.fastq*
1. Haz un análisis de este archivo con FastQC y comenta lo resultados
2. Haz un trimming de los datos para obtener lecturas con una calidad mínima de Q20. Comenta los resultados
3. Ahora, haz el trimming de los datos con una calidad mínima de Q28. Comenta los resultados
4. Haz ahora un trimming de las secuencias que tienen una calidad mínima de Q28, pero eliminando las lecturas con una longitud inferior a 47. Comenta los resultados
5. Y finalmente filtra las lecturas que tengan menos de un 90% de las secuencias conteniendo una calidad por encima de Q20. Comenta los resultados