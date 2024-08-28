# SeasonScope
SeasonScope is a novel deep learning system designed to identify seasons and generate contextually accurate captions from outdoor images.

- **Data Collection and Processing**: Season images are manually scraped using Unsplash API and season captions are manually created using BLIP.
- **Classification**: We train 6 models in total (ResNet-50, VGG-19, GoogLeNet, DenseNet-201, EfficientNetV2, and our own customized Convolutional Neural Network). We achieve over 95% accuracy in season classification with our own CNN model and a modified EfficientNetV2 model enhanced through transfer learning techniques.
- **Image Captioning**: By constructing an image captioning model that integrates CNN with Long Short-Term Memory (LSTM) networks, it is capable of generating high-quality, descriptive captions that effectively convey the nuances of different seasonal landscapes.

## Data
https://drive.google.com/drive/folders/1dO6lUBV_G7y6vGF05-aBCvvNII44Cy7i?usp=sharing