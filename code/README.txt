Files and their content (in the order of creation):
1) crema-d-train-test-split.ipynb - perform the train/test split for both audio and visual data
2) crema-d-human-data-exploration.ipynb - explore the human results to calculate the accuracies and other metrics
3) crema-d-visual-analysis.ipynb - build CNN-LSTM model and train and test on visual data
4) crema-d-audio-analysis-standardise.ipynb - standardise audio data and train and test SVM
5) crema-d-augment-audio.ipynb - add noise and random shift to audio data
6) crema-d-audio-analysis-noise-stand.ipynb - train and test SVM on standardised audio data w/ noise + shift augmentation
7) crema-d-audio-analysis-standardise-pca.ipynb - train and test SVM on PCA transformed audio data
8) crema-d-exploration-of-results.ipynb - plot charts for human vs ML model results