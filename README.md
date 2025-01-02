# Detector

Detector is a AI developed using Neural Networks and the saved model categorizes ships defects into 5 categories:
- Rust
- Scratches
- Pitted
- Inclusion
- Rolled
- Patches
- Crazing
- Corrosion

A simple UI is provided to upload the image of the defect and show the result to simplify user-interaction.
The model contains 3 convolutional layers, 3 max-pooling layers, 2 dense layers, and 1 dropout layer and uses cross-validation.
However, because of lack of data, the accuracy acheived is only 40-50%.
