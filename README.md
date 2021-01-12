# Gender-Recognition-using-Open-Images-dataset-V5
Evaluate a model using deep learning techniques to detect human faces in images and then predict the image-based gender. To that end, the special pre -trained algorithm from source - https://github.com/arunponnusamy/gender-detection-keras will be trained on a dataset of men and women (Human Face) photos. The algorithm would predict a person's gender after training just by examining his / her face.

For exploratory data analysis, we will be examining on –

•	Total number of different categories with highest number of labels available in them.

•	Which labels are mostly used in Human Faces category? By this we will come to know about how many data we must train for female and male faces.

•	How many male or female humans were wearing glasses in the images.

•	What are the different sizes of images in Human Faces?	

•	What are different labels in training and validation/testing data sets available in Human Face category.

**Data Source**-
•	This data source link -https://storage.googleapis.com/openimages/web/visualizer/index.html?set=train&type=detection&c=%2Fm%2F0dzct

•	This data contains around 36.5 M images with 19,969 classes with three types- ‘Segmentation’, ‘Detection’ and ‘Relationships’ with multiple categories.

•	We will be using ‘Detection’ type with ‘Human Face’ category from this dataset to implement this project.

**Execution**-

This is going to be 5 different parts series-

•	Part1 – It covers data extraction and data loading and data cleaning part

•	Part2 – It covers data exploratory data analysis.

•	Part3 – This part contains the Feature extraction.

•	Part4 – This part contains model training.

•	Part5 – This part carries out the evaluation and predictions.

