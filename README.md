# Speech Emotion Recognition Using Deep Learning

Speech Emotion Recognition (SER) plays a crucial role in enhancing communication systems and human-computer interaction, making it a key area of research in affective computing. This repository presents a complete system for recognizing emotions from speech and compares the performance of two feature extraction techniques: **Gammatone Cepstral Coefficients (GTCC)** and **Power-Normalized Cepstral Coefficients (PNCC)**.  

## Methodology  

The experiments were conducted using a Deep Learning model—an **Artificial Neural Network (ANN)** trained with the **Bayesian Regularization Algorithm (BRANN)**. The model was tested on a combination of three datasets: **TESS, RAVDESS, and SAVEE**.  

### Results  

| Feature Extraction | Accuracy (%) |
|--------------------|-------------|
| PNCC              | 76.72%       |
| GTCC              | 82.30%       |

The results demonstrate that **GTCC outperforms PNCC** in speech emotion recognition when trained on the same datasets.  

## Conclusion  

This study highlights the impact of feature selection on SER performance and provides insights into optimizing deep learning models for emotion recognition tasks.
