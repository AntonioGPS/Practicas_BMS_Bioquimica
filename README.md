## Prácticas básicas sobre tecnología NGS.

En esta ocasión realizaremos un análisis mediante ***FastQC*** de las secuencias correspondientes a lecturas RNA-Seq provenientes de un secuenciador Illumina y uno SOLiD

En las secuencias con Illumina valoraremos la calidad y realizaremos un trimming de lecturas de varias formas distintas.

Con las lecturas SOLiD simplemente veremos el patrón característico de calidad que se obtiene con esta plataforma de secuenciación, para su consideración.

Una vez valorada la calidad de las secuencias usaremos, de ser necesario, una de las muchas herramientas de trimming como ***fastq_quality_trimmer***, una de las utilidades
presentes en la colección de herramientas **FASTX-Toolkit** (http://hannonlab.cshl.edu/fastx_toolkit/).

Hay que tener en cuenta que hay otros programas alternativos para realizar el trimming, y que no todos funcionan de igual
forma.
