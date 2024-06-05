# Human-emotion-analysis-based-on-voice-emotion-recognition-using-CNN

![alt text]( https://github.com/pahaht/Human-emotion-analysis-based-on-voice-emotion-recognition-using-CNN/blob/main/pictures/SystemScheme.JPG)

### *Introduction*
Speech Emotion Recognition (SER) is a technology that uses various algorithms 
to detect emotions from audio signals. This project uses FFT to convert time-domain
speech signals into the frequency domain, which is then processed by a CNN to classify the emotions.

### *System design*
FFT Processing: Converts speech signals from time-domain to frequency-domain.
CNN Model: Utilizes a deep learning model to classify emotions.
Emotion Categories: Supports multiple emotion categories (e.g., happy, sad, angry, neutral).
User-Friendly Interface: Easy-to-use interface for testing and evaluating speech samples.

### *Dataset*
In this project, audio samples from Kaggle datasets were analyzed
[https://www.kaggle.com/code/shivamburnwal/speech-emotion-recognition], 
which are broken down into four separate datasets. Crowd-sourced Emotional
Multimodal Actors Dataset (Crema-D), Ryerson Audio-Visual Database of 
Emotional Speech and Song (Ravdess), Surrey Audio-Visual Expressed
Emotion (Savee), and Toronto Emotional Speech Set (Tess).

### *SER analysis by FFT
The FFT is the crossing of the time domain into the frequency domain.
This transformation occurs when the audio signal is converted into a
spectrogram image with the help of the Discrete Fourier Transform
![alt text]( https://github.com/pahaht/Human-emotion-analysis-based-on-voice-emotion-recognition-using-CNN/blob/main/pictures/wavesampled.JPG)
![alt text]( https://github.com/pahaht/Human-emotion-analysis-based-on-voice-emotion-recognition-using-CNN/blob/main/pictures/spectrogram.JPG)


### *Model Architecture*
The model consists of the following main components:
FFT Layer: Converts the audio signal from time-domain to frequency-domain.
CNN Layers: Extracts features from the frequency-domain representation of the audio signal.
Fully Connected Layers: Classifies the extracted features into predefined emotion categories.

![alt text]( https://github.com/pahaht/Human-emotion-analysis-based-on-voice-emotion-recognition-using-CNN/blob/main/pictures/architecture.JPG)




