Les metiers de la donnée sont ativement d'actualité. C'est le marché avec la plus grande croissance sur les dernières années. Du moins selon les rumeurs et la une.

Mais les professionnels de la donnée alors ? 
Que disent ils ? 
Sont-ils mécontent de leur style de vie ?
Sont-ils satisfaits de leur salaire ?
Quels sont les préférences salaire ? 

Tant que de question qu'il est légitime de se poser; n'est-ce pas ?

Eh bien les données ne mentent jamais, croyez moi. 

Let's go allons checker, nous allons trouver des réponses à ces questions rapidement :


## `Source des données :`
Source : enquêtes réalisée par Alex (un professionnel analyst). 
630 professionnels de la donnée au total ont répondu au questionnaire, il s'agit entre autres des data scientist, data analyst, data engineeer et autres.
La donnée est disponible sous format excel .xlsv dans le repertoire data de ce dépo.

## Grandes Parties
Pour faire cette analyse, j'ai suivi les étapes suivantes :

### Data Exploration
C'est ici j'ai pris contact avec la donnée. Savoir ses spécificités, ses caractéristiques m'ont permis d'en apprendre plus sur la donnée et surtout de préparer l'atape prochaine notamment le Data Cleaning.

### Data Cleaning
Power BI definit de manière automatique, juste après la connection à la source de donnée, les types de chaque colonnes. Parfois il faut revérifier et voir si le travail est bien fait. 
Dans Power Query j'ai effectué les tâches suivantes :

- J'ai redéfini les types des colonnes
- Fractionné les collones
- Supprimé celles qui sont désormais inutiles
- Défini de nouvelles colonnes (par calcul basé sur celles existantes)
- Nétoyé les colonnes de sorte à avoir toute donnée prête pour la visualisation

### Visuels
Ici s'est passé la conception même du Dashboard. 

Les critères à évaluer sont les suivants :
- Satisfaction avec le Travail/Style de vie
- Satisfaction avec le Salaire
- Salaire Féminin Vs Masculin
- Salaire Moyen en fonction du profile du professionnel (Scientist/Analyst/Engineer/...)
- Langage de programmation préféré

Chacun des critères a fait l'objet d'un visuels.

### CONCLUSION :
- Le Salaire des professionnels de la donnée est plus élevé au États-unis que ailleurs (soit 81,18K€ en moyenne)
- Globalement mes femmes gagnent un salaire légèrement plus élévé que ce que gagnent les hommes (soit 55,1K€ Vs 53,4K€ en moyenne)
- La plupart des professionnels préfèrent Python, mais beaucoup plus des data analyst (soit 255 d'eux sur 630), au devant de R, C/C++, Javascript mais Java en dernier
- Sur une note totale de 10 ont obtient en moyenne 5.74 de taux de satisfaction par rapport au travail et au style de vie (les hommes sont légèrement plus satisfaits que les femmes soit 5.77 Vs 5.66)
- Sur une note totale de 10 ont obtient seulement en moyenne 4.27 de taux de satisfaction par rapport au salaire ( mais en revanche, niveau salaire, les femmes sont légèrement plus satisfaits que les hommes soit 4.28 Vs 4.27)

# `Dashboard - Power BI`

![`Dashboard`](image/DashbaordPowerBI.png)
