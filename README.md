# EmotionRecognitionKeystrokeDynamics
Emotion Recognition through keystroke dynamics in Pyhon

In this work, we will, therefore, explore the classification task of emotion recognition through keystroke dynamics, as well as evaluate whether including demographic information (age, gender, educatoin level, typing habits, etc.) is appropriate for this task. Inspired by previous works on this task, we will also introduce a new feature based on edit distances to capture the number of typos in typed text and assess if this feature is relevant and helpful for our task.

The contributions of this work are the following:
- We explore the emotion recognition task through keystroke dynamics and show that we can identify people's emotional states thanks to features extracted from keyboards. We also compare different experiment and classification settings and demonstrate that we achieve the best performance for fixed-text experiments, with XGBoost or SVM models.
- We introduce a new feature based on edit distances to capture the number of typos in typed text and show that this feature is valuable and helps improve classification results.
- We investigate whether demographic information on participants helps improve performance, and find that some of them are beneficial for our task. The others should be filtered out thanks to feature selection methods.

Details about this work can be found in my report, available in this GitHub repository.

The *EmoSurv* dataset in available on IEEE website and must be used according to the license granted by its authors: https://ieee-dataport.org/open-access/emosurv-typing-biometric-keystroke-dynamics-dataset-emotion-labels-created-using
