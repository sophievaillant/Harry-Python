Evolution des sentiments
https://towardsdatascience.com/basic-nlp-on-the-texts-of-harry-potter-sentiment-analysis-1b474b13651d

https://medium.com/@shalvi.shrivastava14/nlp-and-textual-analysis-of-harry-potter-series-3604bbe4c6fb

https://github.com/khushmeeet/potter-nlp

https://www.kaggle.com/asterol/harry-potter-and-the-sorcecers-stone-nlp-analysis


Evolution des interactions entre persos
https://jamiefradkin.wordpress.com/2016/03/04/metis-project-4-nlp-and-clustering-with-harry-potter-books/ (là)

https://rpubs.com/Siebelm/Harry_Potter_2


Proposition de pbtique:
comment évoluent les personnages d'HP au fil des livres?
(permet d'inclure l'évolution des sentiments: si sont de + en + positifs ou pas, l'évolution des interactions).
--> J'aime beaucoup cette angle là,
ou bien sur comment évolue la relation entre des personnages
(par ex: le triangle d'amitié Harry-Hermione-Ron) 
un peu sur le modèle de ce qu'a fait le mec (là) qui analyse l'évolution de HP-Snape.

voir aussi sur ce type de sujet:
https://medium.com/zareen-farooqui/harry-potter-text-analysis-4d89ffe59d5b


Suivi du projet:

1) Nettoyage des données pour lundi aprem
- Mettre les textes en csv
- Virer les petits mots
- Nettoyer les bas de pages du 2 au 7 
- Concaténer les textes nettoyés pour pouvoir faire une analyse des chapitres
/!\ ATTENTION: du 2 au 7, les chapitres sont pas indiqués juste EN MAJUSCULES
- Créer un dictionnaire de dictionnaires (cf "https://towardsdatascience.com/basic-nlp-on-the-texts-of-harry-potter-sentiment-analysis-1b474b13651d" )

2) Stats des 
- graph des noms qui reviennent le plus (voir modules python) (Sophie ou Adrien)
- les noms proches (dans la même phrase): score de proximité (ADRIEN)
- modules de sentiments: positifs, négatifs, neutres: trouver peut-être une base ou un package qui catégorise les sentiments (Sophie)
- recouper sentiments et persos 

SUITE:
- reprendre le truc de positivité des sentiments, essayer de tronquer à partir du score de proximité aux mots où deux personnages apparaissent pour
déterminer la positivité/négativité de leur relation
- essayer d'enlever les neutres parce que c'est un roman et beaucoup de mots sont neutres ce qui donne un score très proche de 0
