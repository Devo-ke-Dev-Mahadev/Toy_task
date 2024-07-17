# Toy_task
For AP Values check the Before and After train AP_Values image.
For Model : go to drive and find "train_models/checkpoint.pth"

For visualization i have modified the main.py such that now after evaluation it draw the bounding boxes on the image and store them under the "visual" folder.

After training the pre-trained-model on the training data and then evaluation the AP and AR values are detroiated.

Reasons can be :

--> Overfitting.

--> Insufficient Data for Fine-Tuning.

--> Less data for evaluation.

Model Link and complete repository link: https://drive.google.com/drive/folders/148S4LtVZxceICeC9Y8OGMg16UjoVTxgB?usp=sharing.

In visualization we can see before traing and after training the model is creating additional boxes example image 1904.jpg , we can see there are overlapping boxes.
also in example 11613.jpg the bounding boxes are not correct.
Detecting pillar as pedestrain in example 13187.jpg.

