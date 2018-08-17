# Laboratorio 02

### Alineamiento de secuencias

###### BIOL311            Camila Romero

***

### Parte 1: Colectar genes homólogos

#### 1.- ¿Qué función cumple el gen SRY? [2] 

Este gen sin intrones codifica un factor de transcripción que es un miembro de la familia de proteínas de unión a ADN del grupo de alta movilidad (HMG). Esta proteína es el factor determinante de los testículos (TDF), que inicia la determinación del sexo masculino. Ésta información fue extraída desde el siguiente [link](https://www.ncbi.nlm.nih.gov/gene/6736).

#### 2.- ¿Cuántos genes ortólogos están anotados en esa base de datos? [1] 

En esta base de datos se encuentran 29 genes ortólogos. Ésta información fue extraída desde el siguiente [link](https://www.ncbi.nlm.nih.gov/gene/?Term=ortholog_gene_6736[group]). 

***

### Parte 2: Alineamiento múltiple

***

#### 3.- ¿Qué es el EMBL-EBI? [2] 

Es una organización Europea que contiene varias herramientas y una gran base de datos, la cual puede ser ocupada por científicos para realizar varias actividades. Ésta información fue extraída desde el siguiente [link](https://www.ebi.ac.uk/). 

#### 4.- ¿Cuál es el programa que ellos ofrecen que funciona mejor para secuencias de proteínas? [2] 

El programa que funciona mejor para secuencias proteicas es MUSCLE. Ésta información fue extraída desde el siguiente [link](https://www.ebi.ac.uk/Tools/msa/). 

#### 5.- ¿Qué otros tipo de herramientas ofrece EMBL-EBI? [2]

Se pueden dividir en herramientas para: DNA y RNA, expresion de genes, proteinas, estructuras, sistemas, biologia quimica, ontologias y dominios cruzados. Ésta información fue extraída desde el siguiente [link](<https://www.ebi.ac.uk/services>). 

 #### 6.- ¿Cuál es el costo de abrir un gap? [1] 

El costo de abrir un gap es -1,53. Ésta información fue extraída desde el siguiente [link](<https://www.ebi.ac.uk/Tools/msa/mafft/>). 

#### 7.- ¿Cuál es el costo de extender un gap? [1]

El costo de extender un gap es -0,123. Ésta información fue extraída desde el siguiente [link](<https://www.ebi.ac.uk/Tools/msa/mafft/>). 

 #### 8.- ¿Cuál es la longitud total del alineamiento? [1] 

La longitud total es 1934 pb. Ésta información fue extraída desde el siguiente [link](https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180811-023408-0859-31456864-p1m&analysis=summary). 

#### 9.- ¿Cuál es la especie cuyo gen SRY está más relacionado con el gen SRY de humanos? [2] 

La especie cuyo gen SRY esta más relacionado con el gen SRY de humanos es el primate Colobo rojo ugandés (nombre cientifico:Piliocolobus tephrosceles). Ésta información fue extraída desde el siguiente [link](https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180811-023408-0859-31456864-p1m&analysis=phylotree).

#### 10.- ¿Cuál es el más lejano? [2] 

La especie mas lejana al gen SRY de humanos es el del Vampiro de Azara, una especie de murciélago (nombre cientifico: Desmodus rotundus).  Ésta información fue extraída desde el siguiente [link](https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180811-025411-0715-39382706-p2m&analysis=phylotree).

#### 11.- ¿Cuál es la especie cuyo gen SRY es más cercana a la del burro? [2] 

La especie cuyo gen SRY es mas cercana a la del burro es el caballo de Przewalski (nombre cientíco: Equus ferus przewalskii). Ésta información fue extraída desde el siguiente [link](https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180811-025411-0715-39382706-p2m&analysis=phylotree).

#### 12.- ¿Cómo esperas que sea el alineamiento si el costo de abrir un gap aumenta? ¿Y si disminuye? [3] 

Si el costo de abrir gaps aumenta, se le dará preferencia a extender un gap. En cambi si disminuye, se preferira abrir un gap en vez de extenderlo, esto es porque se busca el menor costo de penalización.

#### 13.- ¿Cómo esperas que sea el alineamiento si el costo de extender un gap aumenta? ¿Y si disminuye? [3] 

Si el costo de extender un gap aumenta, se preferirá abrir un gap, y por el contrario, si disminuye el costo de extender un gap, se preferirá extender un gap, buscando la menor penalización posible.

#### 14.- ¿Cuál fue el efecto de aumentar el costo de abrir un gap en la longitud total del alineamiento? [2] 

La longitud total del alineamiento es 1895 pb, ya que al ser una mayor penalización abrir un gap, se va a tomar preferencia por extender un gap en vez de abrir un gap. Ésta información fue extraída desde el siguiente [link](https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180811-030726-0071-24599517-p2m).

#### 15.- Prueba lo mismo, pero esta vez disminuyendo al mínimo el costo de extender un gap. Describe cómo cambia el alineamiento. [2] 

El alinamiento cambia, pasa de tener una longitud de 1934 bp a 1953 bp.

***

### Parte 3: Diseño de partidores

***

#### 16.- Agrega a tu informe una lista de los "*LEFT PRIMER*" y "*RIGHT PRIMER*" que obtuviste usando Primer3. [3] 

|      |     LEFT PRIMER      |     RIGHT PRIMER     |
| :--: | :------------------: | :------------------: |
|  1   | AGAGTGAAGCGACCCATGAA | TCTCTGTGCATGGCCTGTAA |
|  2   | TTACAGGCCATGCACAGAGA | CTTGAGTGTGTGGCTTTCGT |
|  3   | GGATAGAGTGAAGCGACCCA | TTTCTCTCTGTGCATGGCCT |
|  4   | AGATGCTGCCGAAGAATTGC | GCTTTGTCCAGTGGCTGTAG |
|  5   | CGAAGATGCTGCCGAAGAAT | CTACAGCTTTGTCCAGTGGC |



#### 17.-Indica los partidores *forward* y *reverse* que escogiste y explica por qué son la mejor opción para amplificar el gen SRY de humano. [5] 

Los partidores número 1 de la columna de los LEFT PRIMER (AGAGTGAAGCGACCCATGAA) y 1 de la columna RIGHT PRIMER (TCTCTGTGCATGGCCTGTAA), son la mejor opcion para amplificar el gen ya que tienen caracteristicas similares, como la TM y el porcentaje de G/C  y sus caracteristicas son aceptables para cumplir con la funcion del primer.

#### 18.- ¿Cuál es el largo del amplicón? ¿Y la temperatura de *annealing* sugerida? [3]

 El largo del amplicon es 191 nucleotidos y la temperatura de annealing sugerida es 54°C





