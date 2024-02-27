# IA_Music_Classification

Au cours de ce projet, nous avons développé un modèle de machine learning pour la classification des genres musicaux. Notre approche s'est basée sur une architecture hybride combinant CNN et LSTM pour traiter efficacement les caractéristiques temporelles et spatiales des signaux audio. Bien que le modèle ait montré une certaine capacité à discriminer entre différents genres, l'accuracy obtenue de 51% indique une marge significative d'amélioration.

Pour améliorer les performances du modèle, nous avons envisagé plusieurs stratégies :

Augmentation et Diversification des Données : L'intégration de davantage d'échantillons musicaux, ainsi que l'application de techniques d'augmentation des données audio, telles que le changement de vitesse et l'ajout de bruit, pour enrichir notre ensemble d'apprentissage et augmenter la robustesse du modèle.

Optimisation de l'Architecture du Modèle : Ajustement des couches et des neurones dans les couches Conv1D et LSTM, et expérimentation avec l'ajout de couches de normalisation par lots et de couches de dropout pour une meilleure généralisation.

Ajustement Fin des Hyperparamètres : Modification du taux d'apprentissage, de la taille des lots, et du nombre d'époques, en utilisant des méthodes telles que la recherche par grille ou la recherche aléatoire pour trouver la combinaison optimale.

Application de Techniques de Régularisation : Mise en œuvre de la régularisation L1/L2 et de l'early stopping pour contrer le surajustement.

Évaluation Complète : Utilisation de métriques supplémentaires comme le F1-score et la matrice de confusion pour une évaluation plus nuancée, et application de la validation croisée pour assurer la stabilité et la fiabilité du modèle.

Tout au long du projet, nous avons rencontré des défis tels que l'adaptation des données aux exigences structurelles du modèle et la gestion des fichiers audio mal lus ou corrompus. Ces défis ont été surmontés grâce à un prétraitement méticuleux des données et à une gestion robuste des exceptions lors de l'extraction des caractéristiques.

En conclusion, bien que des améliorations soient nécessaires pour atteindre une précision plus élevée, les stratégies proposées et les leçons tirées de ce projet posent les bases pour de futures itérations et optimisations du modèle.

Arthur Liot & Paolig Blan
