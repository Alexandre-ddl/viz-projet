# Visualisation des Prénoms en France

Ce projet utilise Dash pour créer des visualisations interactives des prénoms les plus populaires en France de 1900 à 2020. Le projet est divisé en trois visualisations distinctes, chacune répondant à différentes questions sur les données des prénoms.

## Description du Projet

Nous travaillons avec un ensemble de données sur les prénoms en France, contenant la liste de tous les prénoms enregistrés en France, année par année, de 1900 à 2020. Il y a deux ensembles de données : l'un agrégé au niveau national et l'autre avec des données par département. Notre objectif est de créer 3 visualisations différentes autour de ces données, chacune se concentrant sur différents types de questions concernant les données :

### Visualisation 1: 
Comment les prénoms évoluent-ils au fil du temps ? Y a-t-il des prénoms qui sont restés constamment populaires ou impopulaires ? Y en a-t-il qui ont été soudainement ou brièvement populaires ou impopulaires ? Y a-t-il des tendances temporelles ?

### Visualisation 2:
Y a-t-il un effet régional dans les données ? Certains prénoms sont-ils plus populaires dans certaines régions ? Les prénoms populaires sont-ils généralement populaires dans tout le pays ?

### Visualisation 3:
Y a-t-il des effets de genre dans les données ? La popularité des prénoms donnés aux deux sexes évolue-t-elle de manière cohérente ?

## Composition du groupe R

- Julian Silva
- Alexandre Desgrees du lou 
- Mathieu Delarue
- Merlin Poitou
- Louis Borreill

## Prérequis

* Python 3.6 ou supérieur est installé sur votre machine.

### Créer un environnement virtuel

```bash
# Se placer dans le répertoire de votre projet
cd /chemin/vers/mon-projet

# Créer un environnement virtuel nommé 'venv'
python3 -m venv venv
```

> Cela crée un dossier `venv/` contenant une installation isolée de Python.

### Activer l'environnement virtuel

* **Sous macOS / Linux**

  ```bash
  source venv/bin/activate
  ```

* **Sous Windows (PowerShell)**

  ```powershell
  .\venv\Scripts\Activate.ps1
  ```

* **Sous Windows (CMD)**

  ```cmd
  .\venv\Scripts\activate.bat
  ```

### Installer les dépendances via `requirements.txt`

1. Assurez-vous d'avoir un fichier `requirements.txt` à la racine de votre projet.

2. Dans l'environnement activé, exécutez :

   ```bash
   pip install -r requirements.txt
   ```

> Cela installera toutes les librairies et versions spécifiées dans le fichier.

### Gérer et mettre à jour les dépendances

* **Pour ajouter une nouvelle dépendance** :

  ```bash
  pip install nom-du-paquet
  pip freeze > requirements.txt
  ```

* **Pour mettre à jour une dépendance** :

  ```bash
  pip install --upgrade nom-du-paquet
  pip freeze > requirements.txt
  ```

* **Pour supprimer une dépendance** :

  ```bash
  pip uninstall nom-du-paquet
  pip freeze > requirements.txt
  ```

### Désactiver l'environnement virtuel

```bash
deactivate
```



