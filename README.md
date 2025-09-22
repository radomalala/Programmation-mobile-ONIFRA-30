# Cours ONIFRA INFOL3 – Programmation Mobile & Kotlin

Bienvenue dans le dépôt officiel des cours de programmation mobile et Kotlin.  
Ce dépôt contient les supports de cours, les exercices, et les corrigés liés aux séances animées par **Radomalala RATRIMOSOA EUGENE**.

---

## 📂 Contenu du dépôt
- `seance0_enrichie.pdf` → Pré-requis & Outils (installation, GitHub, projet fil rouge)  
- `seance1_enrichie.pdf` → Introduction & Hello World  
- `seance2_enrichie.pdf` → Bases de Kotlin  
- `seance3_enrichie.pdf` → Interfaces Graphiques  
- `seance4_enrichie.pdf` → Navigation entre écrans  
- `seance5_enrichie.pdf` → Stockage des données  
- `seance6_enrichie.pdf` → Permissions & Services  
- `seance7_enrichie.pdf` → API Internet  
- `seance8_enrichie.pdf` → Projet final  
- `TP_corriges_enrichis.pdf` → Corrigés des TP (Séances 1 → 7)  
- `cours_kotlin_ONIFRA_INFOL3.pdf` → Bases de Kotlin (avec historique et exemples)  

---

## 🚀 Objectifs de la formation
- Comprendre les bases du développement mobile Android.  
- Apprendre les fondements de Kotlin.  
- Construire des applications mobiles natives et hybrides.  
- Développer un **projet fil rouge** en plusieurs étapes.  

---

## 📌 Prérequis
- Connaissances de base en algorithmique.  
- Environnement Windows (ou Linux/Mac avec adaptation).  
- Outils installés : JDK, Node.js, VS Code, Ionic CLI, Git, GitHub.

---
README _ MonAppTemplate (Kotlin + Gradle)
🚀 Description

Ce projet est un template Android Kotlin prêt à l’emploi, compilable avec Gradle, et utilisable dans Visual Studio Code.
Il contient une simple activité affichant Hello Kotlin avec VS Code 🚀.

📂 Structure du projet
MonAppTemplate/
│── build.gradle.kts          → Configuration Gradle racine
│── settings.gradle.kts       → Nom du projet
│── gradlew / gradlew.bat     → Scripts Gradle (Linux/Windows)
│
└── app/
    │── build.gradle.kts
    │── src/
        └── main/
            ├── AndroidManifest.xml
            ├── java/com/example/monapp/MainActivity.kt
            └── res/layout/activity_main.xml

⚙️ Prérequis

JDK 17+ installé → vérifier avec :

java -version


Gradle (ou utiliser le wrapper ./gradlew).

Android SDK installé (au minimum API 34).

Visual Studio Code avec extensions :

Kotlin Language

Android i18n JSON Tool

Gradle for Java

▶️ Compilation & Exécution
Linux / Mac
./gradlew build
./gradlew assembleDebug

Windows
gradlew.bat build
gradlew.bat assembleDebug

Résultat

Un fichier APK est généré dans :

app/build/outputs/apk/debug/app-debug.apk

📱 Déploiement sur smartphone

Connecter le smartphone via USB ou transférer l’APK avec Xender.

Sur Android → activer Sources inconnues.

Ouvrir app-debug.apk et cliquer sur Installer.

Lancer l’application → un message Hello Kotlin avec VS Code 🚀 s’affiche.


## 👨‍🏫 Auteur
**Radomalala RATRIMOSOA EUGENE**  
Cours ONIFRA INFOL3 – Programmation Mobile  
