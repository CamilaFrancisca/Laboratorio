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

*-*  Es un instituto de bioinformatica el cual proporciona datos biologicos abiertos, software de código abiertos, herramientas analíticas gratuitamente.

**4.** ¿Cuál es el programa que ellos ofrecen que funciona mejor para secuencias de proteínas?

*-* MUSCLE es el mejor programa ya que se adecua a alineciones mediadas logrando una mejor precisión promedio y una mejor velocidad que otras herramientas como ClustalW2 o T-Coffee.  

**5.** ¿Qué otros tipo de herramientas ofrece EMBL-EBI? 

*-* Ofrece alineamiento se seuencias, similitud de secuencias, mapeos ,comparaciones; todo esto en base a ADN, RNA, proteinas, estructuras, biologia quimica, ontologias, dominios cruzados. [EMBL-EBI](https://www.ebi.ac.uk/services/all)

**6.** ¿Cuál es el costo de abrir un gap?

*-* Gap Open 1.53 [MAFFET](https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180810-153305-0272-23252617-p2m&analysis=details)

**7.** ¿Cuál es el costo de extender un gap?

*-* Gap Extension 0.123 [MAFFET](https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180810-153305-0272-23252617-p2m&analysis=details)

**8.** ¿Cuál es la longitud total del alineamiento?

*-* 1942 pb es la longitud de alineamiento

**9.** ¿Cuál es la especie cuyo gen SRY está más relacionado con el gen SRY de humanos?

*-* Piliocolobus tephrosceles.

**10.** ¿Cuál es el más lejano?

*-* Bos indicus, Bison bison.

**11.** ¿Cuál es la especie cuyo gen SRY es más cercana a la del burro?

*-* Equus przewalskii.

**12.** ¿Cómo esperas que sea el alineamiento si el costo de abrir un gap aumenta? ¿Y si disminuye?

*-* Esperaria ver mas extenciones de gap ya que el costo de abrir un gap es mal alto que de extender uno, y si disminuye esperaria lo contrario solo sí el costo de extender un gap es mas costoso que abrir uno.

**13** ¿Cómo esperas que sea el alineamiento si el costo de extender un gap aumenta? ¿Y si disminuye?

*-* Esperaria ver mas gaps solo sí el costo de extender un gap es mayor que el costo de un gap; y si disminuye esperaria lo contrario solo sí es costo de extender es mas bajo que el de abrir un gap. 

**14.** ¿Cuál fue el efecto de aumentar el costo de abrir un gap en la longitud total del alineamiento? 

*-* . 1895

**15.** Prueba lo mismo, pero esta vez **disminuyendo al mínimo el costo de extender un gap**. Describe cómo cambia el alineamiento.

*-* Se genera un amuneto en el alineamiento de conseso por lo cual la secuencia es mas homologa. 1989

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

**Primer 2** _forward_ LEFT PRIMER GGATAGAGTGAAGCGACCCA

**Primer 2** _reverse_ RIGHT PRIMER TTTCTCTCTGTGCATGGCCT

*-* Ocuparia el partidor 2 de la lista ya que posee un menor porcentaje de GC en comparacion con los otros partidores, el cual indica que al elongar la doble hebra de DNA sera mas facil de separarla a simple hebra. Por otra parte el partidor 2 posee mas nucleotidos, el cual lo hace mas especifo que el partidor 0 ya que al igual que el partidor 2 posse el mismo porcentaje de GC. 

**18.** ¿Cuál es el largo del amplicón? ¿Y la temperatura de _annealing_ sugerida?

*-* El largo del amplicon es de 199 nucleotidos y su teperatura de alineamiento es de 54°C.
