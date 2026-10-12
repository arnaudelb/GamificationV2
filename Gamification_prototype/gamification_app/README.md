# Gamification — prototype personnel

## Tester sur ordinateur
Ouvre `index.html` dans un navigateur récent. Les données sont conservées dans le stockage local du navigateur.

## Installer sur téléphone
Pour l'installation PWA et le mode hors-ligne, héberge ce dossier sur un site HTTPS, puis ouvre l'adresse sur le téléphone et choisis « Ajouter à l'écran d'accueil ». Le simple fichier local permet de tester les fonctionnalités, mais pas l'installation PWA.

## Fonctions incluses
- Accueil avec l'image fournie.
- Swipe vers la droite pour CLEAN et vers la gauche pour ÉCHEC sur chaque Red Flag.
- Validation manuelle de la journée.
- Progression, paliers de récompense, tâches bonus et boutique.
- Détection de validation oubliée à l'ouverture et périodiquement lorsque l'application est ouverte.
- Personnalisation des Red Flags, tâches bonus et récompenses.
- Export/import JSON.

## Limites du prototype
Un navigateur ne peut pas exécuter un contrôle en arrière-plan fiable quand l'application est fermée. Un échec oublié est donc détecté à la prochaine ouverture, ou au prochain contrôle si l'application reste ouverte. Les notifications exactes à 11 h 15 nécessiteraient des notifications système et une configuration supplémentaire.

Les données restent locales au navigateur/appareil et ne sont pas synchronisées. Exporter régulièrement une sauvegarde depuis Options.
