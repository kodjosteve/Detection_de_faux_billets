# Réalisation d'un algorithme de détection de faux billets
Le projet de réaliser un algorithme qui détecte des faux billets de banque à partir de leurs dimensions.
## Sommaire
 **Partie 1 : Introduction**
 - 1.1 Contexte
 - 1.2 Objectifs
  
**Partie 2 : Résultats**
 - Conception et testing de l'algorithme
 
# <u> Partie 1 : Introduction</u>

## <u>1.1 Contexte</u>
![](https://github.com/kodjosteve/Detection_de_faux_billets/blob/main/Donn%C3%A9es%20d'entr%C3%A9e/Logo_ONCFM.png)
 <br><br>Vous êtes consultant Data Analyst dans une entreprise spécialisée dans la data. Votre entreprise a décroché une prestation en régie au sein de l’Organisation nationale de lutte contre le faux-monnayage (ONCFM).
 <br>Cette institution a pour objectif de mettre en place des méthodes d’identification des contrefaçons des billets en euros. Ils font donc appel à vous, spécialiste de la data, pour mettre en place une modélisation qui serait capable d’identifier automatiquement les vrais des faux billets. Et ce à partir simplement de certaines dimensions du billet et des éléments qui le composent.
<br> Les données sont des fichiers csv fournis par l'entreprise.

## <u>1.2 Objectifs</u>
Les objectifs visés par ce projet sont les suivants : <br>
 - Réaliser une analyse prédictive
 - Réaliser une régression linéaire et une régression logistique
 - Opérer des classifications automatiques pour partitionner les données

# <u> Partie 2 : Résultats</u>

## <u>Conception et testing de l'algorithme</u>
Le Jupyter Notebook contenant la conception de l'algorithme et les résultats est disponible [ici](https://github.com/kodjosteve/Detection_de_faux_billets/blob/main/Algorithme_detection_faux_billets.ipynb).<br>
La capture d'écran ci-dessous présente les résultats de l'analyse :<br><br>
#### Distributions des variables <br>
![](https://github.com/kodjosteve/Detection_de_faux_billets/blob/main/R%C3%A9sultats/distributions_variables.png)
#### Matrice de confusion <br>
![](https://github.com/kodjosteve/Detection_de_faux_billets/blob/main/R%C3%A9sultats/matrice_de_confusion.png)
#### Résultats de tests <br>
![](https://github.com/kodjosteve/Detection_de_faux_billets/blob/main/R%C3%A9sultats/resultats_test_de_billets.png)
