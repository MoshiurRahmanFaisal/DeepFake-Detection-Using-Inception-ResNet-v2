# DeepFake Detection Using Inception-ResNet-v2

## Dataset

Dataset link: [**Kaggle**](https://www.kaggle.com/code/mmmarchetti/deep-fake-chalenge)

## Preprocessing

- `OPEN-CV`  was used to get frames from the video. 
- Face Detector from `Dlib` was used to get face images from frames. 

## Model Accuracy

Inception-ResNet-v2 pretrained model was used to classify real or fake. 

| **Model** | **Accuracy (%)**
| :-------- | :------- 
| Inception-ResNet-v2 | 91.2% 
