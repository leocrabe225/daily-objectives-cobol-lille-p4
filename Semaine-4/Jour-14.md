
# Objectifs journaliers MS COBOL P4 – **Les fichiers COBOL**


### Mardi 13 Mai


- [ ] Introduire le thème de la semaine : les fichiers en COBOL
* [ ] Discuter des usages concrets des fichiers COBOL (banques, administrations, etc.)

#### Découverte des fichiers en COBOL

- [ ] Introduction à la gestion des fichiers
  - [ ] Environment Division : CONFIGURATION SECTION et INPUT-OUTPUT SECTION
  - [x] Data Division : FILE SECTION et définition d’un fichier
  - [x] Comprendre les concepts de lecture et écriture simples (OPEN, CLOSE)

---

#### **Exercice : Lecture d’un fichier texte – Liste de personnes**

Vous disposez d’un fichier texte `personnes.txt`, contenant une liste de personnes.
Chaque ligne comprend :

* Le **nom** (15 caractères)
* Le **prénom** (15 caractères)
* La **date de naissance** (8 caractères au format MMDDYYYY)

---

##### ➤ **Partie 1 – Affichage basique**

* [x] Lire le fichier ligne par ligne.
* [x] Afficher uniquement le **nom** et le **prénom** de chaque personne.

---

##### ➤ **Partie 2 – Formatage de date**

* [x] Lire et extraire la **date de naissance** de chaque personne.
* [x] Afficher cette date au **format DD/MM/YYYY**.

---

##### ➤ **Partie 3 – Recherche et calcul d’âge**

* [x] Demander à l’utilisateur de saisir un **nom**.
* [x] Rechercher la personne correspondante dans le fichier.
* [x] Afficher son **nom**, son **prénom** et son **âge** (à partir de l’année courante, 2025).

---

#### Consolidation

- [ ] Ajouter une section sur la gestion des fichiers à sa cheat sheet
- [x] Organiser ses programmes dans son repo Git et faire un push


