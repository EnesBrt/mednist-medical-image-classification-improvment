# MedNIST Medical Image Classification Improvement

## Objectif du projet

L'objectif initial de ce projet était d'améliorer une application écrite en utilisant Pytorch et Flask où l'utilisateur peut ajouter une seule image dans l'interface de l'application et obtenir le résultat de prédiction et l'afficher dans l'interface.

La tâche requise était d'ajouter une fonctionnalité qui permet de sélectionner un ensemble d'images, de les afficher dans l'interface et de les trier dans le dossier approprié en utilisant le modèle amélioré.

## Structure du projet

Le projet contient les dossiers et fichiers suivants :

- `models` : Contient les modèles utilisés pour la classification des images.
- `resized` : Contient les images redimensionnées pour la classification.
- `static` : Contient les fichiers statiques utilisés par l'application Flask.
- `templates` : Contient les templates HTML utilisés par l'application Flask.
- `app.py` : Le fichier principal de l'application Flask.
- `commons.py`, `inference.py`, `regression test.py` : Ces fichiers contiennent le code pour le traitement des images et l'inférence du modèle.
- `test.ipynb` : Un notebook Jupyter pour tester l'application.
- `Procfile`, `app.json`, `runtime.txt` : Ces fichiers sont utilisés pour le déploiement de l'application sur une plateforme comme Heroku.

## Comment utiliser le projet

Pour utiliser ce projet, vous devez d'abord cloner le dépôt sur votre machine locale. Ensuite, naviguez jusqu'au répertoire du projet et installez les dépendances nécessaires en utilisant pip :

```bash
pip install -r requirements.txt
```

Ensuite, vous pouvez démarrer l'application Flask en utilisant la commande suivante :

```bash
python app.py
```

Cela démarrera l'application sur votre machine locale. Vous pouvez alors accéder à l'application en ouvrant votre navigateur web et en naviguant jusqu'à `http://localhost:5000`.

Pour utiliser l'application, il suffit d'uploader une image ou un ensemble d'images via l'interface utilisateur. L'application classifie ensuite les images et affiche les résultats dans l'interface.
