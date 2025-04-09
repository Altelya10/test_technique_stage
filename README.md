## test_technique_stage
## Laura JACQUESON

## Exécution du code 
Comme ce projet utilise Jupyter Notebook, il est donc nécessaire d'ouvrir les fichiers `.ipynb` avec Jupyter Notebook pour pouvoir exécuter le code. Il est également nécessaire d'avoir les bibliothèques `pandas` et `json` d'installées. 

## Choix et logique 
J'ai fait le choix d'utiliser Jupyter Notebook pour faire le projet car je suis déjà familiarisée avec cet outil, comme nous l'avons déjà utilisé en cours, et il permet de mieux visualiser les CSV, ce qui m'a aidée dans la réalisation du projet.

Le script suit la logique suivante :
- importation des fichiers CSV 
- création d'un objet pour la structure JSON 
- ajout des éléments dans la structure 
- création du fichier JSON 

Pour la récupération des données dans les CSV, j'avais le choix de faire une fusion des fichiers ou non. Cette fusion aurait abouti à une table de 97 colonnes, ce qui en fait un objet lourd à traiter et rend l'accès aux données complexe. J'ai donc fait le choix de ne pas les fusionner et de récupérer les données séparément.

Le projet contient deux fonctions annexes pour le traitement du format des dates et pour la vérification des couleurs des ampoules. 

Je vérifie pour chaque attribut si une valeur existe avant de l'ajouter. S'il n'y en a pas, aucun attribut ne sera ajouté afin d’éviter d’avoir des valeurs à `"null"`.

