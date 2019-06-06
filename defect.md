## Wafer defect detection and recognition
This project focuses on locating defects in the SEM images and recognizing their types.
For locating defects in the images, we utilize the well-known hypothesis generation (HG) and verification (HV) strategy.
In HG, defect candidates are obtained through [AdaBoost](https://en.wikipedia.org/wiki/AdaBoost) wth [LBP](https://en.wikipedia.org/wiki/Local_binary_patterns) features. In HV, we verify defect candidates by [SVM](https://en.wikipedia.org/wiki/Support-vector_machine) with [HOG](https://en.wikipedia.org/wiki/Histogram_of_oriented_gradients) features.

### Demonstration
 [![Wafer defect detection](https://img.youtube.com/vi/EuYogvaseMo/0.jpg)](https://www.youtube.com/watch?v=EuYogvaseMo)
