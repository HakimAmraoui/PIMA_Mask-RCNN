# PIMA_Mask-RCNN
Projet de recherche et implémentation d'un Mask R-CNN sur des images cellulaires.

## Images
Ce dossier contient les images utiliser pour par le modèle.

## Modele
Le *Modele* contient les fichiers du modèle:

* `annotations.json` : fichier contenant les informations sur les masques des images du dossier *Images*.
* `Run_Mask_RCNN_on_cells.ipynb` : jupyter notebook chargeant le modèle le plus récent.
* `Train_Mask_RCNN_on_cells.ipynb` : jupyter notebook qui entraîne le modèle.
* `mask_rcnn_object_0005.h5` : modèle entraîné par le jupyter `Train_Mask_RCNN_on_cells.ipynb`.

## Instructions

Pour faciliter les import et l'utilisation des librairies utilisées par les fichiers notebook, il est préférable de charger les notebook sur Google Collab et d'upload les fichiers nécessaires.
Après avoir upload le fichier `Run_Mask_RCNN_on_cells.ipynb`, upload le modèle entraîné, le fichier `dataset.zip` et le fichier `annotations.json`.