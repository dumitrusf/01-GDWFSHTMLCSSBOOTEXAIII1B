
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Système de gestion du zoo Arcadia

Un système moderne pour gérer les animaux, les habitats, la nutrition et les rapports dans les zoos. Conçu avec PHP, MariaDB et MongoDB.

[Documentation du projet](https://github.com/dumitrusf/zoo-arcadia/wiki) · [Signaler une erreur](https://github.com/dumitrusf/zoo-arcadia/issues) · [Suggérer une fonctionnalité](https://github.com/dumitrusf/zoo-arcadia/issues)

## Table des matières

- [Système de gestion du zoo Arcadia](#système-de-gestion-du-zoo-arcadia)
- [Caractéristiques principales](#caractéristiques-principales)
  - [Captures d'écran](#captures-décran)
- [Commencer](#commencer)
  - [Prérequis](#prérequis)
  - [Installation](#installation)
- [Contribuer](#contribuer)
- [Stack technologique](#stack-technologique)
- [Licence](#licence)

## Caractéristiques principales

- **Gestion des animaux**: Enregistrement des données, nutrition, état de santé et habitats.
- **Rôles des utilisateurs**: Gestion des rôles (vétérinaires, administrateurs, employés).
- **Conception responsive**: Interface mobile-first.
- **Logs alimentaires et rapports**: Suivi de l'alimentation et de la santé des animaux.

### Captures d'écran

![home](https://onedrive.live.com/embed?cid=2C3D1E2234649594&resId=2C3D1E2234649594!261527&authkey=!AIVvtn2jueg-iSM&ithint=photo&e=TwLXIR)

## Commencer

### Prérequis

- **Apache**: Serveur Web (installé dans `C:/apache`).
- **PHP**: Version 8.x (installé dans `C:/php`).
- **Node.js**: Version 16.x ou supérieure.
- **MariaDB**: Base de données relationnelle.
- **MongoDB**: Base de données non relationnelle.

### Installation

1. **Cloner le repository**:
   ```bash
   git clone https://github.com/dumitrusf/zoo-arcadia.git
   cd zoo-arcadia
   ```

2. **Configurer Apache et PHP**:

   Cloner le repository php-apache-for-arcadia et déplacer les fichiers dans `C:/`.

   - Modifier `httpd.conf` pour pointer vers `C:/apache/htdocs/zoo-arcadia/public`.
   (déjà fait)

   - Éditer `php.ini` pour permettre les extensions nécessaires:
     ```ini
     extension=mysqli
     extension=pdo_mysql
     ```

3. **Configurer les bases de données**:
   ```bash
   mysql -u root -p zoo_arcadia < database/2025_01_19_tables.sql
   mysql -u root -p zoo_arcadia < database/2025_01_19_constraints.sql
   mysql -u root -p zoo_arcadia < database/2025_01_19_init.sql
   ```

4. **Installer les dépendances frontend**:
   ```bash
   npm install
   npm run css
   ```

## Contribuer

Les contributions sont bienvenues. Suivez les étapes suivantes :

1. Faire un fork du projet.

2. Cloner votre fork :
   ```bash
   git clone https://github.com/dumitrusf/zoo-arcadia/fork
   ```

3. Créer une branche pour vos modifications :
   ```bash
   git checkout -b feature/nouvelle-fonctionnalité
   ```

4. Faire vos modifications et les committer :
   ```bash
   git commit -m "feat: ajouter une nouvelle fonctionnalité"
   ```

5. Pousser vos modifications vers votre branche :
   ```bash
   git push origin feature/nouvelle-fonctionnalité
   ```

6. Ouvrir un pull *[pull request](https://github.com/dumitrusf/zoo-arcadia/pulls)*.

## Stack technologique

- **PHP**: Logique du serveur.
- **MariaDB**: Base de données relationnelle.
- **MongoDB**: Base de données non relationnelle.
- **Bootstrap**: Framework CSS/JS.
- **SCSS**: Préprocesseur CSS.
- **Node.js et Gulp**: Automatisation frontend.

## Licence

Distribué sous la licence MIT. Consultez le fichier LICENSE pour plus d'informations.
