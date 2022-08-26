# NFT
Scraping and analysis to create sourcing and sales opportunities in the NFT markets
Travail sur la Blockchain Cardano pour éviter les bots de tradings et disposer d'une liquidité pls faibles des actifs pour analyser le comportement des consommateurs. 


Stratégies :

Strat A: 
1) identifier les collections "nouvelles" qui font de meilleurs résultats que les collections les plus anciennes et qui fonctionnent le mieux (critères sur le volume d'échanges ALLTIME).
2) Une fois les collections identifiées, analyser parmis cette collection les prix de marché selon la classe de rareté crée et selon la marketplace sur laquelle on se place. 

--> programme à lancer chaque semaine


Strat B: 
1) Parmis les collections qui ont les meilleurs volumes de ventes, identifier les pièces qui sont sous les prix et tendances de marché pour rachat.

--> programme à lancer chaque jour


Strat C: 
1) Analyser les prix selon classe de rareté d'une collection sur chaque Marketplace. Achat revente si prix moyen de MarkeplaceA > prix moyen de MarkeplaceB. 



Etat des lieux : 
MVP OK 
Ajouter dataviz, à l'heure actuelle simple tableau csv généré. 
Ajouter des critères statistiques plus précis. 
AJouter des critères à l'analyse, popularité, volume de Markeplace. 

Etendre le modèle à d'autres Blockchain, Solana et ETH in fine. 



Fonctionement : 
Les deux programmes de scraping génèrent des fichiers csv. Le premier celui qui détermine quelles collections sont intéressantes, le deuxième utilise ce fichier pour lancer son analyse intra collection. 
