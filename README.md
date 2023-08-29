# AtmoDetect - Weather Phenomena Recognition Using CNN

## About the Dataset

The provided dataset consists of a collection of 6862 images capturing various types of weather conditions. These images can be employed to develop a weather classification system that categorizes photos based on the prevailing weather conditions depicted in them. This dataset is valuable for machine learning and computer vision projects aimed at weather classification, and it offers a diverse range of images that showcase different weather phenomena.

## Content

The dataset is organized into 11 distinct classes, each representing a specific weather condition. The classes are as follows:
- Dew
- Fog/Smog
- Frost
- Glaze
- Hail
- Lightning
- Rain
- Rainbow
- Rime
- Sandstorm
- Snow

Each class represents a different type of weather event, enabling the construction of a robust weather classification model. The images in the dataset have been labeled and categorized according to the corresponding weather conditions they depict.

## Objectives

The primary objectives of working with this dataset are as follows:

1. **Weather Classification**: The main objective is to develop a convolutional neural network (CNN) model that can accurately classify images based on the depicted weather conditions. By training a CNN on this dataset, the model will learn to distinguish between different types of weather phenomena and make predictions accordingly.

2. **Model Evaluation**: Another goal is to evaluate the performance of various pre-trained CNN architectures on this weather classification task. Architectures such as 'EfficientNetB7', 'ResNet50', 'MobileNet', 'VGG19', 'Xception', 'InceptionResNetV2', 'VGG16', 'ResNet101', and 'DenseNet201' will be assessed for their ability to extract relevant features and classify images effectively.

3. **Model Comparison**: The dataset allows for a comprehensive comparison of the performance of different CNN architectures. By training and evaluating multiple models, it will be possible to determine which architecture yields the best results in terms of accuracy, precision, recall, and F1-score for the given weather classification task.

4. **Generalization**: The developed CNN models will be evaluated for their ability to generalize to new, unseen data. This involves testing the models on a separate test dataset that was not used during training to assess their performance in real-world scenarios.

5. **Insight into Weather Patterns**: Through the successful implementation of the weather classification model, insights can be gained into the characteristics and visual cues that distinguish different weather conditions. This could contribute to a better understanding of weather patterns and their representation in images.

Please feel free to explore the dataset and the results of the weather classification model in the accompanying notebooks and documentation.
