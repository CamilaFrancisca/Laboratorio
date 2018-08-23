### Parte 1: El artículo genoma

---

**1.** ¿Cuántos _Sequencing Projects_ y _Analysis Projects_ hay depositados en GOLD? ¿Cuál es la diferencia entre ambos?

*-* Hay 215.124 proyectos de secuencias y 174.491 de proyectos de analisis a la fecha del 17/08/18.

*-* El proyecto de secuenciacion esta dirigido al tipo de organismo o muestra que se secuenciara en cambio un proyecto de analisis esta dirigido al procesamiento informatico de un proyecto de secuenciacion.

**2.** ¿Cuál es el dominio más representado en la base de datos, _archea_, _bacteria_, _eukaryote_, o _virus_?

*-* El dominio mas representado es la bacteria con 276.030 a la fecha del 17/08/18.

**3.** ¿Cuáles son los _phyla_ más representados entre los proyectos de genomas bacterianos en la base de datos?

*-* Los phila mas representativos son medicina, ambiente, agricultura, evlucion, patogenos, patogenos humanos, humano, microbiomas, proyectos, otros. Datos referenciados a la fecha del 21/08/18

**4.** ¿A qué tipo de proyectos pertenece la mayor cantidad de genomas bacterianos depositados en GOLD? (tipo de proyecto, se refiere al tópico de la investigación, por ejemplo, salud humana, ambiental, etc).

*-* Medicina, datos referenciados por [Gold](https://gold.jgi.doe.gov/statistics).

*-* Imagen de complemento para la pregunta N°3 y N°4  
![gold](https://github.com/CamilaFrancisca/Laboratorio/blob/master/Grafico%20info3.png)


**5.** ¿Cuál es el artículo original del genoma? (en el cual se reporta la sequenciación y ensamble del genoma)

*-* El articulo original del genoma  tiene como nombre *The bonobo genome compared with the chimpanzee and human genomes*.

*-* Link al articulo original [aquí](https://www.ncbi.nlm.nih.gov/pubmed/22722832).

**6.** Explica, qué es el N50, L50, y NG50.

*-* Para poder comprender los conceptos mencionados, es importante definir lo que es un Contig; esto corresponde a segmentos de ADN superpuestos, que juntos representan una región consenso de ADN.
El valor N50 se define como la longitud del contig tal que la mitad del ensamblaje está constituida por contings de longitud igual o superior a dicho valor, y el valor L50 se define como el número de contigs de longitud igual o superior a la del contig N50. De manera similar se define el valor NG50, que toman como referencia el tamaño conocido del genoma en lugar de la longitud total de la secuencia ensamblada.

**7.** ¿Cuál es el propósito de calcular estas estadísticas?

*-* Con el uso de estos valores estadísticos se intentan evitar los peligros inherentes a depender del tamaño medio del genoma para definir otros parámetros.

**8.** ¿Cuántos _contigs_ conforman el genoma del Bonobo? ¿Cuál es el N50 y L50 del genoma? (responde basado en los _contigs_)

*-* Se forman en el genoma 121.356 conting, N50 66.676 conting, L50 11.048 conting.

**9.** ¿Cuál es el largo total y porcentaje de GC del genoma del Bonobo? ¿Qué quieren decir o qué indican éstos valores?

*-* Largo total 3286.64 Mb del genoma y su porcentaje de GC es 42.3185.

**10.** ¿Qué tipo de tecnología se uso para secuenciar el genoma del Bonobo? ¿Qué método (programa o algorítmo bioinformático) se usó para ensamblar el genoma?

*-* Se utilizo la tecnologia 454 GS FLX; 454 GS FLX Titanium y el metodo Celera Assembler v. 5.4.3.

### Parte 2: Predicción de genes

---

**11.** Describe los resultados obtenidos. ¿Cuántos ORFs o genes encontró ORFfinder? ¿En qué hebra están codificados? ¿De qué largo son los ORFs predichos? ¿Algunos de ellos se sobreponen? 

*-* Se encontraron 7 ORFs.

*-* En la hebra continua se encuentran los ORFs 1-2-3 y en la hebra discontinua se encuentran los ORFs 4-5-6-7.

*-* El largo de los ORFs son:

|  ORFs  | Largo (nt) | 
| -------|:----------:| 
|    1   |     909    | 
|    2   |      78    |  
|    3   |      99    |
|    4   |     441    |
|    5   |     405    |
|    6   |      84    |
|    7   |     144    |

*-* Se sobreponen los ORFs 2-3-6-7

**12.** ¿Qué tipo de programa es ORFfinder, _Ab initio_ o por homología?

*-* El buscador ORF busca marcos de lectura abiertos (ORF) en la secuencia de ADN que ingresas, devuelve el rango de cada ORF junto con su traducción de proteínas. ORFfinder busca ADN recientemente secuenciado para "posibles segmentos" de codificación de proteínas , Por cual se deben verificar las proteínas pronosticadas que da ORFfinder utilizando BLAST. Por lo tanto ORFfinder es un programa que trabaja por homologia confiriendo a la secuencia mas homologa su funcion.

**13.** ¿A qué organismo pertenece la secuencia en cuestión?

*-* La secuencia pertenece al organismo Haemophilus influenzae.

**14.** ¿Qué gen(s) está(n) codificados en la secuencia?

*-* Los genes codificados son *FdhE superfamily*, *NAT_SF superfamily*, *DNA_II_psi superfamily*
![IMAGEN]()

**15.** Tomando en cuenta la evidencia que acumulaste usando ORFfinder y BLAST. ¿Cuál o cuáles ORFs predichos por ORFfinder dirías tú que son o es el correcto(s)?

*-* Al analizar la secuencia problema en ORFfinder se determinaron 7 ORF de distintos tamaños, por lo cual se procedio a la realizacion de un blast, para identificar los genes completos de la secuencia problema.

*-* En primer lugar se realizo un blast Nucleotido-Proteina de la secuencia problema completa, para tener nocion de los genes predichos dando como resultado 3 genes. Por lo cual hay que discriminar cuales son de los 7 ORF que da el programa ORFfinder pertenecen a los 3 genes dados por el blast.

*-* En segundo lugar se realizo un Protein blast de cada ORF, de los cuales se analizaron su complementaridad e identidad que tiene la secuencia con la proteina, mediante los datos de query y sbjc.

*-* En conclusion los ORFs correctos que calzan con los 3 genes son los ORFS 1-4-5.

