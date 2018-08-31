### Laboratorio 04 - Filogenética Molecular 
---  

**1.** ¿Qué ofrece o para qué sirve el portal Phylogeny.fr? 

*-* Phylogeny.fr es un servicio web gratuito y fácil de usar dedicado a reconstruir y analizar las relaciones filogenéticas entre secuencias moleculares. Ejecuta y conecta varios programas bioinformáticos para reconstruir un árbol filogenético robusto a partir de un conjunto de secuencias .

**2.** Nombra y explica brevemente los 3 modos en los que se puede ejecutar el pipeline de Phylogeny.fr.

*-* One Click: Se dirige a los usuarios que no desean ocuparse de la selección de programas y parámetros. Por defecto, la canalización ya está configurada para ejecutarse y conectar programas reconocidos por su precisión y velocidad ( MUSCLE para alineación múltiple y PhyML para filogenia) para reconstruir un árbol filogenético robusto a partir de un conjunto de secuencias.

*-* Advanced mode: El servidor de Phylogeny.fr propone la sucesión de los mismos programas, pero los usuarios pueden elegir los pasos a realizar (alineación de secuencia múltiple, reconstrucción filogenética, dibujo de árbol) y las opciones de cada programa.

*-* A la carte: ofrece la posibilidad de ejecutar y probar más programas de alineación y filogenia.

**3.** Menciona qué tipos de análsis se pueden realizar en el portal de acuerdo a la documentación.

*-* Búsqueda de secuencias homólogas, Alineación múltiple, Filogenia, Espectadores de árbol, Refinamiento de alineación, Conversión de formato

**4.** Incluye en tu informe una captura de pantalla de las dos filogenias que inferiste. Recuerda que tu nombre completo debe aparecer en la imagen de cada filogenia.

*-* Filogenia N°1: ProbCons, GBlocks, MrBayes, y TreeDyn.
![](https://github.com/CamilaFrancisca/Laboratorio/blob/master/Prob%20curado.png)

*-* Filogenia N°2: ClustalW, Remove positions with gaps, TNT, y TreeDyn.
![](https://github.com/CamilaFrancisca/Laboratorio/blob/master/clustal%20curado.png)

**5.** ¿A qué se refiere el paso de _Alignment curation_ y para qué sirve? 

*-* Se refiere a las regiones ambiguas o gaps (que contienen huecos y / o mal alineados), que pueden ser eliminadas por dos metodos (Gblocks Remove positions with gaps) los cuales utilizan diversos parametros para remover dichos gaps.

**6.** ¿Cuál es la diferencia entre BioNJ y Neighbor?

*-* BIONj es una versión mejorada del algoritmo NJ basado en un modelo simple de datos de secuencia. Un algoritmo de reconstrucción de filogenia basado en la distancia, adecuado para distancias estimadas a partir de secuencias de ADN o proteínas. Tambien tiene una mejor precisión topológica que NJ en todas las condiciones evolutivas; Sin embargo, los árboles BIONJ y NJ a menudo son cercanos o idénticos, especialmente cuando el número de taxones es bajo.

**7.** Incluye en tu informe una captura de pantalla de las dos filogenias que inferiste.

*-* Filogenia N°1: ProbCons, MrBayes, y TreeDyn.

![](https://github.com/CamilaFrancisca/Laboratorio/blob/master/prob%20no%20curado.png)

*-* Filogenia N°2: ClustalW, TNT, y TreeDyn.

![](https://github.com/CamilaFrancisca/Laboratorio/blob/master/clustal%20no%20curado.png)


**8.** ¿Cuál es el efecto de no hacer la curación del alineamiento en las filogenias?

*-* Al no realizar la curacion se generan divergencias filogeneticas muy grandes afectando a los grupos monofileticos, la escala de estimacion de distancia en alos, lo nodos de las diversas especies; En general genera una filogenia distinta al no estar curada.

**9.** Describe las diferencias entre las filogenias que has estimado (4 en total): cantidad de grupos monofiléticos, relaciones que potencialmente cambiaron, etc.

*-*
