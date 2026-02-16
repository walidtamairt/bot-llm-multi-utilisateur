Présentation

Ce projet est une application de chat multi-utilisateur basée sur un LLM, développée avec Next.js 14 et TypeScript.
Elle permet à plusieurs utilisateurs de discuter en temps réel avec un modèle de langage.

Prérequis

Node.js 18 ou plus

npm ou yarn

Une clé API Google valide

Installation
1. Cloner le dépôt
git clone https://github.com/Zakariae-212/Multi-User-Chat.git
cd Multi-User-Chat

2. Installer les dépendances
npm install

3. Configurer les variables d’environnement

Créer un fichier .env.local à la racine du projet et y ajouter :

GOOGLE_API_KEY=your_google_api_key_here

4. Lancer l’application en développement
npm run dev


L’application sera accessible par défaut à l’adresse :
http://localhost:3000

Modèle de langage utilisé

L’application utilise Google Gemini 2.5 Flash.

Ce modèle a été retenu pour :

sa rapidité, adaptée aux échanges en temps réel ;

sa capacité à fonctionner avec des quotas gratuits, permettant de démarrer sans coût initial ;

ses performances suffisantes pour une application de chat multi-utilisateur.

Structure du projet (optionnel)

app/ : pages et routes Next.js

components/ : composants UI

lib/ : logique métier et intégration du LLM

public/ : ressources statiques
