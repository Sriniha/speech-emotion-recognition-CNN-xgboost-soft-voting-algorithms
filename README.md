# speech-emotion-recognition-xgboost-soft-voting-algorithms

emotion of a person is recognised through speech which is done by 3 different algorithms in this case.

Process: 

download dataset : https://zenodo.org/record/1188976#.YIAL6Z_is2x  (The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS))
 
1. 12 Actors & 12 Actresses recorded speech and song version respectively.
2. Actor no.18 does not have song version data.
3. Emotion Disgust , Neutral and Surprised are not included in the song version data.

1. Please run the notebook named: speech_emotion_recognition_xgboost_.ipynb
2. Please create a ./data/ folder and put all of the data inside.
3. Please create a ./model/ folder and set it as the model weight saving directory.
4. The accuracy scores of xgboost and soft voting algorithms is compared in this project where xgboost has the highest accuracy score with than the other algorithms.


