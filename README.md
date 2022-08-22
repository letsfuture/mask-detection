# Abstract

This project is a type of deep learning, **a computer vision project.**

At first, I studied about **CNN** and detected whether they were wearing masks.

Then, **transfer learning** was applied to confirm performance improvement.

Finally, **yolo** :rocket: was used to detect for **real-time detection.**

The classes are divided into **three classes(without mask, with mask, invalid mask).**

<br>

## 1. Dataset

- **kaggle**
  - [COVID Face Mask Detection Dataset](https://www.kaggle.com/datasets/prithwirajmitra/covid-face-mask-detection-dataset)
  - [Face Mask Detection ~12K Images Dataset](https://www.kaggle.com/datasets/ashishjangra27/face-mask-12k-images-dataset)
- **Github**
  - [MaskedFace-Net](https://github.com/cabani/MaskedFace-Net)
- **Image crawling**
  - using selenium

## 2. Data preprocessing

- using ImageDataGenerator of keras.preprocessing.image
- edited image in person using code(for yolo)
  - reverse left and right
  - reverse color

## 3. Labeling

- [makesense.ai](https://makesense.ai)

<br>

# References

- https://www.kaggle.com/code/yehoonjoo/mask-or-no-mask

- https://github.com/cabani/MaskedFace-Net
- https://github.com/aleju/imgaug