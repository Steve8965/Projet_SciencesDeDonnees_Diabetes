# Projet : Prédiction du risque de diabète

**Auteur : Orly Steve Ngayap Tchouamdjou**

**Programme : Certificat en sciences de données - TÉLUQ**

### Contenu du dépôt: 
Ce dépôt contient tous les documents liés au projet complet en sciences de données :

### 1. Projet Final
- SCI1402_Plan du Projet.pdf
- ProjetFinal_OrlySteve_NgayapTchouamdjou.pdf

### 2. Modèle final
Modèle_Final_Random_Forest.rds (Modèle retenu après comparaison des performances.)

### 3. Code RMarkdown
- SCI1402_Projet en sciences de données_NgayapTchouamdjou_OrlySteve.Rmd
- SCI1402_Projet en sciences de données_NgayapTchouamdjou_OrlySteve.html

### 4. Dossier Data

Contient :

- diabetes_prediction_dataset.csv (jeu de données initial)

- diabetes_clean.csv (jeu de données nettoyé)

### 5. Images du projet
Images_ProjetSciencesDeDonnees/(Contient les courbes ROC, matrices de confusion, comparaisons des modèles, etc.)

**Objectif du projet**: Construire un modèle prédictif fiable permettant d’estimer le risque de diabète à partir de variables biométriques et comportementales, en comparant plusieurs techniques d’apprentissage automatique.

**Modèle choisi**: Le **Random Forest** a été sélectionné pour ses performances supérieures en termes de AUC, F1-score, sensibilité, Robustesse et stabilité.

**Reproduction du modèle:**

```r
modele <- readRDS("Modèle_Final_Random_Forest.rds")
```

## Contact
**Orly Steve Ngayap Tchouamdjou**

Projet réalisé dans le cadre du cours **SCI1402 - TÉLUQ**

**Courriel:** ngayap_tchouamdjou.orly_steve@univ.teluq.ca | sngayap50@gmail.com
