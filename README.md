# Kitchenly 🍲

**Kitchenly** est une application mobile innovante pour la création et la gestion de listes de repas, facilitant l'organisation de vos repas hebdomadaires ou la découverte de nouvelles recettes. Avec un système de swipe inspiré de Tinder, choisissez facilement les plats que vous souhaitez ajouter à vos listes personnalisées, le tout en quelques gestes.

## 📂 Structure du dépôt

### Dossiers principaux à la racine :

À Faire

## 🌟 Présentation de Kitchenly

### Besoin :
Organiser ses repas peut être une tâche fastidieuse. Kitchenly vous propose une solution simple pour explorer des recettes, créer des listes de repas personnalisées et découvrir de nouvelles idées culinaires.

**Pourquoi Kitchenly ?**
- Simplifier la création de menus.
- Rendre l'exploration de recettes ludique grâce au système de swipe.
- Centraliser la gestion des repas.

## ⚙️ Fonctionnalités

- **Parcourir un large choix de repas** : Grâce à l'intégration de l'API [TheMealDB](https://www.themealdb.com/), explorez un grand nombre de recettes du monde entier.
- **Création de listes de repas personnalisées** : Ajoutez et gérez vos repas favoris dans différentes listes.
- **Système de swipe intuitif** :
    - Swipez **à droite** pour ajouter le repas à votre liste.
    - Swipez **à gauche** pour passer au repas suivant.
    - **Tapez sur la carte** pour afficher les détails complets du repas (ingrédients, instructions, etc.).
- **Compte utilisateur** : Gérez et sauvegardez vos préférences et listes de repas.
- **Ajout et suppression de repas** : Organisez facilement vos listes en ajoutant ou supprimant des repas en fonction de vos envies.

## 🔍 Étude de l'existant

| Application     | Points forts                                   | Points faibles                              |
|-----------------|------------------------------------------------|---------------------------------------------|
| Jow             | Interface intuitive, gestion des courses       | Peu flexible pour les listes personnalisées |
| Mealime         | Suggestions basées sur les préférences          | Peu ludique                                 |
| Whisk           | Intégration avec listes de courses             | Interface complexe                          |

## 🎯 Public cible

### Persona :

À Faire

## 📖 User Stories et maquettes

À Faire

## 🔧 Guide pour les développeurs

### Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/kitchenly.git
   cd kitchenly
   ```

2. Installez les dépendances :
   ```bash
   flutter pub get
   ```

3. Configurez l’API :
   - Créez un fichier `.env` dans le dossier `lib/` contenant :
     ```env
     API_KEY=your_mealdb_api_key
     ```

4. Lancez l’application :
   ```bash
   flutter run
   ```
