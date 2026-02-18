# 🕌 Politique de Confidentialité – Julli

**Dernière mise à jour :** 18 février 2026  
**Développeur :** Smahn (Seydina Alhamine Ndiaye)  
**Contact :** seydinaalhaminendiaye24@gmail.com  

---

## 1. Introduction

Julli est une application mobile gratuite de rappel des horaires de prière,  
développée pour la communauté musulmane du Sénégal et de la diaspora.

Nous respectons votre vie privée et nous nous engageons à protéger vos données personnelles.

---

## 2. Données Collectées

Julli collecte uniquement les données suivantes :

### 2.1 Localisation GPS

- **Objectif :** Détecter automatiquement votre ville afin d’afficher des horaires de prière précis  
- **Fréquence :** Uniquement au premier lancement ou lors d’un changement de ville  
- **Stockage :** Stocké localement sur votre appareil (AsyncStorage)  
- **Partage :** Aucune donnée n’est partagée avec des tiers  

### 2.2 Préférences Utilisateur

- Ville sélectionnée  
- Muezzin préféré pour l’Adhan  
- Fond d’écran choisi  
- Activation ou désactivation des notifications  

👉 Ces données sont **stockées uniquement sur votre appareil** et ne sont jamais envoyées à nos serveurs.

---

## 3. Permissions Utilisées

### Android

- **INTERNET** : Récupérer les horaires de prière depuis l’API Aladhan  
- **ACCESS_FINE_LOCATION / ACCESS_COARSE_LOCATION** : Détection automatique de votre ville  
- **VIBRATE** : Vibration lors des notifications de prière  
- **SCHEDULE_EXACT_ALARM** : Planifier les rappels de prière à l’heure exacte  
- **RECEIVE_BOOT_COMPLETED** : Réactiver les notifications après redémarrage du téléphone  

### iOS

- **NSLocationWhenInUseUsageDescription** : Détection de votre ville  
- **NSUserNotificationsUsageDescription** : Rappels avant les prières  
- **UIBackgroundModes (audio)** : Lecture de l’Adhan en arrière-plan  

---

## 4. Services Tiers

Julli utilise les services suivants :

### 4.1 API Aladhan (aladhan.com)

- **Utilisation :** Calcul des horaires de prière  
- **Données envoyées :** Coordonnées GPS de votre ville (latitude / longitude)  
- **Politique de confidentialité :**  
  https://aladhan.com/privacy-policy  

### 4.2 Expo / React Native

- **Utilisation :** Framework de développement  
- **Données collectées :** Aucune donnée personnelle  

🚫 **Aucune publicité, aucun tracker, aucune analyse d’audience.**

---

## 5. Sécurité des Données

Toutes vos données sont stockées **localement sur votre appareil**.

- Aucun serveur backend  
- Aucune base de données distante  
- Aucune transmission de données personnelles  

Nous n’avons techniquement **aucun accès** à vos informations.

---

## 6. Vos Droits

Vous pouvez à tout moment :

- Refuser l’accès à la localisation  
  *(l’application utilisera Dakar par défaut)*  
- Désactiver les notifications dans les paramètres  
- Supprimer toutes vos données en désinstallant l’application  

---

## 7. Données des Enfants

Julli ne collecte sciemment aucune information personnelle auprès d’enfants de moins de 13 ans.

L’application est conçue pour être utilisée par tous les âges, sans collecte de données sensibles.

---

## 8. Modifications

Nous pouvons mettre à jour cette politique de confidentialité.

Toute modification sera publiée sur cette page avec une nouvelle date de **Dernière mise à jour**.

---

## 9. Open Source

Julli est un projet **open source**.

Le code source peut être fourni sur demande pour :
- audit de sécurité  
- transparence  
- vérification communautaire  

---

## 10. Contact

Pour toute question concernant cette politique de confidentialité :

- **Email :** seydinaalhaminendiaye24@gmail.com  
- **Développeur :** Seydina Alhamine Ndiaye (Smahn)  

---

© 2026 **Julli** – Tous droits réservés  
Application développée avec ❤️ pour la communauté musulmane du Sénégal
