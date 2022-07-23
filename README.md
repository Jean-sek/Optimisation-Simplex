# Optimisation-Simplex

Le problème d’optimisation dit du « sac à dos » (KP) peut être rencontré dans plusieurs domaine d’activités économiques. C’est le cas, par exemple : 
en finance quand il s’agit d’optimiser la gestion d’un portefeuille d’actifs afin trouver le meilleur rapport entre rendement et risque pour un capital donné ;
en logistique quand il est question d’optimiser un chargement de conteneur ou d’entrepôt
en industrie lorsqu’il s’agit d’optimiser une production sous contrainte de disponibilité de ressources. 
Il existe bien d’autres domaines d’application du problème du sac à dos. Nous présentons ici un exemple de résolution de ce problème dans le cas d’une optimisation de production en utilisant l’algorithme du simplex.

La résolution de notre problème consiste à trouver la combinaison des nombres de produits P1 et P2 à fabriquer pour maximiser les ventes.
Les marges unitaires de vente des produits sont respectivement de 200 et 150 euros.
Quatre machines (M1, M2, M3 et M4) sont utilisées pour la fabrication des produits. Les disponibilités de ces machines s’évaluent respectivement à 400, 700, 800 et 1000 unités de disponibilité (heures)
Le produit P1 nécessite pour sa fabrication une unité de disponibilité de M1, une de M3 et deux de M4
Le produit P2 nécessite pour sa fabrication une unité de disponibilité de M2, une de M3 et une de M4
