# Machinlearning_bonus_project
    Face detection. Given a certain face, see if the script could tell its name(label) according to the training dataset. Also, test the accuracy of the algorithm.
All our work were based on lab8, the transfer learning with a pre-trained deep neural network.
    So we used vggface package as our pre-trained model. And we downloaded the dataset from http://www.anefian.com/research/face_reco.htm, which contains 750 images of 50 people. 
    Additionally, we added another 15 images of one of our classmates to see if we could extract her face from a larger image and then use the extracted image to do the training and testing work. If you want to use your own pictures to test our program, you could download the face-detection.ipynb to extract your face from your pirture and then add it into our training and testing dataset.
    
Our final project succeeded in facing detection and extraction with validation accuracy = 94.12%.

For more details about the code , you could turn to the final_project.ipynb.

If you want to run this project on your own PC, you should
-Download the dataset_fetching.ipynb and final_project.ipynb.
-Run dataset_fetching.ipynb to get the dataset from dropbox. After this step, you will have a train folder and a test folder in your current path.
-Run final_project.ipynb to get the output of our project. This step could cost about 20min because of  the large amount of data.
