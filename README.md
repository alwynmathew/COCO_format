# Dataset format for COCO dataset

Proper annotation structure of [COCO dataset](http://cocodataset.org/#home) isnt availble in the [offical page](http://cocodataset.org/#format-data), thus I made tree-like structure to easily understand the annotation file before fiddling with the dataset.

You can download COCO dataset from this [link](http://cocodataset.org/#download) ([mirror link](https://pjreddie.com/projects/coco-mirror/)).

Annotation file like [2014 Train/Val annotations](http://images.cocodataset.org/annotations/annotations_trainval2014.zip) have mainly three kind of files:

* caption file
* instance file
* person keypoint file

structure breakdown of each of these files can be found at

* [caption](https://github.com/alwynmathew/COCO_format/blob/master/formats/caption.pdf)
* [instance](https://github.com/alwynmathew/COCO_format/blob/master/formats/instance.pdf)
* [person keypoint](https://github.com/alwynmathew/COCO_format/blob/master/formats/person_keypoints.pdf)

respectively.
