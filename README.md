# 📈 Bank Marketing UCI  
*Why did the banker break up with their partner? Because they lost interest!*

## 🧠 Contexte

Ce projet utilise le dataset **Bank Marketing** disponible sur Kaggle ([lien dataset](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset)). Ce jeu de données provient d’une banque portugaise et contient des informations issues de campagnes de marketing téléphonique visant à promouvoir la souscription de dépôts à terme.

Chaque enregistrement correspond à un client contacté, avec des variables démographiques, économiques et comportementales, ainsi que le résultat de la campagne : si le client a souscrit un dépôt à terme (`yes` ou `no`).

---

## 📊 Description du dataset

Le dataset contient plus de 40 000 exemples avec des colonnes telles que :

- `age` : âge du client  
- `job` : profession  
- `marital` : état civil  
- `education` : niveau d’études  
- `default` : s’il a un crédit en défaut  
- `housing` : prêt immobilier  
- `loan` : prêt personnel  
- `contact` : type de contact (cellulaire ou téléphone fixe)  
- `month` : mois du dernier contact  
- `duration` : durée du dernier appel (en secondes)  
- `campaign` : nombre d’appels durant cette campagne  
- `pdays` : jours écoulés depuis le dernier contact (campagnes précédentes)  
- `previous` : nombre de contacts avant cette campagne  
- `poutcome` : résultat de la campagne précédente  
- `y` : **variable cible** (a souscrit ou pas)

---

## 🤖 Objectif

Construire un modèle de classification supervisée capable de prédire si un client souscrira à un dépôt à terme.

---

## ⚙️ Méthodologie & PyCaret

Nous avons automatisé le processus de Machine Learning avec PyCaret, qui permet :

- Prétraitement automatique  
- Sélection et entraînement de plusieurs modèles  
- Comparaison des performances (métrique Accuracy)  
- Sélection du meilleur modèle

---

## 🧪 Étapes principales

1. Chargement et nettoyage des données  
2. Analyse exploratoire (EDA)  
3. Préparation des variables (encodage, gestion des valeurs manquantes)  
4. Mise en place de PyCaret pour classification  
5. Entraînement et comparaison automatique des modèles  
6. Analyse des résultats, choix du meilleur modèle  
7. Interprétation

---

## 📚 Concepts appris

- Apprentissage supervisé et classification  
- Importance du prétraitement  
- Evaluation par accuracy  
- Utilisation d’AutoML pour accélérer la modélisation

---

## 📁 Structure du repo

- `notebook_exploration.ipynb` : nettoyage, EDA  
- `notebook_modelisation.ipynb` : modélisation avec PyCaret  
- `README.md` : ce fichier  
- `/data/` : fichiers dataset (fournis par Kaggle)

---

## ✅ Résultats

Meilleur modèle identifié : **[À compléter selon résultat PyCaret]**  
Accuracy obtenue : **[À compléter]**

---

## 💡 Conclusion

Le projet démontre comment un outil AutoML permet de construire rapidement un modèle performant pour prédire la souscription d’un dépôt, utile pour optimiser les campagnes marketing.


