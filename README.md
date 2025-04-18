# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.

# 🎯 Objectif de l'application
L’application TripFlow permet à un utilisateur de :

- Créer un voyage personnalisé
- Ajouter des étapes (villes, lieux, activités)
- Visualiser ses étapes sur une carte
- Ajouter des photos, notes vocales ou écrites
- Préparer sa valise via une checklist
- Consulter ses voyages passés comme des souvenirs
- Partager son voyage avec d’autres (via un lien ou une invitation)
- Utiliser l’application hors-ligne en voyage
## 🧩 Fonctionnalités principales

### 1. Authentification
   Inscription / Connexion par email

### 2. Gestion des voyages
- Liste des voyages créés
- Création d’un nouveau voyage (titre, dates, image de couverture)
- Suppression d’un voyage

### 3. Étapes du voyage
**Ajout d'étapes avec :**
- Nom du lieu
- Localisation du lieu
- Date de début/fin
- Description / activité
- Modification et suppression des étapes

### 4. Carte interactive
- Affichage des étapes sur une carte
- Vue itinéraire par ordre chronologique (Optionnel)
- Zoom automatique sur les étapes (au clique sur une étape)

### 5. Journal de bord
- Ajout de texte, photos
- Et audios (optionnel)
- Journal par jour ou par étape (à votre guise)
- Export du journal en PDF où album photo (à vôtre guise)

### 6. Checklist de préparation
- Création de listes personnalisées (ex : valise, documents)
- Possibilité de cocher / décocher
- Rappels par notification locale (Optionnel)

### 7. Partage (Optionnel)
- Option de collaboration, partage d’une invitation via les reséaux, sms, etc (compagnons de voyage)
- Génération d’un lien de lecture seule à partager

### 8. Mode hors-ligne (gestion en local storage, et optionnel)
- Téléchargement des données avant le voyage
- Utilisation offline avec synchronisation au retour