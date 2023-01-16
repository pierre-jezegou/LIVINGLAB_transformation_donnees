# Transformation des données
Ces fichiers ont pour but de transformer un fichier HL7-FHIR en fichier CSV. En effet, nous avons besoin d'un fichier csv pour l'utilisation d'IAs par la suite. C'est donc dans cette optique que ces fichiers ont été développés.

## Utilisation des programmes :
Cloner le dépôt en local :
```bash
git clone https://github.com/pierre-jezegou/LIVINGLAB_transformation_donnees/
```

Ouvrir le fichier `traitement_donnees.py`
```bash
nano traitement_donnees.py
```

Modifier si besoin le nom du fichier FHIR (`.json`) dans ce fichier.

Exécuter le fichier depuis le terminal :
```bash
./traitement_donnees.py
```

Un répertoire 'CSV' va être créé avec tous les nouveaux fichiers.
