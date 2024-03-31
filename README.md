# CNN--DR-DME-Detection

Project: The manual diagnosis process of DR and DME retinal fundus images by ophthalmologists is time consuming and prone to misdiagnosis. This project uses a Convolutional Neural Network to predict the severity of the Diabetic Retinopathy and Diabetic Macular Edema. 

Model Architecture Information: InceptionResNetV2

Dataset used: Indian Diabetic Retinopathy Image Dataset (IDRiD)
This dataset was available as a part of "Diabetic Retinopathy: Segmentation and Grading Challenge" organised in conjunction with IEEE International Symposium on Biomedical Imaging (ISBI-2018), Washington D.C.

Fundus Camera Specifications:
All of the images were taken with a Kowa VX-10 alpha digital fundus camera, which has a 50-degree field of view (FOV) and is centred near the macula. The photos, which are roughly 800KB in size, are in the jpg file format and have a resolution of 4288×2848 pixels. 
Parts of the dataset:
Segmentation
Original color fundus images(81 images - JPG files)
Groundtruth images for the Lesions(TIF files)
Disease Grading
Original color fundus images(516 images - JPG files)
Groundtruth Labels for Diabetic Retinopathy and Diabetic Macular Edema Severity Grade(CSV file)
Localisation 
Original color fundus images(516 images - JPG files) 
Groundtruth Labels for Optic Disc Center Location(CSV file)
Groundtruth Labels for Fovea Center Location(CSV file)

