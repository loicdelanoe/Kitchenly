# Kitchenly 🍲

**Kitchenly** est une application mobile innovante pour la création et la gestion de listes de repas, facilitant l'organisation de vos repas hebdomadaires ou la découverte de nouvelles recettes. Avec un système de swipe inspiré de Tinder, choisissez facilement les plats que vous souhaitez ajouter à vos listes personnalisées, le tout en quelques gestes.

## Fonctionnalités principales

- **Parcourir un large choix de repas** : Grâce à l'intégration de l'API [TheMealDB](https://www.themealdb.com/), explorez un grand nombre de recettes du monde entier.
- **Création de listes de repas personnalisées** : Ajoutez et gérez vos repas favoris dans différentes listes.
- **Système de swipe intuitif** : 
  - Swipez **à droite** pour ajouter le repas à votre liste.
  - Swipez **à gauche** pour passer au repas suivant.
  - **Tapez sur la carte** pour afficher les détails complets du repas (ingrédients, instructions, etc.).
- **Compte utilisateur** : Gérez et sauvegardez vos préférences et listes de repas.
- **Ajout et suppression de repas** : Organisez facilement vos listes en ajoutant ou supprimant des repas en fonction de vos envies.

## Installation

1. **Clonez le repository** :

   ```bash
   git clone https://github.com/votre-utilisateur/kitchenly.git
   cd kitchenly
   ```

2. **Installez les dépendances** :

   ```bash
   flutter pub get
   ```

3. **Configuration de l'API** :  
   Créez un fichier `.env` à la racine du projet pour stocker la clé API de [TheMealDB](https://www.themealdb.com/).
   ```plaintext
   API_KEY=your_mealdb_api_key
   ```

4. **Lancer l'application** :

   ```bash
   flutter run
   ```

## Aperçu des fonctionnalités

### Swipe pour ajouter un repas

Kitchenly vous permet d'explorer facilement des idées de repas en swipant :
- **Swipe à droite** : Ajoute le repas à votre liste de repas.
- **Swipe à gauche** : Ignore le repas.
- **Tape** : Ouvre la fiche complète du repas, avec les informations détaillées.

### Gestion des repas et listes

- **Ajouter un repas** : Une fois sélectionné, le repas est ajouté à votre liste.
- **Supprimer un repas** : Supprimez rapidement les repas indésirables de vos listes.

### Authentification

- **Compte utilisateur** : Inscription et connexion pour sauvegarder vos listes et préférences.

## Technologies

- **Framework** : [Flutter](https://flutter.dev/)
- **Backend API** : [TheMealDB](https://www.themealdb.com/)

## Remerciements

Un grand merci à [TheMealDB](https://www.themealdb.com/) pour l'accès à leur API et leur large base de données de recettes.
