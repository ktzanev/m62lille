# [m62lille](https://github.com/ktzanev/m62lille)

[page web](https://ktzanev.github.io/m62lille/)

## Les TPs du module M62 – « Équations différentielles » de l'Université de Lille.

Vous pouvez récupérer [ce dépôt](https://github.com/ktzanev/m62lille) de deux façons faciles :

- en téléchargeant l'archive [zip](https://github.com/ktzanev/m62lille/archive/master.zip) qui contient la dernière version des fichiers,
- récupérer l'intégralité de ce dépôt, y compris l'historique des modifications, en utilisant `git` avec la commande

  ~~~~~~~
  git clone git@github.com:ktzanev/m62lille.git
  ~~~~~~~


### 2020/21

Vous pouvez aussi ouvrir [ce dépôt](https://github.com/ktzanev/m62lille) dans le cloud :

- avec ![Binder](https://mybinder.org/badge_logo.svg) :
  [[OVH](https://binder.mybinder.ovh/v2/gh/ktzanev/m62lille/master)]
  [[MyBinder](https://mybinder.org/v2/gh/ktzanev/m62lille/master)]
  [[Gesis](https://notebooks.gesis.org/binder/v2/gh/ktzanev/m62lille/master)]
  [[Google Cloud](https://gke.mybinder.org/v2/gh/ktzanev/m62lille/master)]
  ;
- avec ![Google Colab](https://colab.research.google.com/assets/colab-badge.svg) :
  [[Google Colab](https://colab.research.google.com/github/ktzanev/m62lille/blob/master)]
  _(pour l'exécution vous avez besoin d'un compte Google)_.

[Ce dépôt](https://github.com/ktzanev/m62lille) contient les fichiers :

- [Feuille de TP n°0](M62_TP0.ipynb)
*(cette feuille 0 est à étudier, et jouer avec, avant le début des tps)*
- [Feuille de TP n°1](M62_TP1_NOM_Prenom.ipynb)
*(version α qui sera modifiée par la suite)*


### 2019/20

Téléchargeant l'archive [zip](https://github.com/ktzanev/m62lille/archive/refs/tags/v2020.zip) qui contient la version des fichiers de 2019/20.

Dans [la version de 2019/20](https://github.com/ktzanev/m62lille/tree/v2020) vous pouvez trouver les sources `ipynb` suivants :

- Feuille de TP n°0 [[source ipynb](https://github.com/ktzanev/m62lille/blob/v2020/TPs/M62_TP0.ipynb)]<br>
*(cette feuille 0 est à étudier, et jouer avec, avant le début des tps)*
- Feuille de TP n°1 [[source ipynb](https://github.com/ktzanev/m62lille/blob/v2020/TPs/M62_TP1_NOM1_NOM2.ipynb)]
- Feuille de TP n°2 [[source ipynb](https://github.com/ktzanev/m62lille/blob/v2020/TPs/M62_TP2_NOM1_NOM2.ipynb)]
- Feuille de TP n°3 [[source ipynb](https://github.com/ktzanev/m62lille/blob/v2020/TPs/M62_TP3_NOM1_NOM2.ipynb)]
- Feuille de TP n°4 [[source ipynb](https://github.com/ktzanev/m62lille/blob/v2020/TPs/M62_TP4_NOM1_NOM2.ipynb)]

Vous pouvez aussi ouvrir ces fichiers dans le cloud avec ![Binder](https://mybinder.org/badge_logo.svg) :
  [[OVH](https://binder.mybinder.ovh/v2/gh/ktzanev/m62lille/v2020?filepath=TPs)]
  [[MyBinder](https://mybinder.org/v2/gh/ktzanev/m62lille/v2020?filepath=TPs)]
  [[Gesis](https://notebooks.gesis.org/binder/v2/gh/ktzanev/m62lille/v2020?filepath=TPs)]
  [[Google Cloud](https://gke.mybinder.org/v2/gh/ktzanev/m62lille/v2020?filepath=TPs)]
  ;

## Comment utiliser iPython dans les salles de tp, ou sur votre ordinateur

1. Récupérez le fichier `.ipynb` du TP en question.
1. Ouvrez un terminal et aller dans le répertoire où vous avez enregistré les fichiers `.ipynb`.
1. Lancez le notebook iPython avec
  ```bash
  jupyter notebook
  ```
1. Normalement le navigateur web s'ouvre automatiquement à la page du notebook, mais sinon dans le terminal sont affichées des informations qui se terminent par
  ```bash
  Or copy and paste one of these URLs:
  http://localhost:8888/?token=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
  ```
  (où `xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx` est un code unique d'accès).

  Copier et coller cette adresse dans votre navigateur... c'est parti.

## Comment installer iPython sur votre ordinateur

Il y a différentes façons d'installer `python` (et par conséquent `iPython` avec `jupyter`). Nous vous conseillons d'utiliser la distribution [Mini Conda](https://docs.conda.io/en/latest/miniconda.html) qui est la version « mini » d'[Anaconda](https://www.anaconda.com/products/individual).

Cette distribution vient avec le gestionnaire de paquets `conda` qui vous permet d'installer les bibliothèques dont vous avez besoin pour ces TPs :
- `jupyterlab` : pour l'exécution des `.ipynb` dans votre navigateur ;
- `numpy` : pour la manipulation aisée des vecteurs et des matrices ;
- `matplotlib` : pour les rendus graphiques ;
- `scipy` : pour la résolution approchée des EDO avec `odeint` ;

Pour installer toutes ces bibliothèques il suffit d'exécuter en ligne de commande
```bash
conda install -c conda-forge jupyterlab numpy matplotlib scipy
```
