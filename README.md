# Facial_Expression_Detection

The project goal is to get the Facial Expression from a photo/Video and Classify it into one of this classes:
{Angry , Disgust , Fear , Sad , Neutral , Happy , Suprised}
The total Number of the  dataset samples was about 28,000 sample Divided between these classes.

### And here is some samples of the Dataset :
![Sample Images](https://user-images.githubusercontent.com/114799056/194708602-4f7c30ad-cd2d-4f24-ac86-8162f71840b1.png)


And then I apply some Data Augmention on the Dataset , and then split it into Validation/Train .


### And Here is The Structure of the CNN Model:


![model](https://user-images.githubusercontent.com/114799056/194709080-3be02c4f-6f0f-4152-b933-030c044a575b.png)



After we trained the model , we save the structure of the model , and the weights , to use it on a Flask app .

To try the performance of the model yourself , you can clone the project , and then run :

python main.py

### It will open an html webpage (localhost) with a video stream Like this :


![Angry](https://user-images.githubusercontent.com/114799056/194709477-a27b98a1-6e8b-4815-b6c4-da7a3e4e5466.png)




### This Project is a part of Coursera Guide Projects 



