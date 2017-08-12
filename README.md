# Laboratorio 1 bioinformática
----
# Parte 1

----

## Enfermedad escogida: GLYCOGEN STORAGE DISEASE III; GSD3 (1)

#### Describe en no más de 4 lineas la causa y lo que provoca la enfermedad que escogiste

__R:__

+ `La enfermedad de almacenamiento del glicógeno III es un desorden autosomático recesivo, que es causado por mutaciones en el gen AGL(AMYLO-1,6-GLUCOSIDASE, 4-ALPHA-GLUCANOTRANSFERASE; AGL), el cual codifica para la enzima "glycogen debrancher enzyme". La enfermedad se caracteriza por un acumulamiento anormal de glicógeno de cadenas cortas externas, lo cual genera diversos problemas fisiológicos tales como hepatomegalia, hipoglucemia, estatura baja y miopatía variable. Además, existen variantes para esta enfermedad, que se diferencian en la ponderación de expresión de la proteína en distintos tejidos, principalmente hígado y tejido muscular.` (1)

#### ¿Cuál(es) gene(s) han sido relacionados con esta enfermedad?


__R:__

+ `El gen que ha sido relacionado con la enfermedad es AGL, que se localiza en 1p21.2 y posee 36 exones.` (2) 

#### ¿Tiene nombres alternativos el gen?  
	
__R:__

+ `Si, también se le denomina "GDE", que es el nombre de la enzima que codifica`.(2)

#### ¿En qué cromosoma está? ¿Cuántos exones tiene? ¿Cuántas isoformas de transcritos?  

__R:__

+ `El gen AGL se encuentra en el brazo corto del cromosoma 1. Posee 36 exones. Posee 5 isoformas de transcrito, aunque en uniprot aparecen 6 isoformas descritas (8).`


#### ¿Qué tipo de proteina es codificada por este gen? ¿Cuál es su número EC?  


__R:__

+ `Es una enzima monomérica que posee una masa de 160 KDa. Además, posee dos sitios catalíticos activos. Sus EC son EC 3.2.1.33( amylo-1,6-glucosidase) y EC 2.4.1.25(4-alpha-glucanotransferase)`.

#### ¿Qué genes están inmediatamente río arriba/abajo?  

__R:__

+ `Río abajo está el gen SLC35A3, y río arriba está el gen FRRRS1`.

#### ¿Cuál es la longitud de tu gen?
	
__R:__

+ ` El gen posee 73,947 pb.`


#### ¿Cuántas variantes de tu gen hay descritas y en qué posiciones?  

__R:__

+ `Posee 220 variantes descritas. (4)`

 + `__De las cuales:__`
 + `NM_000642.2(AGL):c.256C>T (p.Gln86Ter), __razón: Está descrito como pátogénico.__ (5)`
 + `NM_000642.2(AGL):c.276delG, __razón: Deleción de una G, es además, patogénico.__(6)`
 + `NM_000642.2(AGL):c.753_756delCAGA, __razón: Posee una deleción mayor que en el caso anterior, patogénico__(7)`


#### ¿Las sustituciones corresponden a cambios sinónimos o no sinónimos?¿Existen ortólogos de tu gen en otras especies?¿Cuántos?

__R:__

+ `Primeramente, es difícil responder esta pregunta con _certeza_, ya que de todas las variaciones, pocas han sido revisadas (curadas). De las que han sido revisadas, en su mayoría corresponden a mutaciones missense y de nucleótido simple. Por otra parte, hay 35 cambios 'benignos', que se podría interpretar como que no producen un daño significativo a nivel metabólico. Por esto, pienso que pueden haber mutaciones sinónimas, pero al parecer en una menor frecuencia que las de otra naturaleza.`

+ `Si, existen 212 genes ortólogos descritos.`(3)

#### ¿Y paralógos? ¿Hay pseudogenes? ¿Cuántos?  

__R:__

+ `En la página de variación, aparecen 0 resultados para la selección 'Duplication', por lo que basándome en ésta base de datos, no existen parálogos para el gen AGL.` 

+ `No posee pseudogenes. Hay dos pseudogenes cercanos pero corresponden a otras funciones: RPL39P9 y RP4-581O6.1.`

# Parte 2

----

+ __Página Kegg:http://www.kegg.jp/dbget-bin/www_bget?hsa:agl__.


#### Anteriormente encontraste nombres alternativos de tu gen ¿Existen otros reportados por Kegg? ¿Cuáles?

__R:__

+ `No, los sinónimos encontrados en KEGG son los mismos descritos al comienzo de este informe, sin embargo, en la página Reactome.org, encontré estos sinónimos: glycogen debranching enzyme, glycogen debrancher, GDE_HUMAN, Glycogen debranching enzyme, Glycogen debrancher, 4-alpha- glucanotransferase , Oligo-1,4-1,4-glucantransferase, Amylo-alpha-1,6-glucosidase , Amylo-1,6-glucosidase, Dextrin 6-alpha-D-glucosidase (9).` 

#### ¿En qué rutas metabólicas participa la proteina codificada por tu gen?  

__R:__

+ `En dos: Starch and sucrose metabolism(hsa00500) y Metabolic pathways(hsa01100 ).`

![hsa00500](https://github.com/CapitanFlint/Laboratorio-1-0x-8-8-2017/blob/master/scratch%20metabolic%20pathway.png)


__Imagen 1__: Ruta metabólica 'Scratch and sucrose metabolism.

![hsa01100](https://github.com/CapitanFlint/Laboratorio-1-0x-8-8-2017/blob/master/metabolic%20pathway%20general.png)


__Imagen 2__: Ruta metabólica general.


#### ¿Cuál es el número de identificación de tu gen (entry number)?  

__R:__

+ `178. Con ese código es posible acceder a la información del gen, definido como 'NCBI-GENEID'.(10) `

+ `Otros códigos de acceso son:ENSG00000162688 (Ensembl),P35573 (UniProt),610860 (OMIM),536 (HomoloGene).`


#### En general, cada unidad dentro de una base de datos tiene un número o código de identificación único. De esta forma, uno puede obtener exactamente lo que quiere dentro de un oceano de otras cosas ¿En qué otras bases de datos está tu gen presente y cuáles son sus números de acceso?  

__R:__

+ http://atlasgeneticsoncology.org/Genes/GC_AGL.html [ATLASID:55879], 

+ http://biogps.org/#goto=genereport&id=178 [Utiliza códigos de acceso de otros sitios],

+ http://reactome.org/content/detail/R-HSA-71545 [R-HSA-71545],

+ http://amigo.geneontology.org/amigo/gene_product/WB:WBGene00011050 [Esta es una variación, su código es: WBGene00011050 y está ligada a esta base de datos: http://www.wormbase.org/species/c_elegans/gene/WBGene00011050?from=http://www.wormbase.org/db/gene/gene?name=WBGene00011050#0-9g-3].


+ __NOTA:__ Las bases de datos están indicadas con su vínculo a la página web correspondiente, seguido de el código ID que se utiliza en cada base de datos, escrito entre "[]".


#### ¿En qué otras rutas metabólicas está involucrado tu gen?


__R:__


+ `Está involucrado solamente en el 'starch and sucrose metabolism', actuando específicamente en la formación de glucosa-alfa 1-fosfato a partir de glicógeno (ver #### __Imagen 1__).`


#### ¿Qué significan los cuadros verdes en el diagrama?


__R:__


+ `Los cuadros verdes corresponden a una simplificación del nombre de una enzima particular`.


#### ¿Con qué rutas se cruza la ruta metabólica?


__R:__


+ `Se cruza principalmente con Nucleotide metabolism y con Glycan biosynthesis and metabolism(ver __Imagen 2__) `. 


#### ¿Cuántos "dominios" forman la anotación GO?


__R:__


+ `Ontology Structure, Ontology Relations, Cellular Component Ontology ,Molecular Function Ontology, Biological Process Ontology,Species-Specific Terms:` 
  - `Cell`
  - `Membrane proteins`
  - `Membranes and envelopes`
  - `Protein complexes`
  - `Cell Cycle`
  - `Development`
  - `Metabolic processes`
  - `Other organisms and viruses`
  - `Regulation`
  - `Detection and Response to stimulus`
  - `Sensory perception`
  - `Transport and transporters`



#### Ve a "Tools" --> "AmiGO 2" y escribe en la casilla de búsqueda GO:0006096 ¿A qué corresponde este término y qué información te entrega la página?


__R:__


+ `El término corresponde a un proceso metabólico, especficamente a los procesos glicolíticos. La página entrega tres informaciones principales:`
- `Sobre información detallada sobre el proceso en cuestión, sirviendo como una biblioteca para acceder a otros servicios.`
- `Sobre anotaciones de ontología`.
- `Sobre los genes y productos relacionados con ese proceso metabólico`.


#### Haz clic en "Graph Views" y examina el gráfico. Anota 10 sub-categorías GO a la cual GO:0006096 pertenece


__R:__


![ProcesosGlicoliticos](https://github.com/CapitanFlint/Laboratorio-1-0x-8-8-2017/blob/master/Procesos%20glicol%C3%ADticos.png)

__Imagen 3:__ Los cuadrados de colores que aparecen abajo de cada proceso relacionado indica una especie de organismo en particular. Cada cuadrado representa una sub-categoría.


## __Glosario__:
- `Isoforma de un gen: Corresponde a una variación entre mRNA que provienen de un mismo locus y que tal diferencia se basa en el splicing.`

- `Variación de un gen: corresponden a diferencias producidas por SNPs o MNPs.`


# BIBLIOGRAFÍA

1) http://www.omim.org/entry/232400?search=disease&highlight=disease
2) https://www.ncbi.nlm.nih.gov/gene/178
3) https://www.ncbi.nlm.nih.gov/gene/?Term=ortholog_gene_178[group]
4) https://www.ncbi.nlm.nih.gov/clinvar/?term=AGL[gene]
5) https://www.ncbi.nlm.nih.gov/clinvar/variation/196286/
6) https://www.ncbi.nlm.nih.gov/clinvar/variation/371401/
7) https://www.ncbi.nlm.nih.gov/clinvar/variation/370509/
8) http://www.uniprot.org/uniprot/P35573
9) http://reactome.org/content/detail/R-HSA-71545
