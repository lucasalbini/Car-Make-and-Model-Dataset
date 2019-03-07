# UTFPR-CMMD - Federal University of Technology - Paraná - Car Make and Model Dataset

## Image dataset for car make and model recognition

This dataset was created for car make and model recognition in static images. We provide annotated images for multiclass classification obtained from specialized websites and google images. The data have 25000 images split into 50 different classes at the level of Make and Model.

## Specifications Table

![Specification Table](SpecificationTable.png)

## Value of the data

* There are very few datasets especially devised for recognition of car make and model. This dataset contains images of the 50 best selling cars in Brazil in the year of 2018 and contains about 500 instances per class. In the future it is expected to increase the number of classe to cover the majority of vehicles used in Brazil.

* Recognition of car make and model is very important for publicly security, a powerful classifier can reduce labor cost in and increase the efficiency of real-time security cameras.

* Our dataset has images of different types that can increase the robustness of the classifier.


## Data

Data were collected from various sources, such as vehicle specialized websites, manufacturers websites, image repositories on the internet, among others. The initial objective was to classify images in three category: Car Make, model and year. But, due to the complexity of the problem we decided to start only with the vehicle model.

The data set has a total of 25,000 images distributed in 10 makes and 50 models, each class with an average of 500 images. The distribution of the models can be seen in the image below.

![Make Count](make_count.png)

The dataset was preprocessed using [YOLO](https://pjreddie.com/darknet/yolo/), to cut only the vehicle in the image, discarding the background and possible noises. Some examples of images within the dataset can be seen below.

![CMMD-UTFPR](mosaico.JPG)


## Links to the data
[UTFPR-CMMD]()

## Acknowledgments

## Publications:



