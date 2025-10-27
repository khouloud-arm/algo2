Problème 1 : Somme des éléments distincts de deux ensembles

Description :
Ce problème consiste à trouver la somme de tous les éléments qui apparaissent dans l'un ou l'autre des deux ensembles donnés, mais pas dans les deux (éléments distincts).

Approche utilisée :

On utilise des tableaux pour représenter les deux ensembles.

On initialise une variable somme = 0.

On parcourt chaque élément du premier tableau et on vérifie s'il n'existe pas dans le deuxième tableau. Si c'est le cas, on l'ajoute à somme.

Ensuite, on parcourt chaque élément du deuxième tableau et on vérifie s'il n'existe pas dans le premier tableau. Si c'est le cas, on l'ajoute à somme.

Le résultat final est la somme de tous les éléments distincts.
Problème 2 : Produit scalaire et orthogonalité de vecteurs

Description :
Ce problème demande de calculer le produit scalaire (dot product) de deux vecteurs et de déterminer si deux vecteurs sont orthogonaux. Deux vecteurs sont orthogonaux si leur produit scalaire est nul.

Approche utilisée :

Les vecteurs sont représentés sous forme de tableaux.

Une procédure dot_product(v1, v2, ps) est utilisée pour calculer le produit scalaire et stocker le résultat dans la variable ps.

Pour n couples de vecteurs, on calcule leur produit scalaire et on vérifie si le résultat est nul pour déterminer l’orthogonalité.

La procédure peut être remplacée par une fonction dot_product(v1, v2) qui retourne directement le produit scalaire.

Des boucles imbriquées sont utilisées pour parcourir les éléments des vecteurs et effectuer la multiplication et l’addition nécessaires au produit scalaire.
Remarque :

Le passage de paramètres peut être effectué par valeur ou par référence selon que l'on utilise une fonction ou une procédure.

Les tableaux permettent de manipuler facilement les vecteurs et d’implémenter les calculs avec des boucles.
