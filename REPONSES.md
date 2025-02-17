## REPONSES :
1. Peut-on modifier l'âge d'un chien une fois qu'il a été créé (essayez de donner 10 ans à chien3 pour vérifier) ? 

Oui, une fois créé, le chien peut changer d'âge.

2. Que se passe-t-il si on modifie le nom de chien2 ?

Le nom du chien ne change pas.

3. Pourquoi tous les chiens ont tous le même nom ?

Car la classe qui créé le nom est static : nom est partagé par tous les objets, ce qui signifie que modifier le nom de n'importe quel chien modifiera celui de tous les chiens.

4. Observez avec attention les lignes N°20 à N°26 du main() et réfléchissez : par quel miracle le chien3 à la ligne N°26 s'affiche correctement ?
   Répondez à cette question en expliquant avec précision ce qui se passe et pourquoi.

Car java utilise la méthode toString() par défaut.
