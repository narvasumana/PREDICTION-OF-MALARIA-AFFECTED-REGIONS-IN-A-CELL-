# PREDICTION OF MALARIA AFFECTED REGIONS IN A CELL

What is it?

In this project I am training the Matterport Mask R-CNN model to detect the Region affected with Malaria in a cell.

How I did it?

First, I downloaded the Mask R-CNN package, then prepared a dataset of 100 annotated images using VGG Annotator. After annotating the images using VGG annotator we can export the annotated images as csv or json file. Then I trained the model on GPU. The training of model takes time, then I tested the model on new images and the model detected the malaria affected region in a cell with an acccuracy of 96%.

How to run?

We need to download the Mask R-CNN package from Matterport, then download the images dataset folder. Then we can run the notebook(i.e. .ipynb) file on jupyter notebook.
