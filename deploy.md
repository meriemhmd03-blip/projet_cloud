# Rapport de déploiement - [HAMDADA MERIEM]

## Liens

- **Application en ligne :** [https://projetcloud.osc-fr1.scalingo.io]
- **Dépôt de code :** [https://github.com/meriemhmd03-blip/projet_cloud.git]

## Prérequis techniques

-PHP 8.4+ avec l'extension pdo_msql
-Composer installé
-Un compte Scalingo

## Fichier de configuration CI

-Versioning sur GitHub : Création d'un dépôt public sur le compte GitHub et poussez le code local.

-Configuration d'un fichier ci.yml et placement dans le dossier .gitHub/workflows
Commit & Push de ce fichier sur GitHub.
Le fichier de configuration de l'intégration continue se trouve dans : .github/workflows/ci.yaml

## Procédure de déploiement pas à pas

A. Initialisation sur Scalingo
1.Création de l'application projetcloud (Create an application)

B. Ajout des variables d'environnement sur Scalingo APP_ENV=prod et APP_SECRET récupéré en copiant la valeur "php -r "echo bin2hex(random_bytes(16));" sur le terminal vscode

Puis Commit des changement : git commit -m "Déploiement"

C. Mise en ligne : Push des commits avec git push
