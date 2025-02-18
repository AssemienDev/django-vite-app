# django-vite-app

Ce projet est un script conçu pour configurer un projet Django avec Vite et Tailwind CSS. Il est destiné à simplifier la mise en place d'un environnement de développement web moderne avec Django comme backend, React pour le frontend, et Tailwind CSS pour la gestion des styles.

## Prérequis

Avant d'exécuter ce script, assurez-vous que votre environnement remplit les conditions suivantes :

### Python
Le script nécessite **Python 3.9** ou une version supérieure pour fonctionner correctement.

Vérifiez votre version de Python avec la commande suivante :

```bash
python --version
```

Si nécessaire, téléchargez et installez Python depuis le site officiel : [python.org](https://www.python.org/).

### Node.js
Le script fonctionne avec **Node.js v20.15.0** ou supérieur pour gérer la configuration de Vite.

Vérifiez votre version de Node.js avec la commande suivante :

```bash
node --version
```

Si vous devez installer ou mettre à jour Node.js, rendez-vous sur [nodejs.org](https://nodejs.org/).

### Autres Prérequis
- **Tailwind CSS v3.4.17** : Ce script est conçu pour fonctionner avec cette version de Tailwind. Aucune version ultérieure n'a été testée pour le moment.
- **React et Django** : Le script fonctionne exclusivement avec une combinaison de React pour le frontend et Django pour le backend.

### Environnement de Développement
- Sur Windows, il est important d'exécuter ce script dans **cmd** (Command Prompt) et non dans **PowerShell**. PowerShell peut causer des conflits ou des erreurs, donc il est recommandé d'utiliser cmd pour garantir une exécution fluide sur windows ou dans **bash** sur Linux/MacOS.

## Installation

### Étape 1 : Creer ton projet

Installer le package :
```bash
pip install django-vite-app
```

### Avertissement d'installation :

Le script create-django-vite-app.exe sera installé dans un répertoire spécifique de votre système, mais ce répertoire n'est peut-être pas automatiquement ajouté au PATH de votre système. S'il n'est pas ajouté cela signifie que vous pourriez recevoir l'avertissement suivant :

Exemple:\
WARNING: The script create-django-vite-app.exe is installed in 'C:\Users\utilisateur\AppData\Local\Packages\PythonSoftwareFoundation.Python.3.12\LocalCache\local-packages\Python312\Scripts' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.

### Solution :

Pour résoudre ce problème et pouvoir lancer la commande create-django-vite-app directement depuis votre terminal (cmd sous Windows ou bash sous Linux/MacOS), vous devez ajouter le répertoire d'installation du script au PATH de votre système.

Voici comment faire :

    Ouvrir les paramètres système avancés :
        Cliquez avec le bouton droit sur Démarrer, puis sélectionnez Système > Paramètres système avancés.
        Cliquez sur Variables d'environnement....

    Modifier la variable Path :
        Dans la section Variables système, trouvez et sélectionnez la variable Path, puis cliquez sur Modifier.
        Ajoutez un nouveau chemin en cliquant sur Nouveau et collez le chemin suivant :
    
    Placer le chemin que le warning vous aura donner 
    Exemple: C:\Users\utilisateur\AppData\Local\Packages\PythonSoftwareFoundation.Python.3.12\LocalCache\local-packages\Python312\Scripts

Enregistrer les modifications :

    Cliquez sur OK pour enregistrer les modifications.


Enfin, vous pouvez lancer le script avec la commande suivante, toujours dans **cmd** sur windows ou dans **bash** sur Linux/MacOS :
```bash
create-django-vite-app
```

Cela lancera le processus de configuration pour intégrer Vite avec votre projet Django et configurera Tailwind CSS.

### Étape 2 : Suivre les étapes dans le cmd sur windows ou dans bash sur Linux/MacOS

C'est un script interactif qui interagit avec l'utilisateur à chaque étape

## Usage
Après installation vous aurez un message 

✅ Installation terminée ! \
Backend : un scrit pour lancer django \
Frontend: un script pour lancer react

### Point important: exécuter les scripts dans le CMD sur windows ou dans **bash** sur Linux/MacOS

## Fonctionnalités

- Ce script crée un environnement de développement intégré avec Django, React et Tailwind CSS.
- Il configure automatiquement Vite comme bundler pour React.
- Il installe Tailwind CSS v3.4.17 et l'intègre dans le projet.

## Limitations

- Actuellement, ce script est conçu pour fonctionner uniquement avec **Django** + **React** + **Tailwind CSS**. D'autres frameworks ou outils de frontend ne sont pas supportés pour le moment.
- Le script doit être exécuté dans **cmd**, et non dans **PowerShell**, pour éviter tout conflit potentiel sur windows ou dans **bash** sur Linux/MacOS.

## Contribution

Les contributions sont les bienvenues ! Si vous avez des suggestions ou des améliorations, n'hésitez pas à ouvrir une issue ou à soumettre une pull request.

## Licence

Ce projet est sous licence MIT. Consultez le fichier [LICENSE](LICENSE) pour plus de détails.

