
# Semaine 2 : Apprendre Git et GitHub - Premiers pas vers le travail collaboratif

Cette semaine, vous allez découvrir **Git** et **GitHub**, des outils essentiels pour le contrôle de version et la collaboration en développement web. Votre mission est de cloner un projet existant, créer une nouvelle branche, ajouter des modifications, et soumettre une **pull request**. Suivez les étapes ci-dessous pour accomplir cette tâche.

---

## Objectifs de la semaine

1. **Comprendre les bases de Git** : Initialiser un dépôt, créer des commits, et gérer des branches.
2. **Découvrir GitHub** : Pousser du code vers un dépôt distant et collaborer via des pull requests.
3. **Pratiquer le travail collaboratif** : Contribuer à un projet en suivant un workflow Git/GitHub standard.

---

## Étapes à suivre

### 1. Installer Git (si ce n'est pas déjà fait)

- Téléchargez et installez Git depuis [git-scm.com](https://git-scm.com/).
- Vérifiez l'installation en exécutant la commande suivante dans un terminal :

  ```bash
  git --version
  
  ```

- Configurez Git avec votre nom et votre e-mail :
  ```
  git config --global user.name "Votre Nom"
  git config --global user.email "votre@email.com"
  ```
  
 ### 2. Cloner le projet de la semaine 1
 
- Allez sur le dépôt GitHub du projet de la semaine 1.
- Cliquez sur le bouton "Code" et copiez l'URL du dépôt (au format HTTPS).
- Ouvrez un terminal et exécutez la commande suivante pour cloner le projet :
```
git clone <URL-du-dépôt>
```
Remplacez <URL-du-dépôt> par l'URL que vous avez copiée.

- Accédez au dossier du projet :
  ```
  cd nom-du-dossier
  ```

### 3. Créer une nouvelle branche

- Créez une nouvelle branche pour vos modifications. Par exemple :
  ```
  git branch ajout-formulaire-contact
  ```
- Basculez sur cette branche :
  ```
  git checkout ajout-formulaire-contact
  ```
  **Astuce** : Vous pouvez combiner la création et le changement de branche en une seule commande :
  ```
  git checkout -b ajout-formulaire-contact
  ```

### 4. Ajouter des modifications au projet

- Ouvrez le projet dans votre éditeur de code (VS Code, Sublime Text, etc.).
- Dans le dossier **semaine2** ajouter un nouveau fichier **index.html**
- Dans ce fichier ajouter des nouvelles fonctionnalités. Voici quelques idées :
  - Un formulaire de contact dans la section "Contact".
  - Une nouvelle section "Services" avec une liste de services proposés.
  - Un tableau contenant des tarifs des services offerts
- Enregistrez vos modifications.

### 5.  Valider vos modifications avec Git

- Ajoutez les fichiers modifiés à l'index :
  ```
  git add .
  ```
  **Astuce** : Vous pouvez ajouter des fichiers spécifiques en remplaçant . par le nom du fichier.
- Créez un commit avec un message descriptif :
  ```
  git commit -m "Ajout d'un formulaire de contact"
  ```

### 6. Pousser la branche sur GitHub

- Poussez votre branche vers le dépôt distant :
  ```
  git push origin ajout-formulaire-contact
  ```
  **Remarque** : Si c'est la première fois que vous poussez cette branche, Git vous demandera de définir un upstream. Suivez les instructions fournies.
  

### 7. Demander une pull request

- Allez sur le dépôt GitHub du projet.
- Vous verrez une notification pour créer une pull request à partir de votre branche.
- Cliquez sur "Compare & pull request".
- Rédigez une description claire de vos modifications :
  - Expliquez ce que vous avez ajouté ou modifié.
  - Mentionnez pourquoi ces modifications sont utiles.
- Soumettez la pull request.

## Résultat attendu

À la fin de cette semaine, vous aurez :

- Cloné un dépôt GitHub.
- Créé une nouvelle branche et ajouté des modifications.
- Poussé vos modifications vers GitHub.
- Soumis une pull request pour collaborer sur le projet.

