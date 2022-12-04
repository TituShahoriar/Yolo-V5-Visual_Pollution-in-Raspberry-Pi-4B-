
visual_pollution_dhaka - v8 2022-10-17 1:33am
==============================

This dataset was exported via roboflow.com on November 28, 2022 at 9:06 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 5657 images.
Visual-pollution-dhaka are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 224x224 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Random brigthness adjustment of between -20 and +20 percent
* Random exposure adjustment of between -7 and +7 percent
* Salt and pepper noise was applied to 3 percent of pixels


