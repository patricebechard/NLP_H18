# TP1 - Séquence de lemmes vers formes de surface

##### Objet du TP

De nombreuses chaînes de traitement des langues font intervenir des lemmes. Le lemme d'un mot est sa forme de base. Ainsi `manger` est la forme de base (le lemme) associé à la forme `mangeront`. Dans ce devoir, vous allez mesurer quelle est la perte liée à traiter des séquences de lemmes plutôt que des séquences de formes. Votre objectif est à cette fin, de réaliser un système capable de procéder à la prédiction d'une séquence de formes à partir d'une séquence de lemmes. Ce type de mapping est un problème générique que vous pouvez tenter de résoudre par une approche populaire, comme les modèles séquence à séquence (Seq2Seq). Vous pouvez également décider de produire des règles, ou tenter d'entraîner un modèle à base de features. Ceci est laissé à votre sagacité. Dans tous les cas, la note à ce TP ne dépendra que faiblement des résultats que vous allez obtenir, mais sera bien davantage corrélée à la curiosité avec laquelle vous allez étudier le problème.

