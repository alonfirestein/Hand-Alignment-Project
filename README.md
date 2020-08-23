# Hand-Alignment-Project

## This is a university based project in the field of Data Science and Machine Learning. 
##### The idea of this project is based upon a research paper called "Harnessing Machine Learning For Interpersonal Physical Alignment" (included in the files). The research was conducted by Dr. Roi Yozevitch, Dr. Hila Gvirts, Dr. Ornit Apelboim, and Dr. Elhanan Mishraky.

The research presents a novel way to determine interpersonal physical synchrony state by inspecting hands’ postures obtained from a unique 3D depth camera device named Leap-Motion Controller.
We have datasets with hand motion sensor recordings, our task was to classify the type of the hands moving:
1.)Spontaneous
2.)Synchronized
3.)Alone

In the datasets there are 14 different features including hand, wrist and elbow postioning, velocity, yaw, pitch... etc 
In the Jupyter Notebook file we can see the rest of the features given in the datasets.

**Note:** For this we combined every 5 rows into 1 row.


|   Model Name  | Validation Score|
| ------------- | ------------- |
| KNN  | 96%  |
| Random Forest  | 80%  |
| Gradient Boosting | 93%  |
| Linear SVC | 99%  |
| Logistic Regression | 83% |



