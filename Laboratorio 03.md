# :microscope: Laboratorio 03 - Ensamblaje de genomas y predicción de genes :woman_scientist:

###### Camila romero                  BIOL311

***

### Parte 1: El artículo genoma

#### 1.- ¿Cuántos *Sequencing Projects* y *Analysis Projects* hay depositados en GOLD? ¿Cuál es la diferencia entre ambos? [2] 

Existen 215.124 sequencing projects y 174.941 analysis projects. La diferencia es que en sequencing projects el secuenciamiento es directo de la muestra o el oganismo, en cambio analysis project son los procesos informaticos del secuenciamiento de las muestras o el organismo. Esta información fue obtenida del siguiente [link](<https://gold.jgi.doe.gov/>).

#### 2.- ¿Cuál es el dominio más representado en la base de datos, *archea*, *bacteria*, *eukaryote*, o *virus*? [1]  

El dominio más representado son las bacterias con 111.074 proyectos relacionados. Esta información fue obtenida del siguiente [link](<https://gold.jgi.doe.gov/statistics>).

#### 3.- ¿Cuáles son los *phyla* más representados entre los proyectos de genomas bacterianos en la base de datos? [1]  

Los phyla mas representados en cuanto a genomas bacterianos son  las proteobacterias (53.821(48,8%)). Esta información fue obtenida del siguiente [link](<https://gold.jgi.doe.gov/statistics>).

#### 4.- ¿A qué tipo de proyectos pertenece la mayor cantidad de genomas bacterianos depositados en GOLD? (tipo de proyecto, se refiere al tópico de la investigación, por ejemplo, salud humana, ambiental, etc.) [1]  

La mayor cantidad de proyectos es en base a medicina. Esta información fue obtenida del siguiente [link](<https://gold.jgi.doe.gov/statistics>).

#### 5.- ¿Cuál es el artículo original del genoma? (en el cual se reporta la sequenciación y ensamble del genoma) [2]  

El articulo lleva por nombre ''The bonobo genome compared with the chimpanzee and human genomes'' y fue publicado por el instituto de antropoigia evolucionaria Max Planck. Esta información fue obtenida del siguiente [link](https://www.ncbi.nlm.nih.gov/pubmed/22722832).

#### 6.- Explica, qué es el N50, L50, y NG50. [3] 

N50 es la medida en donde despues del ordenamiento de los contings, este se encuentra en la mitad (50%) del largo total se la secuencia.

L50 es el menor numero de contings cuya suma de longitud es igual a la de N50.

NG50 es como el N50 pero solo con los genes codificados, es decir es la mitad del genoma conocido. 

#### 7.- ¿Cuál es el propósito de calcular estas estadísticas? [3] 

El proposito es establecer parametros que son utiles al momento de realizar experimentos de ensamblaje , evaluando la calidad del genoma, y establecer predicciones en base a estos valores estadisticos.

#### 8.- ¿Cuántos *contigs* conforman el genoma del Bonobo? ¿Cuál es el N50 y L50 del genoma? (responde basado en los *contigs*) [3] 

El genoma del Bonobo esta conformado por 121,356 contigs, cuyo N50 es 66,676 y L50 es 11,048. Esta información fue obtenida del siguiente [link](https://www.ncbi.nlm.nih.gov/assembly/GCF_000258655.2).

#### 9.- ¿Cuál es el largo total y porcentaje de GC del genoma del Bonobo? ¿Qué quieren decir o qué indican éstos valores? 

El largo total es 3286.64 Mb y el porcentaje de GC es %42.3185. Esta información fue obtenida del siguiente [link](https://www.ncbi.nlm.nih.gov/genome/?term=txid9597).

#### 10.- ¿Qué tipo de tecnología se uso para secuenciar el genoma del Bonobo? ¿Qué método (programa o algorítmo bioinformático) se usó para ensamblar el genoma? 

Se uso secuenciamiento 454, y usando el software  Celera Assember para ensamblar el genoma. Esta información fue obtenida del siguiente [link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3498939/).

------

### Parte 2: Predicción de genes

***

#### 11.- Describe los resultados obtenidos. ¿Cuántos ORFs o genes encontró ORFfinder? ¿En qué hebra están codificados? ¿De qué largo son los ORFs predichos? ¿Algunos de ellos se sobreponen (fíjate en la posición de inicio [*start*] y término [*stop*])? [3] 

ORFfinder encontró 7 genes. Algunos de ellos se sobreponen: el ORF7 se sobrepone con el ORF1, El ORF4 se sobrepone con los ORFs 6 y 2, el ORF 5 se sobrepone con el ORF3. Esta informacion fue obtenida del siguiente [link](https://www.ncbi.nlm.nih.gov/orffinder/).

| ORFs | largo (nucleotidos) | largo (aminoácidos) | hebra |
| :--: | :-----------------: | :-----------------: | :---: |
|  1   |         909         |         302         |   +   |
|  2   |         78          |         25          |   +   |
|  3   |         99          |         32          |   +   |
|  4   |         441         |         146         |   -   |
|  5   |         405         |         134         |   -   |
|  6   |         84          |         27          |   -   |
|  7   |         144         |         47          |   -   |





#### 12.- ¿Qué tipo de programa es ORFfinder, *Ab initio* o por homología? [2] 

ORFfinder es un programa de tipo *ab initio*.

#### 13.- ¿A qué organismo pertenece la secuencia en cuestión? [2] 

La secuencia pertenece a los cocobacilos gram- negativo Haemophilus influenzae. Esta información fue obtenida de [link](https://blast.ncbi.nlm.nih.gov/Blast.cgi#alnHdr_1348135914).

#### 14.- ¿Qué gen(s) está(n) codificados en la secuencia? [2] 

el ORF1 codifica para la proteina formate dehydrogenase (FdhE)

el ORF4 codifica para peptide N-acetyltransferase

el ORF5 codifica para DNA polymerase III subunit psi

#### 15.- Tomando en cuenta la evidencia que acumulaste usando ORFfinder y BLAST. ¿Cuál o cuáles ORFs predichos por ORFfinder dirías tú que son o es el correcto(s)? [3] 

Los mas correctos son los ORFs 1, 4 y 5 ya que stos son los mas largos, los otros ORFs estan contenidos dentro de estos por eso lo mas probable es que los orfs ya nombrados correspondan a la secuencia completa que codifica para las distintas proteinas mencionadas en la preguta anterior.