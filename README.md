# Dementia Detection with Data Science Techniques

## Overview

This repository contains the research code and findings for a project focused on dementia detection using data science techniques. The research journey involved exploring both text-based and audio-based classification methods to identify dementia cases. The repository includes code implementations, dataset descriptions, and evaluation results for the different models employed.

## Text-Based Classification

### Pre-processing

The first phase of the research involved text classification, where textual transcripts from the Pitt Corpus (Dementia Bank Organization, s.d.) were used as input for the classification models. Before training the models, thorough pre-processing techniques were applied to enhance data quality and relevance. Steps included noise reduction and speech-to-text conversion to ensure dataset accuracy and comprehensiveness.

### Model Selection

Multiple classification methods were employed and evaluated for text-based dementia detection. The following models were used:

- **Support Vector Machines (SVM):** A widely-used algorithm for text classification tasks.
- **Deep Neural Networks:** Employed to capture complex relationships within the textual data.
- **Ensemble Models:** A combination of SVM and Recurrent Neural Networks (RNN) predictions.
- **Transformer-Based Models:** Specifically, TFDistilBertForSequenceClassification, adapted and fine-tuned for the dementia detection task.

### Model Performance

The performance of the different models was evaluated and compared using various metrics. The initial SVM model showed promising results with an accuracy of 0.81 and a Receiver Operating Characteristic Area Under Curve (ROC AUC) of 0.89. The SVM-RNN ensemble achieved an accuracy of 0.79 and a ROC AUC of 0.84, while the TFDistilBertForSequenceClassification model achieved comparable results with an accuracy of 0.79 and a ROC AUC of 0.87. These findings demonstrate strong performance in identifying dementia cases.

## Audio-Based Classification

### Pre-processing

In parallel with text classification, the research also explored audio-based classification for dementia detection. This involved assigning class labels to raw audio waveforms extracted from the Pitt Corpus. A pre-processing phase was conducted to extract meaningful features such as spectrograms and mel-frequency cepstral coefficients (MFCCs) from the audio data.

### Wav2Vec2 Model

The next step in the audio-based classification process involves utilizing the extracted features as inputs to fine-tune the Wav2Vec2 model with a dedicated dataset. This powerful model aims to enhance the accuracy and efficiency of dementia detection through audio classification.

Please note that the training phase of this algorithmic approach is part of our future planned work and is yet to be completed.

## Contributions and Further Exploration

This repository presents valuable insights into the potential of data science techniques for dementia detection. The findings highlight the effectiveness of different models in identifying dementia cases using textual and audio data. Researchers and developers interested in this domain can leverage the code and methodologies presented here for further exploration and improvement.

## Acknowledgments

We acknowledge the Pitt Corpus and Dementia Bank Organization for providing the dataset used in this research.

## License

This project is licensed under the [MIT License](LICENSE).
