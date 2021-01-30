# Projet Accidents de voiture
# Introduction
Ce projet se base sur les données des accidents s'étant produit en France de 2005 à 2016. A partir de ce jeu de données nous avons répondu à plusieurs questions que nous nous sommes posés en réalisant des algorithmes de clustering ainsi qu'en recherchant des motifs fréquents. 

Vous trouverez notre rapport expliquant tout ce que nous avons réalisé lors de ce projet. 

Ce projet a été réalisé par :
* BAMBA William
* CHUPIN Pierre-Henri
* HOSSAIN Shajjad
* JASSINEUX Marie
* SOLOMON Maria
* TREGER Pauline

# Lancer les algorithmes de clustering
La première partie de notre projet consiste à utiliser des algorithmes de clustering.

#### Pré-requis
Ces algorithmes ont été réalisé à l'aide du logiciel KNIME.  
Pour lancer les différentes parties de clustering de ce projet, il faut donc au préalable avoir téléchargé le logiciel KNIME.  
Téléchargez les 6 jeux de données, utilisés dans nos algorithmes, se trouvent [ici](https://www.kaggle.com/shstars/pretraitement-geo-dm/data). Ces données sont celles que nous avons créé à l'aide de notre pré-traitement.  

#### Exécution dans KNIME
Une fois que vous avez téléchargé KNIME et les 6 fichiers csv, vous pourrez lancer tous nos algorithmes de clustering se trouvant dans le dossier "Cluster" dans KNIME.  
Lorsque vous ouvrez un de nos algorithmes dans KNIME, il faudra charger dans chaque noeud "File Reader" le fichier csv correspondant. Lors du chargement de chaque fichier, dans la Preview du noeud "File Reader", il faudra changer le type de la colonne "Num_Acc" en la mettant en type String.  
Une fois tous les fichiers correctement chargés, vous pourrez exécuter tous les noeuds dans KNIME.  
  
  
# Lancer la recherche de motifs fréquents
La deuxième partie de notre projet consiste à utiliser des algorithmes de recherche de motifs fréquents.

#### Pré-requis
Nous avons réalisé la recherche de motifs fréquents à l'aide du langage de programmation Python et ses librairies.  
Afin de pouvoir lancer notre code, il vous faut donc installer Python et les librairies `mlxtend` et `pandas`, ainsi qu'un logiciel pouvant lire des NoteBook Python.  
Téléchargez les données se trouvant [ici](https://www.kaggle.com/dataset/49ae342a734271e08724f10b9ecfb73a936ed9f05bd3061fb1ea50bfef14d25f), téléchargez le fichier et placez le dans le dossier "frequent_patterns".

#### Exécution du code
Une fois toutes ces installations réalisées, vous pourrez ouvrir et exécuter notre NoteBook Python "frequent_item.ipynb" se trouvant dans le dossier " frequent_patterns".