# Laboratorio 04 - Filogenética Molecular

#### Por José Miguel Yañez Mena  

### phylogeny.fr
A la Carte

¿Qué cosas ofrece este portal? 

Phylogeny.fr ha sido diseñado para proporcionar una plataforma de alto rendimiento que transcribe de forma transparente los programas relevantes para el análisis filogenético en una tubería completa y flexible.

¿Para qué tipo de usuario está diseñado?

 Aunque los aficionados filogenéticos serán capaces de encontrar la mayoría de sus herramientas favoritas y ejecutar análisis sofisticados, la filosofía principal de Phylogeny.fr es ayudar a los biólogos sin experiencia en la filogenia en el análisis de sus datos de una manera robusta.
 
Menciona 5 tipos de análsis que se pueden realizar en el portal de acuerdo a la documentación

Segun la documentacion en este portal se pueden realizar los siguientes analisis: Alineación múltiple, alineación múltiple mediante información estructural, filogenia con máxima verosimilitud, estimaciones de soportes de clados y representación del árbol filogenetico.

Dos filogenias: gen SRY 

1.- Una con ProbCons, GBlocks, MrBayes, y TreeDyn

![filo 1](https://github.com/Peepcross/TOO-COOL-4-THIS-LAB/blob/master/yeee.png)

Otra con ClustalW, "Remove positions with gaps", TNT, y TreeDyn

![filo 2](https://github.com/Peepcross/TOO-COOL-4-THIS-LAB/blob/master/alahu%20akbar.png)

¿A qué se refiere el paso de *Alignment curation* y para qué sirve?

 El alignment curation corresponde a la eliminacion de todas las partes que no han sido alineadas logaritmicamente, lo que podria traducirse en que las secuencias que quedan en las afueras y que no se relacionan con las demas, luego no forman arte del arbol filogenetico.

¿Cuál es la diferencia entre BioNJ y Neighbor? (Pista: revisa la documentación)

En que BioNj tiene una capacidad muchas mas taxas que Neighbor. <5000 vs <500 respectivamente.

Corre de nuevo las filogenias pero esta vez sin *Alignment curation*. ¿Cuál es el efecto en las filogenias?

ProbCons, MrBayes, y TreeDyn
![filo 1 sin curar](https://github.com/Peepcross/TOO-COOL-4-THIS-LAB/blob/master/filo%201%20sin%20curar.png)

ClustalW, TNT, y TreeDyn
![filo 2 sin curar](https://github.com/Peepcross/TOO-COOL-4-THIS-LAB/blob/master/filo%202%20sin%20curar.png)

Al no estar curadas muchas especies se repiten y el formato se ve mucho mas desordenado en comparacion a 
las que si estan curadas.

Describe las diferencias entre las filogenias que has estimado: cantidad de grupos monofiléticos, relaciones que potencialmente cambiaron, etc.

El cambio mas notorio fue en los grupos monofileticos y las distancias evolutivas, que aumentaron al no estar curados. 
