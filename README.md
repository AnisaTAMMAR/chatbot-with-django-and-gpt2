# Chatbot avec Django et GPT-2

Ce projet est un chatbot intelligent développé avec Django comme framework backend et GPT-2 pour la génération de réponses conversationnelles.

## Fonctionnalités

- Interface web pour interagir avec le chatbot.
- Intégration du modèle GPT-2 pour générer des réponses contextuelles.
- Gestion des sessions utilisateur avec Django.
- Facile à déployer et à personnaliser.

## Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants installés :

- Python 3.8 ou supérieur
- pip (gestionnaire de paquets Python)
- Git (pour cloner le dépôt)

## Installation

1. Clonez ce dépôt sur votre machine locale :
   ```bash
   git clone https://github.com/AnisaTAMMAR/chatbot-with-django-and-gpt2
   cd chatbot-with-django-and-gpt2
   ```
2.Créez un environnement virtuel et activez-le :

```bash
python -m venv venv
source venv/bin/activate  # Sur Windows : venv\Scripts\activate
```
3.Installez les dépendances du projet :

```bash
pip install -r requirements.txt
```
4.Téléchargez le modèle GPT-2 (si nécessaire) et placez-le dans le dossier approprié.

5.Appliquez les migrations de la base de données :

```bash
python manage.py migrate
```
6.Lancez le serveur de développement :

```bash
python manage.py runserver
```
7.Accédez à l'application via votre navigateur à l'adresse :


```bash
http://127.0.0.1:8000/
```
#Structure du projet
-chatbot/ : Application Django principale.

   -models.py : Modèles de base de données.
   
   -views.py : Logique de traitement des requêtes.
   
   -templates/ : Fichiers HTML pour l'interface utilisateur.

-gpt2/ : Module pour l'intégration de GPT-2.

-manage.py : Script de gestion de Django.

-requirements.txt : Liste des dépendances Python.

##Utilisation
1.Ouvrez l'interface du chatbot dans votre navigateur.

2.Saisissez votre message dans la zone de texte et appuyez sur "Envoyer".

3.Le chatbot générera une réponse en utilisant GPT-2.

##Déploiement

1.Pour déployer ce projet sur un serveur en production, suivez les étapes suivantes :

2.Configurez un serveur web comme Nginx ou Apache.

3.Utilisez un service comme Gunicorn pour servir l'application Django.

4.Configurez les variables d'environnement pour la production (e.g., DEBUG=False, SECRET_KEY, etc.).

5.Déployez sur une plateforme comme Heroku, AWS, ou DigitalOcean.

#Contribution
Les contributions sont les bienvenues ! Si vous souhaitez contribuer, suivez ces étapes :

1.Forkez le projet.

2.Créez une branche pour votre fonctionnalité (git checkout -b feature/NouvelleFonctionnalité).

3.Committez vos changements (git commit -m 'Ajout d'une nouvelle fonctionnalité').

4.Pushez vers la branche (git push origin feature/NouvelleFonctionnalité).

5.Ouvrez une Pull Request.

Fait avec ❤️ par TAMMAR Anisa
