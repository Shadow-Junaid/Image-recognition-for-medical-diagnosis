
Chest X-Rays - v4 2022-08-16 10:39am
==============================

This dataset was exported via roboflow.com on August 22, 2022 at 11:04 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 13976 images.
Pneumonia are annotated in folder format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Random shear of between -3° to +3° horizontally and -2° to +2° vertically
* Random brigthness adjustment of between -5 and +5 percent
* Random exposure adjustment of between -5 and +5 percent


