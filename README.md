# Emotion_Detection_CNN-IITISoc2022


https://user-images.githubusercontent.com/99892898/184361402-13b8b507-b4a8-42b7-ba8b-eb34ed96a73a.mp4



## Packages need to be installed
- Numpy
- CV2
- keras
- tensorflow
- intrtools

## Kaggle Code link
- https://www.kaggle.com/code/amankumar2004/emotion-detection-recognition


## All the folders in the directory:
1. harcascade- 
2. models- contains the final .json file and model weights we used in our final inference.py and live_emotion_detection.py file. 
   emotion_model.json
   emotion_model_weights.h5
4. samples- contains the video we found on internet on which we tested our face recognition and emotion detection on using live_emotion_detection.py file.
5. face_emotion_recognition.ipynb file if the final jupyter notebook we trained on giving all the details including confusionn matrix and dataset breifing.

It will take several hours depends on your processor. (On i7 processor with 16 GB RAM it took me around 4 hours)

|   Train_acc   |    Train_loss   |    Val_acc      |    Val_loss     |    F1_score     |
| :------------ |:---------------:|:---------------:|:---------------:|:---------------:|
|   84.09%      |    0.9372       |    65.60%       |    1.117        |    0.486569     |
| :------------ |:---------------:|:---------------:|:---------------:|:---------------:|
