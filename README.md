# Speech-emotion-recognition
Building model able to recognize emotion in audio recordings of human voice


### Project description

RAVDESS dataset: https://zenodo.org/record/1188976#.XuZO_0RR05k

Dataset contains recordings as raw vaw files. So, first, features have to be extracted from it, to be fed into ML models. This is done using Mel-frequency cepstral coefficents (MCFC), state-of-the-art algorithm for sound features extraction. More on it can be found in attached Juypter notebook. Model is then built using LSTM reccurent neural network architecture.


### Used technologies

- Python 3.7 with JupyterLab environment
- Tensorflow 2.1 with Keras
- librosa
- numpy
- scipy
- matplotlib
- seaborn
- scikit-learn
