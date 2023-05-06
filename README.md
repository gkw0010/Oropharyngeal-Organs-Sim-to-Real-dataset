# Endoscopic Images generated from SOFA-based oropharynx model with style transfer from phantom (EISOST)
EISOST is a Sim-to-Real oropharyngeal organs segmentation dataset, including 1397 labeld images. The dataset consists of 3 necessary oropharyngeal organs, namely, the uvula, epiglottis, and glottis. Training data includes 1194 images sampled from SOFA-based oropharynx model. Test data includes 203 images captured on a real-world phantom. For the annotations, we provide coarse and fine annotations at the pixel level, including instance-level labels for oropharyngeal organs.
![Image text](https://github.com/gkw0010/EISOST-Sim2Real-Dataset-Release/blob/main/Representative_image.png)

# Image Style-Transfer for Domain Adaption
To reduce the differences between two datasets, we try to introduce style-transfer method. With the help of ArtFlow, we convert the appearance of virtual images into real oropharyngeal organs’ appearance, thereby enhancing the sense of photo-realistic of virtual data while preserving useful anatomical features for model training.
The results of the representative image style-transfer and the corresponding styles are shown below.
![Image text](https://github.com/gkw0010/EISOST-Sim2Real-Dataset-Release/blob/main/Style-Transfer.png)

# Download
[[source_img](https://drive.google.com/file/d/1GWg8y4FDFwNznIRi0AaoqYuT8RNN-kKn/view)]
[[target_img](https://drive.google.com/file/d/1ZI9vwpyDGuzp0poWIfUKoatWRAOvCoUl/view?usp=sharing)]
[[trans_img](https://drive.google.com/file/d/1ZPi29nl1sgoKsoUO6_ESrMdp8o6GYnHs/view?usp=sharing)]

 # Attention
EISOST dataset is free for research purpose only. For any questions about the dataset, please contact: gkwang@link.cuhk.edu.hk.
