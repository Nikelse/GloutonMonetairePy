# Glouton Monetaire
- rendre la monnaie avec le minimum de pièces possibles parmi une liste
- optimal -> algorithme fonctionnel avec les pièces disponibles du modèle Européen par exemple
- non optimal -> des pièces avec des valeurs différentes

Algorithme glouton -> qui mange tout mais ne ressort pas forcement un résultat pertinent, car il dépend de son jeu de données.

# Exemple : 
- liste de pieces disponibles :18euros, 7eurso, 1euros
- rendre 21 euros en minimum de piece
-> la logique programme ici va rendre une piece de 18euros, et 3 pièces de 1euro ce qui donne un total de 4pièces
-> pourtant 3 pièces de 7euros suffisaient pour arriver à la somme

L'algorithme dépend donc du set de données à savoir que le système monétaire permet de rendre cet algo optimal dans certains cas seulements.
