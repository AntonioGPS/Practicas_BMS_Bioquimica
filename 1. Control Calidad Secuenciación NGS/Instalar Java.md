## Cómo comprobar y/o instalar JAVA en tu ordenador

#### A. Comprobar si se tiene instalado Java en un ordenador Linux:
1. Abre una ventana de terminal pulsando con las teclas Ctrl + Alt + T
2. Escribe 
```
$java -version
```

#### B. Comprobar si se tiene instalado en un ordenador Windows
1. Busca el botón de Inicio de Windows
2. Busca el programa cmd
3. Ejecútalo
4. Escribe
```
>java -version
```
5. Observa que se indica la versión, que el SE Runtime Environment está también instalado, así como el Java Hotspot de 32 o 64 bits


![](https://github.com/AntonioGPS/PracticaBMS_1/blob/master/1.%20Control%20Calidad%20Secuenciaci%C3%B3n%20NGS/Imagenes/JAVA_window.png)

#### C. Qué hacer si no se tiene instalado Java
1. Para instalarlo en Windows, entra en este [ENLACE](http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html?ssSourceSiteId=otnes) y descarga la versión adecuada, teniendo en cuenta si tienes un sistema operativo de 32 o 64 bits. Para saber qué sistema operativo tienes, da con el ratón derecho sobre el icono de **Mi PC** o **Equipo** en Windows, luego, propiedades, y fíjate que en la pantalla te lo indica
![](https://github.com/AntonioGPS/PracticaBMS_1/blob/master/1.%20Control%20Calidad%20Secuenciaci%C3%B3n%20NGS/Imagenes/Windows32_o_64bit.png)
2. Para instalarlo en Linux
```
$sudo ap-get install openjdk-7-jdk
```
3. Deberás tener permiso como root e indicar tu password
