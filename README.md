Voici un README documentant votre projet "Data Scientist" :

---

# Projet : Data Scientist

## Introduction

Dans ce projet, vous manipulerez des arrays et des hashs contenant des centaines d'éléments, le tout via un programme dans un dossier Ruby bien structuré. Ce projet est une excellente introduction aux programmes plus complexes que vous verrez la semaine prochaine.

## Structure du projet

Créez un dépôt GitHub avec la structure suivante :

```
ton_dossier
├── lib
│   ├── 00_journalists.rb
│   └── 01_cryptocurrencies.rb
└── README.md
```

## Configuration

1. Clonez le dépôt GitHub.
2. Naviguez dans le dossier cloné.
3. Assurez-vous d'avoir Ruby installé sur votre machine.

## Utilisation

### 1. Journalistes

Le fichier `00_journalists.rb` contient des analyses sur une liste de handles Twitter de journalistes.

#### Fonctionnalités

- **Nombre de journalistes** : Affiche le nombre total de journalistes dans l'array.
- **Handles contenant un numéro** : Compte et affiche les handles contenant un numéro.
- **Handles contenant "aude"** : Compte et affiche les handles contenant les lettres "aude" à la suite.
- **Handles commençant par une majuscule** : Compte et affiche les handles commençant par une majuscule.
- **Handles contenant au moins une majuscule** : Compte et affiche les handles contenant au moins une majuscule.
- **Nombre total de underscores** : Affiche le nombre total de underscores dans tous les handles.
- **Tri par ordre alphabétique** : Trie et affiche les handles par ordre alphabétique.
- **50 handles les plus courts** : Affiche les 50 handles les plus courts.
- **Position de @epenser** : Affiche la position de @epenser dans l'array.

#### Exécution

Pour exécuter le script, utilisez la commande suivante dans le terminal :

```bash
ruby lib/00_journalists.rb
```

### 2. Cryptomonnaies

Le fichier `01_cryptocurrencies.rb` analyse des données de cryptomonnaies.

#### Fonctionnalités

- **Crypto avec la plus grande valeur** : Affiche la crypto avec la plus grande valeur.
- **Crypto avec la plus petite valeur** : Affiche la crypto avec la plus petite valeur.
- **Nombre de cryptos contenant "coin"** : Compte et affiche les cryptos contenant le mot "coin".
- **Devises dont le cours est inférieur à 6000** : Affiche les devises avec un cours inférieur à 6000.
- **Devise la plus chère sous 6000** : Affiche la devise la plus chère parmi celles avec un cours inférieur à 6000.

#### Exécution

Pour exécuter le script, utilisez la commande suivante dans le terminal :

```bash
ruby lib/01_cryptocurrencies.rb
```

<!-- ## Contributeurs

- [Votre Nom](https://github.com/votre-profil-github)

## Licence -->
