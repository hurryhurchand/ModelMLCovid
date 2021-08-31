# ModelMLCovid

## Objectif

Développer une approche ML, qui utilise des données médicales antécédentes d'un  patient pour prédire une éventuelle admission aux soins intensifs.

## Type de problème:
Supervisé
Classification

## Les défis et les approches:

1. Dataset non-équilibré 
    Solutions : 
    (a) Utilisation d'une technique de undersampling
2. Nombreuses valeurs manquantes
    (b) Imputation des valeurs avec la technique KNN
3. Absence d'un expert du domaine pour conseillé sur la pertinence des descripteurs et sélection des features
    (c) Utilisation de Crammer's V pour déterminer des variables à forte corrélations
    (d) Utilisation de Random Forest pour identifier des features pertinents

## Résultat:

1. Nous avons développés des modèles ML qui prédisent avec une moyenne be 90% l'éventualité de l'admission d'un patient en ICU
2. Nous avons utilisés les modèles suivants

    (a) KNN
    (b) Régression logistique
    (c) Decision Tree
    (d) Random Forest
    (e) Réseau de neuronne
    (f) SVM

