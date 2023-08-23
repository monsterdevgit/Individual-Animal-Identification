## **Identification of Individual Animals from video**  
This study demonstrates the application of various ML models for the identification of individual animals from video footage. By comparing the performance of different classifiers using confusion matrices and evaluation scores, we can gain insights into the effectiveness of each model for this specific task. The dataset and code provided in the repository allow for further exploration and analysis in the field of individual animal classification.

The following ML models were employed:
1. Largest Prior 
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

Each feature and label data are encoded in an excel csv file. The columns name of the label dataset represents individual animals (class labels), and their corresponding numerical values. These datasets were gotten from original videos and code included in this repository [here](https://github.com/LucyKuncheva/Animal-Identification-from-Video) which were sourced from Pixabay under Pixabay License. Special thanks to Lucy Kuncheva.  

The video data used in this study is summarized below:
| Short Name | Video Name | Frames | Size | Bounding boxes | Identities |
| ---------- | ---------- | ------ | ---- | -------------- | ---------- |
| Pigs | Pigs_49651_960_540_500f.mp4 | 500 | (960, 540) | 6184 | 26 |
| Koi fish | Koi_5652_952_540.mp4 | 536 | (952, 540) | 1635 | 9 |
| Pigeons (curb) | Pigeons_8234_1280_720.mp4 | 443 | (1280, 720)| 4700 | 16 |
| Pigeons (ground) | Pigeons_4927_960_540_600f.mp4 | 600 | (960, 540) | 3079 | 17 |
| Pigeons (square) | Pigeons_29033_960_540_300f.mp4 | 300 | (960, 540) | 4892 | 28 |
