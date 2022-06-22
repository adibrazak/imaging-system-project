# imaging-system-project

Dataset used


File YOLOTest1: not success in trying to use YOLO. 
Putting it here incase anyone want to have a look at what I'm doing wrong
.
File Recyclable Image preprocessing: the file contain code use to process the image.
To summarize,  the only image processing applied only smoothing and CLAHE as for now.
.
File Recyclable classification: code for training etc.
.
.
For progress, firstly we collect image from internet and put as non-recyclable and recyclable categories.

Then, the data was used for training.

Training accuracy and validation accuracy results were record.
.
Next, the data was applied with image smoothing and CLAHE.

Then, the data was used for training.

Training accuracy and validation accuracy results were record.
.
As for comparison, when the training just get started, the accuracy using image without processing (Results->2.1 No preprocessing.PNG)

is lower compared to accuracy using processed image (Results->5.1 smooth+clahe.PNG)
.
At epoch 1, using image without processing, training accuracy: 61.47% , validation accuracy: 55.46%.

Using image with processing, training accuracy: 67.12% , validation accuracy: 70.31%.
.
(Results->2.2 No preprocessing.PNG)

At epoch 11~20, using image without processing, most  training accuracy is <80% with most validation accuracy < 75%.

(Results->5.2 smooth+clahe.PNG)

using image with processing, most  training accuracy is >80% with lot of validation accuracy >75%.
