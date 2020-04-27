# Dataiku-Labwork
Lors du processus de recrutement chez Dataiku, j'ai eu à réaliser un exercice de classification à partir d'un jeu de données brutes.
La question était de construire un modèle permettant de classifier si une personne gagnait + ou - de 50k€/an. Le réel but de cet exercice n'est pas de résoudre le problème, mais de montrer les méthodes que j'utilise, comment j'approche un problème, etc...


Quelques erreurs à noter : 
- lorsque je normalise les données, je devrai utiliser un **scaler** afin de conserver les bonnes proportions de données.
- la fonction **concat_deconcat** n'est pas forcément le meilleur moyen de construire un dataframe avec des données catégoriques encodées mais c'est une méthode que j'avais utilisé sur un autre projet, je l'ai donc ré-utilisé ici.

Je met cet exercice en ligne pour montrer la manière dont j'écris mon code. 
