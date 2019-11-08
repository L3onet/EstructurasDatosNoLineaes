# Estructuras de datos no lineales

Proyecto de estructuras de datos no lineales con Python.

## Árboles 

El árbol es una estructura de datos muy importante en informática y en ciencias de la computación.
Los árboles son estructuras no lineales, al contrario que los arrays y las listas enlazadas,
que constituyen estructuras lineales.
Los árboles se utilizan para representar fórmulas algebraicas, para organizar objetos en orden
de tal forma que las búsquedas sean muy eficientes y en aplicaciones diversas tales como
inteligencia artificial o algoritmos de cifrado. Casi todos los sistemas operativos almacenan sus
archivos en árboles o estructuras similares a árboles. Además de las aplicaciones citadas, los
árboles se utilizan en diseño de compiladores, procesado de texto y algoritmos de búsqueda.


### Árboles binarios de búsqueda.

Un **árbol binario** es un árbol cuyos nodos no pueden tener más de dos subárboles. En un árbol
binario, cada nodo puede tener cero, uno o dos hijos (subárboles). Se conoce el nodo de la izquierda
como *hijo izquierdo* y el nodo de la derecha como *hijo derecho*.

Un árbol binario es una estructura recursiva. Cada nodo es la raíz de su propio subárbol y
tiene hijos, que son raíces de árboles, llamados subárboles derecho e izquierdo del nodo, respectivamente.
Un árbol binario se divide en tres subconjuntos disjuntos:

`{R}` Nodo raíz.

`{I1, I2, ...In}` Subárbol izquierdo de R.

`{D1, D2, ...Dn}` Subárbol derecho de R.

## Grafos

Los grafos tienen aplicaciones en campos tan diversos como sociología, química, geografía, ingeniería eléctrica
e industrial, etc. Los grafos se estudian como estructuras de datos o tipos abstractos de datos.

Un grafo G agrupa *entes* físicos o conceptuales y las relaciones entre ellos. Un grafo está formado
por un conjunto de vértices o nodos *V*, que representan a los *entes*, y un conjunto de arcos *A*,
que representan las relaciones entre vértices. Se representa con el par *G = (V, A)*. Un grafo formado 
por los vértices `V = {1,4,5,7,9}` y el conjunto de arcos `A = {(1,4),
(4,1), (5,1), (1, 5), (7,9), (9,7), (7,5), (5,7), (4,9), (9,4)}`.

Un arco o arista representa una *relación* entre dos nodos. Esta relación, al estar formada
por dos nodos, se representa por *(u, v)* siendo u, v el par de nodos. El grafo es *no dirigido* si
los arcos están formados por pares de nodos no ordenados, no apuntados; se representa con un
segmento uniendo los nodos, *u — v*.

Un grafo es dirigido, también denominado *digrafo*, si los pares de nodos que forman los arcos
son ordenados; se representan con una flecha que indica la dirección de la relación, `u → v`. El grafo
consta de los vértices `V = {C,D,E,F,H}` y de los arcos `A = {(C,D,),
(D,F), (E,H), (H,E), (E,C)}` forma el grafo dirigido `G = {V,A}`

Fuente:

Joyanes-Aguilar, L., & Zahonero-Martinez, I. (2008). *Estructuras de datos en Java*. Madrid, España: McGraw-Hill.
