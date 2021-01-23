# Traitement d'image
Notebooks Jupyter pour les algorithmes de traitement d'images les plus répandus.

# Utilisation
Pour manipuler directement les notebooks, rendez-vous sur Binder [:link:](https://mybinder.org/v2/gh/ingranys/traitement-image/HEAD).

# Résultats

## Segmentation
Mise en oeuvre de l'algorithme de machine learning **k-means** pour segmenter les images en **N couleurs**.

### Principe général du k-means

<p align="left">
  <img src="https://github.com/ingranys/traitement-image/blob/main/résultats/kmeans-theory.png" width="300">
</p>

### Application sur des images

<p align="left">
  <img src="https://github.com/ingranys/traitement-image/blob/main/résultats/kmeans-mario.png" width="350">
</p>

<p align="left">
  <img src="https://github.com/ingranys/traitement-image/blob/main/résultats/kmeans-castle.png" width="500">
</p>

### Module interactif

<p align="left">
  <img src="https://github.com/ingranys/traitement-image/blob/main/résultats/kmeans-widget.png" width="500">
</p>

### Visualisation de "la courbe en coude"

<p align="left">
  <img src="https://github.com/ingranys/traitement-image/blob/main/résultats/kmeans-elbow.png" width="350">
</p>


## Recadrage intelligent
Mise en oeuvre d'une implémentation de l'algorithme **seam-carving** pour recadrer les images de manière intelligente.

### Résultats en sortie

<p align="left">
  <img src="https://github.com/ingranys/traitement-image/blob/main/résultats/seamcarving-dali.png" width="600">
</p>

<p align="left">
  <img src="https://github.com/ingranys/traitement-image/blob/main/résultats/seamcarving-castle.png" width="600">
</p>

### Module interactif

<p align="left">
  <img src="https://github.com/ingranys/traitement-image/blob/main/résultats/seamcarving-widget.png" width="500">
</p>


## Détection des contours
Implémentation des algorithmes classiques pour la détection des contours : **sobel**, **prewitt**, **laplace**, **canny**...

### Implémentation de Sobel

<p align="left">
  <img src="https://github.com/ingranys/traitement-image/blob/main/résultats/edge-sobel.png" width="500">
</p>

### Comparaison des filtres

<p align="left">
  <img src="https://github.com/ingranys/traitement-image/blob/main/résultats/edge-filters.png" width="700">
</p>

### Visualisation de Canny

<p align="left">
  <img src="https://github.com/ingranys/traitement-image/blob/main/résultats/edge-canny2.png" width="250">
</p>


## Flou profond
Implémentation de filtres avancées pour reproduire un effet de **bokeh**.

### Variations des filtres

<p align="left">
  <img src="https://github.com/ingranys/traitement-image/blob/main/résultats/bokeh-filters.png" width="400">
</p>

### Résultats en sortie

<p align="left">
  <img src="https://github.com/ingranys/traitement-image/blob/main/résultats/bokeh-tree.png" width="600">
</p>


## Lissage
Implémentation d'un algorithme de lissage basé sur un noyau **Gaussien**.

### Génération du noyau

<p align="left">
  <img src="https://github.com/ingranys/traitement-image/blob/main/résultats/blur-gaussian.png" width="600">
</p>

### Résultats en sortie

<p align="left">
  <img src="https://github.com/ingranys/traitement-image/blob/main/résultats/blur-mario1.png" width="350">
</p>

### Décomposition du noyau

<p align="left">
  <img src="https://github.com/ingranys/traitement-image/blob/main/résultats/blur-mario2.png" width="350">
</p>

### Effet inattendu 

<p align="left">
  <img src="https://github.com/ingranys/traitement-image/blob/main/résultats/blur-mario3.png" width="200">
</p>
