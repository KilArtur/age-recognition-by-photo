# age-recognition-by-photo
Определение возраста человека по фотографии
Данные взяты с сайта [ChaLearn Looking at People](https://chalearnlap.cvc.uab.cat/dataset/26/description/)

===== APPA-REAL DATABASE =====  
The APPA-REAL database contains 7,591 images with associated  
real and apparent age labels. The total number of apparent  
votes is around 250,000. On average we have around 38 votes  
per each image and this makes the average apparent age very  
stable (0.3 standard error of the mean).  


The images are split into 4113 train,  1500 valid and 1978 test images, provided in the folders train/, valid/ and test/.  
For each image X.jpg, we also provide a corresponding X.jpg_face.jpg  which contains the cropped & rotated face with a 40% margin obtained from the Mathias et. al face detector (http://markusmathias.bitbucket.org/2014_eccv_face_detection/) at multiple rotations.   Furthermore, an X.jpg.mat file is provided with meta-information about the detected face.  

The real age and apparent age ratings are provided in the files gt_train.csv, gt_test.csv and gt_valid.csv, with a separate row for each rating.  

Furthermore, we provide per-image summaries in gt_avg_train.csv, gt_avg_valid.csv and gt_avg_test.csv, showing the number of ratings, average apparent age, standard deviation of apparent age and the real age for each image.  
