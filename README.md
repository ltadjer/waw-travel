# Waw.travel

## Présentation du Projet
Waw.travel est une plateforme web conçue pour les passionnés de road trips afin de partager leurs aventures avec leur famille et leurs amis. Le projet est initié par l'agence de communication "New Horizons" et vise à créer un espace communautaire baptisé "Waw" (Where Are We). La plateforme permet aux utilisateurs de créer des carnets de voyage avec plusieurs points de contrôle, et une page web publique fournit des informations détaillées sur l'ensemble du road trip.
(c'est un projet fictif)

## Mise en Route
1. **Cloner le Répertoire :**
   ```bash
   git clone https://github.com/ltadjer/waw-travel.git
   ```

2. **Configurer PHP et Tailwind CSS :**
   - Assurez-vous que PHP est installé.
   - Installez Tailwind CSS avec npm si ce n'est pas déjà fait :
     ```bash
     npm install
     ```

3. **Configuration de la Base de Données :**
   - Importez le schéma de base de données fourni à l'aide du fichier "waw_travel_Database.sql" sur PHPMyAdmin ou un outil similaire.

4. **Exécution du Projet :**
   - Configurez un serveur PHP et accédez à `http://localhost:8888/waw-travel/public/`.

## Technologies Utilisées

- **PHP :** Langage de script côté serveur. ![WordPress Plugin Required PHP Version](https://img.shields.io/wordpress/plugin/required-php/:slug)
- **Tailwind CSS :** Un framework CSS utilitaire. [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

## Fonctionnalités
- **Authentification :** Les utilisateurs peuvent s'inscrire et se connecter de manière sécurisée.
- **Gestion des Roadtrips :**
  - Créer un road trip.
  - Modifier les détails d'un road trip existant.
  - Supprimer un road trip.
  - Afficher une liste de tous les road trips.
- **Sécurité :** Mise en place d'une protection contre les vulnérabilités XSS.
- **Feedback Utilisateur :** Utilise un système de messagerie flash pour fournir des retours d'information aux utilisateurs.
