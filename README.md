# Tensorflow-Object-Detection-Pipeline
The use of Object Detection API pipeline for varied cases (in this case annotating large dataset by creating a primitive model)

The first step of the pipeline is to get the training and testing images ready. These need to be labelled. In this git repo, we are creating a primitive model using only a few training image set, annotating them manually. Then using this primitive model to get large dataset annotated though the testing process of the api.
So for labelling the images, we need them to be in the PASCAL VOC metrics or popularly known as the tf-record format. Hence, after labelling them using the labelling tool mentioned in this repo, we convert those into the tf-record format to feed into training. Also, we shall have a '.pbtxt' class label file. 

## Labelling tool - LabelImg 

Requirements - python3.x and pyQt5

