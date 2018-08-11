### Parte 1: Colectar genes homólogos

---

**1.** ¿Qué función cumple el gen SRY?

*-* Regulador transcripcional que controla un cambio genético en el desarrollo masculino. Es necesario y suficiente para iniciar la determinación del sexo masculino al dirigir el desarrollo de precursores celulares de soporte (células pre-Sertoli) como Sertoli en lugar de células de la granulosa (por similitud). En el cerebro adulto masculino involucrado en el mantenimiento de las funciones motoras de las neuronas dopaminérgicas (por similitud). Participa en diferentes aspectos de la regulación génica, incluida la activación o represión del promotor (por similitud) [UniProt/Swiss-Prot](https://www.uniprot.org/uniprot/Q05066)

**2.** ¿Cuántos genes ortólogos están anotados en esa base de datos?

*-* Se han descrito hasta ahora 28 ortólogos del gen SRY de humano en otras especies. datos segun [NCBI](https://www.ncbi.nlm.nih.gov/gene/6736#reference-sequences)

*-* Secuencia Fasta de todos los ortòlogos del gen  [SRY](https://github.com/CamilaFrancisca/Laboratorio/blob/master/Fasta02.fasta)

### Parte 2: Alineamiento múltiple

---

**3.** ¿Qué es el EMBL-EBI?

*-* 

**4.** ¿Cuál es el programa que ellos ofrecen que funciona mejor para secuencias de proteínas?

*-* MUSCLE es el mejor programa ya que se adecua a alineciones mediadas logrando una mejor precisión promedio y una mejor velocidad que otras herramientas como ClustalW2 o T-Coffee.  

**5.** ¿Qué otros tipo de herramientas ofrece EMBL-EBI? 

*-* 

**6.** ¿Cuál es el costo de abrir un gap?

*-* Gap Open 1.53 [MAFFET](https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180810-153305-0272-23252617-p2m&analysis=details)

**7.** ¿Cuál es el costo de extender un gap?

*-* Gap Extension 0.123 [MAFFET](https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180810-153305-0272-23252617-p2m&analysis=details)

**8.** ¿Cuál es la longitud total del alineamiento?

*-* 1942 pb es la longitud de alineamiento

**9.** ¿Cuál es la especie cuyo gen SRY está más relacionado con el gen SRY de humanos?

*-* SRY_Piliocolobus_tephrosceles 0.00135

**10.** ¿Cuál es el más lejano?

*-* SRY_Bos_indicus 0.00109, SRY_Bison_bison 0.00326

**11.** ¿Cuál es la especie cuyo gen SRY es más cercana a la del burro?

*-* SRY_Equus_przewalskii 0.00075

**12.** ¿Cómo esperas que sea el alineamiento si el costo de abrir un gap aumenta? ¿Y si disminuye?

*-* Esperaria ver mas extenciones de gap ya que el costo de abrir un gap es mal alto que de extender uno, y si disminuye esperaria lo contrario solo sí el costo de extender un gap es mas costoso que abrir uno.

**13** ¿Cómo esperas que sea el alineamiento si el costo de extender un gap aumenta? ¿Y si disminuye?

*-* Esperaria ver mas gaps solo sí el costo de extender un gap es mayor que el costo de un gap; y si disminuye esperaria lo contrario solo sí es costo de extender es mas bajo que el de abrir un gap. 

**14.** ¿Cuál fue el efecto de aumentar el costo de abrir un gap en la longitud total del alineamiento? 

*-* Se genera mejor alineacion entre la secuencia consenso ya que al aumentar el valor del gap se prefiere extender un gap por su numero de penalizacion. 

**15.** Prueba lo mismo, pero esta vez **disminuyendo al mínimo el costo de extender un gap**. Describe cómo cambia el alineamiento.

*-* 
 
### Parte 3: Diseño de partidores

---

**16.** Agrega a tu informe una lista de los "_LEFT PRIMER_" y "_RIGHT PRIMER_" que obtuviste usando Primer3

**Primer 0** LEFT PRIMER AGAGTGAAGCGACCCATGAA

**Primer 0** RIGHT PRIMER TCTCTGTGCATGGCCTGTAA

**Primer 1** LEFT PRIMER TTACAGGCCATGCACAGAGA

**Primer 1** RIGHT PRIMER CTTGAGTGTGTGGCTTTCGT

**Primer 2** LEFT PRIMER GGATAGAGTGAAGCGACCCA
 
**Primer 2** RIGHT PRIMER TTTCTCTCTGTGCATGGCCT

**Primer 3** LEFT PRIMER AGATGCTGCCGAAGAATTGC

**Primer 3** RIGHT PRIMER GCTTTGTCCAGTGGCTGTAG

**Primer 4** LEFT PRIMER CGAAGATGCTGCCGAAGAAT

**Primer 4** RIGHT PRIMER CTACAGCTTTGTCCAGTGGC

**17.** Indica los partidores _forward_ y _reverse_ que escogiste y explica por qué son la mejor opción para amplificar el gen SRY de humano. 

**Primer ..** _forward_ LEFT PRIMER .....

**Primer ..** _reverse_ RIGHT PRIMER .....

*-* Ocuparia el partidor...  de la lista ya que posee un menor porcentaje de GC en comparacion con los otros partidores, el cual indica que al elongar la doble hebra de DNA sera mas facil de separarla a simple hebra. Tambien posee major tamaño de nucleotidos que seran alineados; por otro lado la temperatura para que el amplicon se una a la hebra (alineamiento) es un poco mejor en comparacion con los otros partidores.  

**18.** ¿Cuál es el largo del amplicón? ¿Y la temperatura de _annealing_ sugerida?

*-* El largo del amplicon es de 19. nucleotidos y su teperatura de alineamiento es de 54°C
