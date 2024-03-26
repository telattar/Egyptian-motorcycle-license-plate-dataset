# Egyptian Motorcycle 🏍️ License Plate dataset
## Why was it collected?
Numerous Egyptian license plate recognition systems have been created in recent years using deep learning models, image processing procedures, morphological operations, and other techniques.
However, due to the lack of an appropriately sized dataset, the outcomes of these systems are difficult to compare.

More importantly, it has been noticed that none of the previous researches took into consideration the motorcycle license plates, which look quite different from the plates attached to cars, busses and trucks.

In order to fill this gap, a 1230-image dataset of Egyptian motorcycle license plates has been collected, annotated using roboflow, and used in my graduation project.
The dataset in this repository is suitable for use with YOLOv8 and possibly other versions of YOLO.

![samples dataset](https://github.com/telattar/Egyptian-motorcycle-license-plate-dataset/assets/110330655/5c5ce9f9-fb37-4876-8191-23baa2045b18)

## What this repo contains

This repo has three folders: test, train and valid. each folder contains a fraction of the dataset.

The ```train``` folder contains 80% of the dataset and is used for model training. Meanwhile, both the ```test``` and ```valid`` folders contain 10% of the dataset, and are used for testing and validating the trained model.

Each folder contains two subfolders: ```images``` which contains the photos, and ```labels``` which have .txt files that contain each image's annotation. 

Please cite the link to this repo if you'll use the dataset.
Credits to Tarteel Elattar. All rights reserved.
