# TP – Support Vector Machine (SVM)

**Auteur :**  
- Lucine Bonnefont

---

## Sujet du TP
Ce TP porte sur l’utilisation des Support Vector Machines (SVM) pour la classification.
Il vise à mettre en pratique différents aspects théoriques et pratiques :  
- Classification binaire sur des données simples,  
- Influence du noyau (linéaire, polynomial),  
- Impact du paramètre de régularisation C.

---

## Contenu du dépôt
- `TP_ML_SVM.pdf` : énoncé complet du TP fourni par les enseignants.
- `rendu/TP1.qmd` : fichier Quarto utilisé pour générer le compte rendu.
- `rendu/TP1.pdf` : compte rendu final.
- `code/svm_script.py` : code fourni à compléter.  
- `code/svm_source.py` : code source des fonctions utilisées.  
- `code/svm_gui.py` : script permettant de générer un jeu de données déséquilibré et de visualiser l’effet des paramètres.  
  

---

## Compilation
Le fichier **`TP1.pdf`** est déjà fourni.  
Si vous souhaitez regénérer le document à partir du `.qmd`, voici la démarche à suivre:  

1. Installer [Quarto](https://quarto.org/). 
2. Rendez vous dans le dossier du fichier à générer :  `cd rendu`
3. Exécuter la commande suivante dans votre terminal: `quarto render TP1.qmd`