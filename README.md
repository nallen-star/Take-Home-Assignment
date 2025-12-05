# Take-Home-Assignment

Using the Folder of provided images I compared the speed and results of using two different deep learning algorithims.

The first was the YOLO model and the second was the Faster RCNN model. 
The TakeHome juptyer file contains the code for each model and a comparison of the results. 

# Code Breakdown 
- The first chunk imports the necessary libraries and runs the YOLO model. It ouputs a dataframe of the model used, image analyzed, the amount of objects detected, the average confodence of the identification and e time it took to run the model on the respective image.
- The second chunk runs the FRCNN model for each image and again creates a dataframe that contains the model used, image analyzed, the amount of objects detected, the average confodence of the identification and e time it took to run the model on the respective image.
- The third chunk creates a comparison dataframe that houses a combination of the two previously created YOLO and FCRNN model dataframes. This way its easy to see and compare the results of each model.
- The fourth and final chunk, contains a way to get image data without deep learning algorithims. It pulls an images height and width as well as the average color (BGR color codes). 
