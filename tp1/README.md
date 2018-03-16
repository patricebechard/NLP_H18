# TP1 - Séquence de lemmes vers formes de surface

*Texte tiré en partie de l'énoncé du devoir disponible [en ligne](http://www-labs.iro.umontreal.ca/~felipe/IFT6285-Hiver2018/frontal.php?page=devoir1.html)*

##### Objet du TP

De nombreuses chaînes de traitement des langues font intervenir des lemmes. Le lemme d'un mot est sa forme de base. Ainsi `manger` est la forme de base (le lemme) associé à la forme `mangeront`. Dans ce devoir, vous allez mesurer quelle est la perte liée à traiter des séquences de lemmes plutôt que des séquences de formes. Votre objectif est à cette fin, de réaliser un système capable de procéder à la prédiction d'une séquence de formes à partir d'une séquence de lemmes. 

##### Rapport

Le rapport final (anglais) est présenté dans le fichier *IFT6285-patricebechard.pdf*

##### Code source

Le code source est écrit en Python 3.6 et est présenté sous format jupyter notebook dans le fichier *IFT6285-patricebechard.ipynb*

##### Données

L'ensemble des données sont tirées de Wikipedia. Elles sont divisées en trois parties (train, dev, test) et sont disponibles dans le fichier *wikipedia_data*