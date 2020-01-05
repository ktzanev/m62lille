# [m62lille](https://github.com/ktzanev/m62lille)

[page web](https://ktzanev.github.io/m62lille/)

## Les TPs du module M62 – « Équations différentielles » de l'Université de Lille.

Vous pouvez récupérer [ce dépôt](https://github.com/ktzanev/m62lille) de deux façons faciles :

- en téléchargeant l'archive [zip](https://github.com/ktzanev/m62lille/archive/master.zip) qui contient la dernière version des fichiers,
- récupérer l'intégralité de ce dépôt, y compris l'historique des modifications, en utilisant `git` avec la commande

  ~~~~~~~
  git clone git@github.com:ktzanev/m62lille.git
  ~~~~~~~

Vous pouvez aussi ouvrir [ce dépôt](https://github.com/ktzanev/m62lille) dans le cloud :

- avec Google Colab : [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ktzanev/m62lille/blob/master) [pour l'exécution vous avez besoin d'un compte Google];
- avec Binder : [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ktzanev/m62lille/master?filepath=TPs).

### 2019/20

Dans [ce dépôt](https://github.com/ktzanev/m62lille) vous pouvez trouver les sources `ipynb` suivants :

- Feuille de TP n°1 [[source ipynb](https://ktzanev.github.io/m62lille/TPs/M62_2019_2020_TP1.ipynb)] [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ktzanev/m62lille/blob/master/TPs/M62_2019_2020_TP1.ipynb) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ktzanev/m62lille/master?filepath=%2FTPs%2FM62_2019_2020_TP1.ipynb)
- Feuille de TP n°2 [[source ipynb](https://ktzanev.github.io/m62lille/TPs/M62_2019_2020_TP2.ipynb)] [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ktzanev/m62lille/blob/master/TPs/M62_2019_2020_TP2.ipynb) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ktzanev/m62lille/master?filepath=%2FTPs%2FM62_2019_2020_TP2.ipynb)
## Comment utiliser iPython dans les salles de tp

1. Ouvrer un terminal et aller dans le répertoire où vous allez stocker les fichiers `ipynb`.
2. Pour récupérer le TP numéro `X` faire
  ```
  wget https://ktzanev.github.io/m62lille/TPs/M62_2019_2020_TPX.ipynb
  ```
  *(Cette adresse correspond au lien vers la source ipynb indiqué plus haut en face du tp en question.)*

3. Puis lancer le notebook iPython avec
  ```
  jupyter notebook
  ```
4. Normalement le navigateur web s'ouvre automatiquement à la page du notebook, mais sinon dans le terminal sont affichées des informations qui se terminent par
  ```
  Or copy and paste one of these URLs:
  http://localhost:8888/?token=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
  ```
  (où `xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx` est un code unique d'accès).

  Copier et coller cette adresse dans votre navigateur ... c'est parti.
