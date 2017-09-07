# Laboratorio 04 - Filogenética Molecular

## Plataforma phylogeny.fr y preparación de datos

### ¿Qué cosas ofrece este portal? 

_R_:Es una web que se enfoca en la reconstrucción y analisis de relaciones filogeneticas entre secuencias moleculares. Además otorga 3 opciones de analisis filogenicos sencillos("One Click","Advanced" y "A la Carte").  

### ¿Para qué tipo de usuario está diseñado?

_R_: Para los usuarios no especialistas.

### Menciona 5 tipos de análsis que se pueden realizar en el portal de acuerdo a la documentación

_R_: Posee 4 categorias de herramientas
    
    - De aliniamiento multiple como el Muscle
    
    - De filogenia como el PhyML o TNT.
    
    - De Utilidades como el Readseq
    
    - De "Tree viewers" como el TreeDyn o Drawgram
    
### ¿A qué se refiere el paso de *Alignment curation* y para qué sirve?

_R_: Se refiera a la "limpieza" de las secuencias.

### ¿Cuál es la diferencia entre BioNJ y Neighbor? (Pista: revisa la documentación)

_R_: La diferencia esta en sus taxones. BioNJ puede llegar hasta 5000 taxones en cambio Neighbor llega hasta 500 taxones.

### Corre de nuevo las filogenias pero esta vez sin *Alignment curation*. ¿Cuál es el efecto en las filogenias?

_R_:[FilogeniaconProbCons,GBlock,MrBayesyTreeDyn](https://drive.google.com/file/d/0B0rzqm380_roSUQyaWY5MjFDcjQ/view?usp=sharing)

[PNG](https://drive.google.com/file/d/0B0rzqm380_roajRZWUt6aUFfT2M/view?usp=sharing) 
[sin curacion](https://drive.google.com/file/d/0B0rzqm380_roMnJ2WWZmVTZJOFU/view?usp=sharing)
[PNGdelasincuracion](https://drive.google.com/file/d/0B0rzqm380_roc0xpejRxYmtkWFE/view?usp=sharing)

[FilogeniaconClustalW,"Remove positions with gaps",TNTyTreeDyn](https://drive.google.com/file/d/0B0rzqm380_roX3pGRWpOWkdQNXc/view?usp=sharing)

[PNG](https://drive.google.com/file/d/0B0rzqm380_roX0d5Ny1oQ1VKM2c/view?usp=sharing)
[sin curacion](https://drive.google.com/file/d/0B0rzqm380_rodUtOUWRJU1VnbkU/view?usp=sharing)
[PNGdelasincuracion](https://drive.google.com/file/d/0B0rzqm380_roY2xyaG5ZT2QwWms/view?usp=sharing)

### Describe las diferencias entre las filogenias que has estimado: cantidad de grupos monofiléticos, relaciones que potencialmente cambiaron, etc.

_R_:Las relaciones varian bastantes entre ambas filogenias. En la primera filogenia(con ProbCons, GBlocks, MrBayes, y TreeDyn) el organismo Gavia _Stellata_ no posee un ancestro en comun cercano con la especie _Orycteropus afer afer_, encambio en la segunda filogenia estos tienen un ancestro en comun cercano, en otro caso las especies _Bos Taurus_, _Bos Indicus_ y _Bison Bison Bison_ presentan la misma relacion en ambas filogenias. 
Con respecto a los grupos monofileticos la Filogenia 1 posee y la filogenia 2 tiene
