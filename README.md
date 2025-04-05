# Disease-prediction

## Contexte 

Réaliser un projet avec de Machine learning avec Pyspark c'est à dire de mettre en place un modèle qui va permettre de réaliser des prédictions.

## 🎯 Objectif 
L’objectif de ce projet est de prédire la présence d’une maladie cardiovasculaire à partir de variables cliniques et biologiques, à l’aide de données médicales de patients.

### Analyse exploratoire 

L’analyse permet d’identifier les patients les plus à risque, même si certains peuvent être asymptomatiques.

L’usage de ces variables permet d’aider à la décision médicale préventive.

*Conclusions clés*: 

- L’âge est un facteur clair de risque
- Pression plus élevée chez les malades
- Légèrement plus élevé chez les malades
- Sex : Les hommes sont beaucoup plus à risque que les femmes.
- Angina: Les patients asymptomatiques sont souvent malades, ce qui est critique pour la détection précoce.
- Glycémie: Pas très discriminante dans ce dataset

 Ces différences renforcent la pertinence de ces variables pour la modélisation

### Machine Learning
Après préparation des données et entraînement d’un modèle de classification (régression logistique , voici les principaux résultats obtenus sur les données de test :


✅ Performances globales du modèle **régression logistique**

| Métrique   | Valeur   |
|------------|----------|
| Accuracy   | 83.91 %  |
| Precision  | 83.72 %  |
| Recall     | 83.72 %  |
| F1-score   | 83.91 %  |


🔲 Matrice de confusion

|                     | Prédit 0 | Prédit 1 |
|--------------------:|---------:|---------:|
| **Réel 0 (sain)**   |   36     |    7     |
| **Réel 1 (malade)** |   7      |   37     |


 **Interprétation**
 
Le modèle atteint une précision de 84 %, ce qui montre une bonne performance globale.

Il est équilibré : il détecte bien à la fois les patients malades et non malades.

Le recall de 83.72 % indique qu’il détecte correctement la majorité des patients à risque, ce qui est essentiel dans un contexte médical.

La précision élevée permet de limiter les faux positifs, donc d’éviter de diagnostiquer à tort des patients sains.

Le F1-score confirme un bon compromis entre précision et rappel.


## 👨‍💻 Auteurs 

**AFOLABI Nazifou**

- **Datascientist | Machine Learning & Modeling** 
- Passionné par les sciences de données et l'intelligence artificielle.
- **Email** : [afolabinazif96@gmail.com](mailto.afolabinazif96@gmail.com)
- **LinkedIn** : [Nazifou AFOLABI](https://www.linkedin.com/in/nazifou-afolabi-10544729b/)

