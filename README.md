thank to @carolinepacheco helped me about convert Yolo to all file PascalVOC.
Make sure you have the dependencies listed on yolo_to_voc.py.

Update root path (where this script lies) in line 46. ROOT = 'coco'.

Let's say that you have a custom dataset, which is not included in COCO. eg ship. Add its name to YOLO_CLASSES=(), in the first position.

Remove images that are already in /coco/images, /coco/labels and /coco/outputs.

Put all your images at /coco/images folder.

Put corresponding annotations (.txt files) to /coco/labels

source: @carolinepacheco https://github.com/carolinepacheco/Convert-YOLO-to-PascalVOC 
follow  @carolinepacheco.

Thank.