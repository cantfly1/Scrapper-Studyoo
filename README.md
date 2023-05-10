## Récupérateur d'images et téléchargeur Google Drive

Ce script Python vous permet de récupérer des images sur Internet et de les télécharger sur Google Drive. C'est un outil utile pour collecter rapidement un grand nombre d'images pour une utilisation dans divers projets, tels que des modèles d'apprentissage automatique, l'analyse de données et la visualisation.

Le script utilise les bibliothèques suivantes :

- `pathlib` : Une bibliothèque pour travailler avec des chemins de fichiers de manière indépendante de la plate-forme.
- `jmd_imagescraper` : Une bibliothèque pour récupérer des images à partir de moteurs de recherche.
- `jmd_imagescraper.imagecleaner` : Une bibliothèque pour nettoyer manuellement les images récupérées.
- `pydrive` : Une bibliothèque pour travailler avec l'API Google Drive.

### Utilisation

1. Clonez ce dépôt sur votre machine locale.
2. Installez les bibliothèques requises en exécutant la commande `pip install -r requirements.txt` dans votre terminal ou invite de commande.
3. Définissez l'identifiant de dossier Google Drive correct dans la ligne `file = drive.CreateFile(...)` du script.
4. Exécutez le script en ouvrant `scraper.ipynb` 

Le script recherchera des images pour une requête spécifiée, les téléchargera dans le répertoire spécifié et les téléchargera sur Google Drive. Vous pouvez modifier la requête, le nombre d'images à télécharger et d'autres paramètres en modifiant l'appel de la fonction `duckduckgo_search()` dans le script.

Notez que vous devez avoir les identifiants API nécessaires configurés pour vous authentifier auprès de Google Drive. Pour plus d'informations sur la configuration des identifiants API, veuillez vous référer à la [documentation de l'API Google Drive](https://d35mpxyw7m7k7g.cloudfront.net/bigdata_1/Get+Authentication+for+Google+Service+API+.pdf).

### Licence

Ce projet est sous licence STUDYOO 
