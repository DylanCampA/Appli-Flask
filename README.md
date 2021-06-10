Application de création, modofication et suppression d'articles stockés dans une bdd SQLite.

Ce qu'il faut faire : 

Exécuter la commande : 
```sh
python3 -m venv env
``` 
pour créer un environnement virtuel

Exécuter la commande : 
```sh
source env/bin/activate
```
pour activer cette envirennement 

Exécuter la commande :
```sh
export FLASK_ENV=development && export FLASK_APP=app && flask run -p 5001
```
Poour exécuter l'application sur un environnement de développement. 
Le fichier ou l'application est exécuter est app.py (là où il y a les routes).
L'application s'exécutera sur le port 5001 (Le port par défault est 5000)
