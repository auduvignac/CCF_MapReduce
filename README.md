CCF: Fast and Scalable Connected Component Computation in MapReduce
Auteurs : Hakan Kardes, Siddharth Agrawal, Xin Wang et Ang Sun

L’identification des composantes connexes dans un graphe est un problème fondamental dans de nombreux domaines tels que l’analyse des réseaux sociaux, l’exploration de données et le traitement d’images.

Cet article propose une approche basée sur le paradigme MapReduce pour détecter efficacement les composantes connexes d’un graphe. Dans ce projet, nous avons implémenté l'algorithme CCF (Connected Component Computation) en PySpark, en exploitant deux structures de données :

- RDD (Resilient Distributed Dataset) ;
- DataFrame.

Nous avons appliqué cette implémentation au graphe utilisé dans l’article avant d’étendre notre analyse à des graphes de plus grande échelle. Une étude comparative a été menée pour évaluer les performances des différentes structures de données et algorithmes étudiés.
