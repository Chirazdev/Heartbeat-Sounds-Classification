# Détection des Maladies Cardiaques par Analyse des Sons Cardiaques
Ce projet utilise un modèle LSTM (Long Short-Term Memory) pour faciliter le dépistage précoce des maladies cardiaques en analysant et classifiant les sons cardiaques. L'objectif principal est de discriminer efficacement entre différents types de sons cardiaques et de détecter les éventuelles anomalies qui pourraient indiquer des problèmes de santé cardiaque. Ce système fournit un outil précieux aux professionnels de la santé pour un diagnostic précoce et précis.

# Phases du Projet

1. Prétraitement et Exploration des Données
Les données brutes des sons cardiaques sont prétraitées pour nettoyer les enregistrements et préparer les données pour l'analyse. Cette phase comprend la normalisation, la réduction du bruit et la segmentation des enregistrements en segments appropriés pour l'analyse ultérieure.

2. Extraction des Caractéristiques
Les caractéristiques pertinentes sont extraites à partir des segments de sons cardiaques prétraités. Cela inclut l'extraction de caractéristiques temporelles et fréquentielles significatives qui seront utilisées comme entrées pour le modèle LSTM.

3. Classification des Sons Cardiaques
Un modèle LSTM est utilisé pour classifier les sons cardiaques en catégories telles que normaux et anormaux. Le modèle est entraîné sur les caractéristiques extraites des données prétraitées et est capable de capturer les relations temporelles complexes dans les séquences de sons cardiaques.

4. Évaluation et Testing
Les performances du modèle sont évaluées à l'aide de mesures de performance standard telles que la précision, le rappel et la courbe ROC. Des tests sont effectués pour vérifier la capacité du système à détecter avec précision les signaux d'anomalie dans les sons cardiaques.
