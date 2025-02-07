## Description
Ce projet automatise le traitement et l'importation de fichiers CSV dans Google Cloud Storage (GCS) avant leur chargement dans BigQuery. 
Voici les étapes :
- Téléchargement des fichiers depuis GCS.
- Nettoyage et validation des données.
- Stockage des données valides et des erreurs.
- Chargement des données nettoyées dans BigQuery.
- Déplacement des fichiers traités vers un dossier d'archives.

## Prérequis
- Python (version)
- Google Cloud SDK
- Accès à Google Cloud Storage et BigQuery
- packages necessaire (voir `requirements.txt`)

## Installation
1. Clonez le projet :
   
   git clone https://github.com/ton-utilisateur/ton-repo.git
  
2. Installez les dépendances :

   pip install -r requirements.txt

3. Configurez  accès à GCP 


