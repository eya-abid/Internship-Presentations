
traffic - v2 new
==============================

This dataset was exported via roboflow.ai on August 28, 2021 at 8:06 PM GMT

It includes 248 images.
Cars are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Random brigthness adjustment of between 0 and +25 percent
* Random Gaussian blur of between 0 and 10 pixels
* Salt and pepper noise was applied to 8 percent of pixels

The following transformations were applied to the bounding boxes of each image:
* Random brigthness adjustment of between -52 and 0 percent


