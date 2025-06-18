# YOLO_NAS_Helmet_Detection
Using the High Latency low quantized model YOLO-NAS to detect Helmet inside an Industrial Environment to ensure Worker's safety. Used Customed data set for two classes &amp; trained with the pre-trained Coco dataset backbon
## Annotation
The Annotations for Two different classes - [Helmet On, No Helmet], was made using Computer Vision Annotation Tool(CVAT). CVAT annotates an image with class labels & gives a .txt file to produce yolostyle annotation. It gives annotation in the following format - [Class X_centre Y_Centre Width Height] all normalised form. The annotated yolo format is then converted to bbox format(X_top_left, Y_top_left, X_bottom_right, Y_bottom_right) for augmentations & transformation before training.
