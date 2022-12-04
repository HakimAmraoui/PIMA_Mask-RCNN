# PIMA_Mask-RCNN
Research project and implementation of a Mask R-CNN on cellular images.

## Images
This folder contains the images used for the template.

## Modele
The *Model* contains the model files:

* `annotations.json` : file containing information about the masks of the images in the *Images* folder.
* `Run_Mask_RCNN_on_cells.ipynb` : jupyter notebook loading the most recent model.
* `Train_Mask_RCNN_on_cells.ipynb` : jupyter notebook that trains the model.
* `mask_rcnn_object_0005.h5` : model driven by the jupyter `Train_Mask_RCNN_on_cells.ipynb`.

## Instructions

To facilitate the import and use of the libraries used by the notebook files, it is best to load the notebooks on Google Collab and upload the necessary files.
After uploading the `Run_Mask_RCNN_on_cells.ipynb` file, upload the trained model, the `dataset.zip` file and the `annotations.json` file.
