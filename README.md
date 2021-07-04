# Covid-Detection
Using CXR images to create an efficient ML classifier that can distinguish COVID-19 cases from non-COVID-19 cases with high accuracy and sensitivity.
Dataset:
COVID- 140 X-ray images
Normal- 140 X-ray images
Pneumonia- 140 X-ray images

1-Run "preprocess_images.py" to preprocess images done by resizing, normalization, adaptive histogram equalization

2-Run "extract_features.py" to create three feature pools for covid or normal or pneumonia datasets

3-Run "evaluate_features.py" to evaluate extracted features

4-Run "train_model.py" to train and then evaluate model
