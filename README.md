# RNAclassification
L’objectif de base de ce projet était l’implantation de modèles de classification des séquences ARN pour
que par la suite appliquer l’un de ces modèles sur un génome et déterminer quelles sont les parties de ce
génome qui sont des séquences ARN. Dans ce projet, on applique deux méthodes de classifications:
- la première basée sur les motifs, où on essaie de trouver les motifs imoprtants pour classifier les séquences d'ARN
- la deuxième basée sur le modèle LSTM qui travail avec les données brut et essaie à partir du concept des réseux de neurones récurrents de trouver ce qui caractérise chaque séquence pour prédire sa famille.

La base de données se trouve dans le fichier data.zip. Veuillez le décompresser et maintenir le nom du dossier décompressé "data" pour préserver les chemins de fichiers qui se trouvent dans les fichiers jupyter. 
Vous trouverez dans le dossier resultats des fichiers générés représentant quelques résultats de la méthode de classification par motifs (comme les motifs importants trouvés).
