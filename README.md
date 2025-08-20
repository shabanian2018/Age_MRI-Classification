# 2D-CNN & 2.5D-CNN & 3D-CNN_MRI-Classification
2D CNN and 3D CNN models for MRI multi-classification using 5fold cross validation.
On the task of classifying infants into age groups based on T1w, T2w, and PD images, several architectures of 2D and 3D CNN were explored and compared to Transfer Learning using ResNet50 and Inception, among others.

The dataset consists of 89 patients, out of which several had more than one image taken in one or more ages. All images are NIfTI


3D CNN architecture for early fusion
![](images/3D_fusion_model.jpg)



Confusion matrices for (a) 2D, (b) 3D fusion CNN
![](images/2D_3D_fusion_kfold.png)


## 🚀 How to Cite
Shabanian, Mahdieh, Eugene C. Eckstein, Hao Chen, and John P. DeVincenzo. "Classification of neurodevelopmental age in normal infants using 3D-CNN based on brain MRI." In 2019 IEEE international conference on bioinformatics and biomedicine (BIBM), pp. 2373-2378. IEEE, 2019.

@inproceedings{shabanian2019classification,
  title={Classification of neurodevelopmental age in normal infants using 3D-CNN based on brain MRI},
  author={Shabanian, Mahdieh and Eckstein, Eugene C and Chen, Hao and DeVincenzo, John P},
  booktitle={2019 IEEE international conference on bioinformatics and biomedicine (BIBM)},
  pages={2373--2378},
  year={2019},
  organization={IEEE}
}
