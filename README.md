# IncomePredictionModel
Création d’un modèle prédictif pour estimer le revenu potentiel des individus à partir de variables explicatives telles que le revenu moyen par pays, l'indice de Gini et la classe de revenu des parents. Ce projet vise à aider une banque à cibler des clients potentiels à haut revenu.

## Description
Ce projet a pour objectif de prédire le revenu potentiel des individus afin d’aider une banque à identifier les clients les plus prometteurs en termes de futurs hauts revenus. Le modèle repose sur des données mondiales et intègre des variables explicatives comme le revenu moyen par pays, l’indice de Gini et la classe de revenu des parents.

## Contenu du projet
1. **Données utilisées** :  
   - **World Distribution Income** : base de données contenant les quantiles de revenu pour 116 pays.  
   - **Population par pays** : données issues de la Banque Mondiale.  
   - **Indice de Gini** : mesure des inégalités de revenus pour chaque pays.  

2. **Analyse exploratoire** :  
   - Visualisation des distributions de revenu et des indices de Gini par pays.  
   - Sélection de pays représentatifs via clustering (K-means).  
   - Étude des inégalités grâce aux courbes de Lorenz.  

3. **Modélisation** :  
   - Modèles testés : ANOVA et régressions linéaires multiples.  
   - Meilleur modèle retenu : régression linéaire avec transformation logarithmique des revenus.  
   - Variables explicatives principales : revenu moyen (log), indice de Gini, classe de revenu des parents.  

4. **Résultats** :  
   - Modèle final explique 72,4 % de la variance du revenu individuel.  
   - Analyse des impacts des variables sur la prédiction et recommandations pour améliorer la qualité du modèle.  

## Technologies utilisées
- **Python** : pandas, scikit-learn, statsmodels, seaborn, matplotlib.  
- **Modélisation statistique** : ANOVA, régressions linéaires multiples.  

## Prochaines étapes
- Ajouter d'autres variables explicatives pour augmenter la variance expliquée.  
- Étendre l’analyse à plus de pays ou périodes historiques pour une meilleure généralisation.  

