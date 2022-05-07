# Emotion Recognition from Multi Channel EEG Signals

### Presentation Video - <a href="https://drive.google.com/file/d/1bjPKzAdPDGlTP6Amaq2KV9vyCMPJx-Dz/view?usp=sharing">Click Here</a>
### Project Report - <a href="https://drive.google.com/file/d/1-G99b2uUtsyAe2CtwbyeJ035Kc-R9iLH/view?usp=sharing">Click Here</a>
### Pre-processed Data - <a href="https://drive.google.com/drive/folders/1kAyd2pwrfy2z7sCJ1SXzHoyVj7PnYBjN?usp=sharing">Click Here</a>
### DE Features - <a href="https://drive.google.com/drive/folders/1hKTs-pO4gU39Zt9isIM8ungsoeA9k_rF?usp=sharing">Click Here</a>
### 3D Constructed Features - <a href="https://drive.google.com/drive/folders/10lHb1qMr7Evh7BhWzyXivODUvTl7t2fb?usp=sharing">Click Here</a>
### Result Data - <a href="https://drive.google.com/drive/folders/1uiCtkXp3K9M1Zpazp7LeOvs8dc38yXjX?usp=sharing">Click Here</a>

Electroencephalogram (EEG) based emotion recognition is one of the most important tasks in the brain-computer interfacing (BCI) domain. In this project, my objective is to develop a robust machine learning framework to classify human emotions from multi-channel EEG signals. For extracting useful features from the EEG signal, first, the signals are decomposed into four frequency bands using the Butterworth filter and then differential entropy (DE) features from that are extracted. These DE features are used as the input for the machine learning models. Besides the general feature, I used a 3D representation of EEG features that is suitable for fully convolutional networks. Here, I conducted a comparative study with the standard machine learning models, some customized models, and their variants and evaluated them on the well-recognized DEAP dataset. Our result shows that a model with SVM performed better than the other models. My proposed neural network and fully convolutional network approach also showed promising results. However, I believe these approaches have the potential to achieve better performance with more tuning efforts.
