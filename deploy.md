# Rapport de déploiement - [HAMDADA MERIEM]

## Liens

- **Application en ligne :** [https://projetcloud.osc-fr1.scalingo.io]
- **Dépôt de code :** [https://github.com/meriemhmd03-blip/projet_cloud.git]

## Prérequis techniques

PHP 8.4+
avec l'extension pdo_msql
Composer installé
Un compte
Scalingo

## Fichier de configuration CI

Le fichier de configuration de l'intégration continue se trouve dans : .github/workflows/ci.yaml

## Procédure de déploiement pas à pas

A. Initialisation sur Scalingo
1.Création de l'application

B. Ajoute des variables d'environnement sur Scalingo APP_ENV et APP_SECRET
Commit des changement
git commit -m "Déploiement"

C. Mise en ligne
1.Push des commits :git push
