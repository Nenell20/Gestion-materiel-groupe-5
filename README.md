# Compte Rendu - TP3: Gestion Materiel Groupe 5
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
---

## 1. Identification

- **Nom et Prénom :** Yannis HEBERT, Mathis RICARD, Naël MIGNET
- **Date :** Mardi 15 Septembre 2026
- **Nom du dépôt Github :** Gestion-materiel-groupe-5
- **URL du dépôt Github :** https://github.com/Nenell20/Gestion-materiel-groupe-5.git

---

## 2. Origin

### Rôle de `origin` dans `git remote add origin URL_DU_DEPOT`
Dans cette commande, **`origin`** est le nom de raccourci attribué par convention à l'adresse du dépôt distant sur GitHub. Cela évite d'avoir à ressaisir l'URL complète à chaque fois qu'on souhaite interagir avec le serveur distant (ex: `git push origin main`).

---

## 3. Les principales commandes

- **`git init`** : Initialise un nouveau dépôt Git local dans le dossier courant en créant le sous-dossier masqué `.git`.
- **`git add`** : Ajoute des modifications ou de nouveaux fichiers à la zone d'index (*staging area*) pour les préparer au prochain commit.
- **`git commit`** : Enregistre l'état actuel des fichiers indexés dans l'historique du dépôt local avec un message explicatif.
- **`git push`** : Envoie les commits enregistrés localement vers le dépôt distant (sur GitHub).
- **`git pull`** : Récupère les dernières modifications depuis le dépôt distant et les fusionne directement dans la branche locale active.
- **`git clone`** : Télécharge une copie complète d'un dépôt distant (code, branches et tout l'historique des commits) sur sa machine locale.

---

## 4. Publication du projet

### Étapes de publication initiale :
1. **Création du dépôt local :** Dans le dossier du projet contenant les fichiers (`index.html`, `style.css`, etc.), le dépôt Git local a été initialisé via la commande `git init`. Les fichiers ont ensuite été indexés (`git add .`) puis validés (`git commit -m "Initial commit"`).
2. **Association du dépôt distant :** Après avoir créé un dépôt vide nommé `Gestion-materiel-groupe-5` sur GitHub, il a été lié au dépôt local avec la commande :
   ```bash
   git remote add origin https://github.com/Nenell20/Gestion-materiel-groupe-5.git
3. **Ajout des collaborateurs** dans le dossier Github partagé, et les droit d'administrateur.
4. **Choix du projet** et répartition des rôles et activités que chacun devras faire.
5. **Travail en autonomie** sur nos tâches respectives.
6. **Partage** de nos résultat en faisant un dossier partager sur ``VisualStudioCode``, pour être plus productif.
7. **Finalisation** en équipe et vérifications
8. **Publication finale du projet**