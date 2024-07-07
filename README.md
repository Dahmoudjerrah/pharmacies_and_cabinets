Projet Mauritania Healthcare Locator
Ce projet est une application web conçue pour aider les utilisateurs à trouver les pharmacies,
pharmacies de garde et cabinets de santé les plus proches en Mauritanie.
En utilisant des données de géolocalisation et des API provenant d'un autre projet backend,
l'application affiche les emplacements triés par proximité avec l'utilisateur et permet de filtrer par
régions administratives (Willayas) et districts (Moughataas). 
Les emplacements sont également représentés sur une carte interactive.

Fonctionnalités
Recherche basée sur la géolocalisation : Détecte automatiquement l'emplacement de l'utilisateur
et affiche les cabinets et pharmacies les plus proches.
Options de filtrage : Les utilisateurs peuvent filtrer les résultats par Willaya et Moughataa.
Carte interactive : Affiche les emplacements sur une carte Google avec des marqueurs et fournit des directions.
Pagination : Permet de naviguer à travers plusieurs pages de résultats.
Design responsive : Assure une utilisation sur différents appareils, y compris les ordinateurs de bureau et les mobiles.
Technologies Utilisées
EJS : Moteur de template pour le rendu du contenu dynamique.
HTML5 & CSS3 : Structure et stylisation des pages web.
Tailwind CSS : Framework CSS basé sur l'utilitaire pour la stylisation.
JavaScript : Interactivité côté client.
API Google Maps : Intégration pour l'affichage des cartes et la fourniture de directions.
Comment exécuter le projet
Clonez le dépôt :
git clone https://github.com/Dahmoudjerrah/pharmacies_and_cabinets.git
Accédez au répertoire du projet :
cd pharmacies_and_cabinets
Installez les dépendances :
npm install
Démarrez le serveur (uniquement pour servir le projet frontend) :
node src/app.js
Ouvrez votre navigateur et accédez à :
http://localhost:3001
