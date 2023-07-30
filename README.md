## **A study on Individual Animal identification from video**  
The varied physical characteristics of animals present distinct obsatcles for traditional visual systems. 
This study offers an examination of the performance of various classifiers in the identification of individual animals through the analysis of their collective characteristics.  
The study aims to contribute to the study of Animal classifiction by evaluating and comparing the effectiveness of various classifiers: 
1. Largest Prior classifier
2. Linear Discriminant Analysis
3. K-Nearest Neighbour
4. Decision Tree
5. Support Vector Machine
6. Bagging
7. Random Forest.


### Data Description:
The dataset consists of label and features data. With four feature representations consisting of:  
* RGB features (colour)
* H10 - hue histogram features (colour)
* HOG features (shape)
* LBP features (texture)

Each feature and label data are encoded in an excel csv file. The columns name of the label dataset represents individual animals (class labels), encoded to numerical values. These datasets were gotten from original videos and code included in this repository [here](https://github.com/LucyKuncheva/Animal-Identification-from-Video) which were sourced from Pixabay under Pixabay License. Special thanks to Lucy Kuncheva.  

The video data used in this study is summarized below:
| Short Name | Video Name | Frames | Size | Bounding boxes | Identities |
| ---------- | ---------- | ------ | ---- | -------------- | ---------- |
| Pigs | Pigs_49651_960_540_500f.mp4 | 500 | (960, 540) | 6184 | 26 |
| Koi fish | Koi_5652_952_540.mp4 | 536 | (952, 540) | 1635 | 9 |
| Pigeons (curb) | Pigeons_8234_1280_720.mp4 | 443 | (1280, 720)| 4700 | 16 |
| Pigeons (ground) | Pigeons_4927_960_540_600f.mp4 | 600 | (960, 540) | 3079 | 17 |
| Pigeons (square) | Pigeons_29033_960_540_300f.mp4 | 300 | (960, 540) | 4892 | 28 |
