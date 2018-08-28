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

*-*

**5.** ¿A qué se refiere el paso de _Alignment curation_ y para qué sirve? 

*-*Después de la alineación, las regiones ambiguas (es decir, que contienen huecos y / o mal alineados) se eliminaron con Gblocks (v0.91b) utilizando los siguientes parámetros: 
- longitud mínima de un bloque después de la limpieza de huecos: 10 - no 
se permitieron huecos en la alineación final 
-todos los segmentos con posiciones contiguas no conservadas mayores de 8 fueron rechazados 
-número mínimo de secuencias para una posición de flanco: 85%

**6.** ¿Cuál es la diferencia entre BioNJ y Neighbor?

*-* BIONJ: una versión mejorada del algoritmo NJ basado en un modelo simple de datos de secuencia.
Gascuel O. Biología Molecular y Evolución. 1997 14: 685 - 695. 

Por favor cite ESTOS documentos si usa BIONJ.
Un algoritmo de reconstrucción de filogenia basado en la distancia
BIONJ es muy adecuado para distancias estimadas a partir de secuencias de ADN o proteínas. BIONJ tiene una mejor precisión topológica que NJ en todas las condiciones evolutivas; su superioridad se vuelve importante cuando las tasas de sustitución son altas y varían entre linajes. Sin embargo, los árboles BIONJ y NJ a menudo son cercanos o idénticos, especialmente cuando el número de taxones es bajo. BIONJ conserva la velocidad de NJ y se puede aplicar a conjuntos de datos muy grandes (> 1000 taxones). BIONJ se puede ejecutar en varias matrices para construir árboles bootstrap. Como de costumbre, las distancias deben corregirse, por ejemplo, usando DNADIST o PROTDIST de PHYLIP.

*-* 

**7.** Incluye en tu informe una captura de pantalla de las dos filogenias que inferiste.

*-*

**8.** ¿Cuál es el efecto de no hacer la curación del alineamiento en las filogenias?

*-*

**9.** Describe las diferencias entre las filogenias que has estimado (4 en total): cantidad de grupos monofiléticos, relaciones que potencialmente cambiaron, etc.

*-*
