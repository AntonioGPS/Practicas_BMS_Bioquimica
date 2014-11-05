##Instrucciones para el Control de Calidad de lecturas NGS

1. Comprueba abriendo una ventana de comando en tu ordenador (una terminal en Linux o con "inicio" y cmd en tu Windows) si tienes instalado Java. Si no sabes como hacerlo, mira el documento **Instalar Java.md**
2. Instala el programa [**FastQC**](http://www.bioinformatics.babraham.ac.uk/projects/fastqc/), que funcionando bajo JAVA, puede ser usado en cualquier plataforma (Windows, Linux y Macintoh). Lee el manual para ejecutarlo en tu ordenador. Es importante saber que el programa se inicia de forma distinta dependiendo de la plataforma
3. Instala el paquete de herramientas [**FastX-Toolkit**](http://hannonlab.cshl.edu/fastx_toolkit/). Este programa solo funciona bajo sistemas Linux o Macintosh. Si dispones de Windows, deberás ser capaz de instalar Linux.
4. En la página de FastX-Toolkit accede al enlace que pone **Command-Line Usage** para encontrar aquella utilidad que consideres más oportuna para hacer el recortado (trimming) por calidad de las secuencias
5. Analiza la calidad del archivo RNA_original.fastq con el programa FastQC. Guarda los resultados con ayuda del propio programa
6. Realiza un trimming con ayuda del programa adecuado de los contenido en FastX-Toolkit con valores de calidad superiores a un valor de Q igual o superior a 20
7. Idem sobre el archivo original RNA_original.fastq con un valor de calidad igual o superior a 28
8. Indica que porcentaje de secuencias son eliminadas y conservadas

