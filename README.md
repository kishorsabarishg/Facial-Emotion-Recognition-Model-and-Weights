# Facial-Emotion-Recognition-Model-and-Weights

> The model is trained on the CK+48 dataset from https://www.kaggle.com/shawon10/ckplus which consists of 981 images.

> There are seven classes of expression : Anger, Contempt, Disgust, Fear, Happy, Sadness and Surprise

> The order classes to the model is : {'happy': 0, 'disgust': 1, 'contempt': 2, 'sadness': 3, 'fear': 4, 'anger': 5, 'surprise': 6}

> The labels are contained in the "lable_1.pickle" file.

> The model was trained for 50 epochs on Google Colab with images resized into 128pixels X 128pixels (original dimensions : 48pixels X 48pixels)

> The models validation accuracy is : 97.97%

> The file "Emotion_Model.json" consists of the trained Model. It contains the information about the network, ie., layers,layer size, activation, type of layer, etc.

> The file "Emotion_model_weights.h5" contains the weights for the trained model.

> The file "labels.pickle" contains the labels of the class.

> Download these files and read it(open it) and use it!

> The "CKPLUSFER.ipynb" is the code for training on the images.

> The "Testing.ipynb" is for real-time video testing.

> The "haarcascade_frontalface_default.xml" is used to detect the frontal face of a human. It is based on Cascade Classfier.
