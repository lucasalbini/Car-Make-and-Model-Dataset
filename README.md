# UTFPR-CMMD - Federal University of Technology - Paraná - Car Make and Model Dataset

## Image dataset for car make and model recognition

This dataset was created for car make and model recognition in static images. We provide annotated images for multiclass classification obtained from specialized websites and google images. The data have 25000 images split into 50 different classes at the level of Make and Model.

## Specifications Table

![Specification Table](SpecificationTable.png)

## Value of the data

* There are very few video datasets especially devised for anomaly detection. These two datasets include images taken on a highway where trucks are not allowed at certain hours of the day. Such events are considered anomalies. However, as all classes are fully-labeled, for academic purposes, any of the classes can be treated as an anomaly.

* Data is provided mainly for training One-Class classifiers for anomaly detection, in video frames. However, due to the labeling, this data can also be used for counting vehicles. This dataset includes videos and static images (frames) so that data can be analyzed in different ways.

* Differently from other image/video datasets, we make available both the clips, the discretized frames and a text file with the ground truth (indicating anomalies or normal frames)

## Data

Data were collected on a highway on a clear day. The initial objective was to detect large vehicles (trucks), since they are not allowed to run during certain hours of the day. Videos were collected with the camera in two positions, such that the highway lane was filmed transversally (UTFPR-HSD1) and longitudinally (UTFPR-HSD2). In the first case, the camera was positioned at the floor level. In the latter, the camera was positioned at an elevated level. UTFPR-HSD2 has different scenarios: vehicles coming towards the camera and vehicles going away from the camera. Moreover, objects become occluded at certain times.

Videos were collected at 30 fps (frames per second) with resolution 1920 x 1080 pixels. All frames extracted from videos have the same resolution. The figure below summarizes the quantity of each class in the dataset.

![Classes UTFPR-HSD](ClassesUTFPR-HSD.png)
## Sample images from UTFPR-HSD1 and UTFPR-HSD2

![UTFPR-HSD1](SamplesUTFPR-HSD1.png)

![UTFPR-HSD2](SamplesUTFPR-HSD2.png)

## Sample video from UTFPR-HSD1 and UTFPR-HSD2


![UTFPR-HSD1](VideoUTFPR-HSD1.gif) ![UTFPR-HSD1](VideoUTFPR-HSD2.gif)

## Links to the data
[UTFPR-HSD1]()
###https://drive.google.com/file/d/1C3mXMpItQgctGALu7cGMAmeOShXdzIOY/view?usp=sharing

## Acknowledgments

## Publications:



