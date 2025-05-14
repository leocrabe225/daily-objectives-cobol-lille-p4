# Objectifs journaliers MS COBOL P4


### Mercredi 14 Mai


#### 📌 Introduction aux **fichiers séquentiels**

* [x] Comprendre la clause `SELECT` dans l’`ENVIRONMENT DIVISION`
  * [x] `ASSIGN TO` + nom du fichier réel
  * [x] `ORGANIZATION IS SEQUENTIAL`
* [x] Étudier la section `FILE-CONTROL` et la déclaration `FD` dans `DATA DIVISION`
* [x] Découvrir les commandes :

  * [x] `OPEN INPUT/OUTPUT/EXTEND`
  * [x] `READ` avec clause `AT END`
  * [x] `WRITE`

#### 📌 Structure et déclaration des enregistrements

* [x] Comprendre comment déclarer un enregistrement lié au fichier
* [x] Relier chaque champ COBOL à une colonne du fichier texte

---

### Gestion de son apprentissage

* [ ] Ajouter une section « fichiers séquentiels » dans sa cheat sheet
* [ ] Documenter les commandes `OPEN`, `READ`, `WRITE`, `AT END`

---

* [x] Présenter un des programmes utilisant les fichiers séquentiels
* [x] Faire un retour rapide sur les notions de `AT END` et structure d’enregistrement

#### 📌 Manipulation avancée des **fichiers séquentiels**

* [x] Lire un fichier en boucle, filtrer des données, écrire un nouveau fichier
* [x] Gérer les fichiers d’entrée ET de sortie dans un seul programme
* [x] Simuler la mise à jour d’un fichier séquentiel avec un fichier temporaire

#### 📌 Fichiers d’entrée multiples

* [x] Étudier un programme lisant 2 fichiers (clients + commandes)
* [x] Importance de synchroniser les fichiers (triés par ID ? )

---

### Exercices pratiques

* [x] Lire un fichier d'élèves `eleves.txt` (`Nom`, `Note`) et créer un fichier `reussite.txt` avec uniquement les élèves ayant plus de 10
* [x] Lire un fichier `inventaire.txt`, extraire les articles en rupture (`STOCK = 0`) et les écrire dans `rupture.txt`
* [x] Lire 2 fichiers (`clients.txt`, `commandes.txt`) et afficher les commandes par client (assume ID client commun)
* [x] Écrire un programme qui copie un fichier `compte-rendu.txt` ligne par ligne, en ignorant les lignes vides

---

### Gestion de son apprentissage

* [ ] Ajouter un schéma des interactions entre fichiers d’entrée/sortie
* [ ] Documenter la gestion des fichiers temporaires pour la mise à jour

---
