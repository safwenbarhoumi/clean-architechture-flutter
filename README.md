# Flutter Clean Architecture Project
[![Flutter CI/CD](https://github.com/safwenbarhoumi/clean-architechture-flutter/actions/workflows/main.yml/badge.svg)](https://github.com/safwenbarhoumi/clean-architechture-flutter/actions/workflows/main.yml)

Ce repository contient un projet Flutter structuré selon les principes de **Clean Architecture**, qui favorise la séparation des responsabilités et la maintenabilité du code.

## 📋 Table des Matières
- [À propos du projet](#-à-propos-du-projet)
- [Structure du projet](#-structure-du-projet)
- [Prérequis](#-prérequis)
- [Installation](#-installation)
- [Fonctionnalités](#-fonctionnalités)
- [Ressources utiles](#-ressources-utiles)
- [Auteur](#-auteur)

---

## 🧐 À propos du projet
L'architecture propre est basée sur les principes de Robert C. Martin, qui encouragent :
- Une séparation claire des responsabilités.
- Une facilité à tester et à étendre le code.
- Une adaptation aisée à différents frameworks ou technologies.

### Les couches principales :
1. **Presentation** : Widgets Flutter et gestion de l'état.
2. **Domain** : Contient la logique métier et les cas d'utilisation.
3. **Data** : Gestion des sources de données (API, local, etc.) et implémentation des repositories.
4. **Core** : Classes et utilitaires communs.

---

## 🗂️ Structure du projet

```plaintext

lib/
├── core/            
│   # Classes communes (e.g., erreurs, constants)
├── data/            
│   # Sources de données (API, local, etc.)
│   ├── models/      
│   │   # Modèles de données
│   ├── repositories/ 
│       # Implémentations des repositories
├── domain/          
│   # Logique métier
│   ├── entities/    
│   │   # Entités métier
│   ├── usecases/    
│   │   # Cas d'utilisation
│   ├── repositories/ 
│       # Abstractions des repositories
├── presentation/    
│   # Widgets, pages, et gestion de l'état
│   ├── bloc/        
│   │   # Gestion de l'état avec BLoC/Cubit
│   ├── pages/       
│   │   # Pages de l'application
│   ├── widgets/     
│       # Widgets réutilisables

```

---

## ⚙️ Prérequis

Avant de commencer, assurez-vous d'avoir installé :
- [Flutter SDK](https://flutter.dev/docs/get-started/install) (version 3.0 ou supérieure)
- [Dart SDK](https://dart.dev/get-dart)
- Un IDE comme [Android Studio](https://developer.android.com/studio) ou [Visual Studio Code](https://code.visualstudio.com/)

---

## 🚀 Installation

1. Clonez le repository :
   ``` 
   git clone https://github.com/safwenbarhoumi/clean-architechture-flutter
   ```
2. Accédez au dossier du projet :
   ```
   cd clean-architechture-flutter
   ```
3. Installez les dépendances :
   ```
   flutter pub get
   ```
4. Lancez l'application :
   ```
   flutter run
   ```

---

## ✨ Fonctionnalités

- **Architecture modulaire** : Facilite la maintenance et les mises à jour.
- **Support multi-plateforme** : Fonctionne sur iOS, Android, et le Web.
- **Tests unitaires** : Inclut des exemples de tests pour la logique métier.

---

## 📚 Ressources utiles

- [Documentation officielle de Flutter](https://flutter.dev/docs)
- [Principes de Clean Architecture](https://8thlight.com/blog/uncle-bob/2012/08/13/the-clean-architecture.html)
- [Flutter Clean Architecture (projet GitHub)](https://github.com/boskokg/flutter-clean-architecture)

---

## 👨‍💻 Auteur

- **Safwen BARHOUMI**  

