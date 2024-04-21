# PLANT DISEASE IDENTIFICATION USING-CNN
![image](https://github.com/Tanwar-12/PLANT-DISEASE-IDENTIFICATION-USING-CNN/assets/110081008/0b1b85db-1f29-4147-bd11-641cdd5e91fc)![image](https://github.com/Tanwar-12/PLANT-DISEASE-IDENTIFICATION-USING-CNN/assets/110081008/fdf2ecf7-63ec-45b0-a5b8-f6eae129b586)
## **INTRODUCTION**
**This project is an approach to the development of plant disease recognition model, based on leaf image classification, by the use of deep convolutional networks. The developed model is able to recognize 38 different types of plant diseases out of of 14 different plants.**
* Plants: 'Tomato',  'Apple',  'Blueberry',  'Grape', 'Peach', 'Corn', 'Cherry', 'Squash', 'Strawberry', 'Pepper', 'Orange', 'Potato', 'Raspberry', 'Soybean'

### **THE DATASET CONTAINS**:
* 70295 training images
* 17572 testing images

### **WORKFLOW:**
1. **Loading the images from the folder resizing them into 128 * 128 (256 * 256 takes time for processing) and coverting them to tensors** 
2. **Building a validation dataset using 0.3% of the total dataset.**
3. **Loading the data using Batches**
4. **Trying various CNN architecture**
  * Combination of Multilayer CNN with Linear Layers
  * VGG16 using Transfer Learning
  * Resnet34 using Transfer Learning
  * 5. **Selecting the device and loading the data into device i.e (GPU)** 
6. **Training the model and evaluating the model on test data**
7. **Saving the Model**
## NUMBER OF UNIQUE PLANTS
* Number of Unique Plants:  14
**Unique Plants:**  ['Strawberry', 'Blueberry', 'Potato', 'Pepper,', 'Apple', 'Tomato', 'Peach', 'Soybean', 'Grape', 'Squash', 'Corn', 'Cherry', 'Raspberry', 'Orange']

  ## LOADING TRAIING & TEST DATASET AS TENSOR

  ### NUMBER OF CLASSES: 38
  ### VISUALISING A SINGLE IMAGE

![image](https://github.com/Tanwar-12/PLANT-DISEASE-IDENTIFICATION-USING-CNN/assets/110081008/106e5802-c04a-49e1-9a50-62c4d80589c3)

  ### VALIDATION DATASET & DATALOADER
  ## VISUALISE A BATCH OF IMAGES

   ![image](https://github.com/Tanwar-12/PLANT-DISEASE-IDENTIFICATION-USING-CNN/assets/110081008/ced53d41-45dc-41ac-bb53-7b657667ff80)


## BUILDING A CNN MODEL
![image](https://github.com/Tanwar-12/PLANT-DISEASE-IDENTIFICATION-USING-CNN/assets/110081008/28472d6a-0748-4362-aea7-72b009ddf77e)


#### BUILDING A VGG16 MODEL USING TRANSFER LEARNING

####  BUILDING A RESNET34 MODEL USING TRANSFER LEARNING



 ###  TRAINING THE MODEL
 


 ###  PLOTTING ACCURACY & LOSSES
 ![image](https://github.com/Tanwar-12/PLANT-DISEASE-IDENTIFICATION-USING-CNN/assets/110081008/c6b76d2e-0c05-4b04-ab0a-5a07b80329a6)

 ![image](https://github.com/Tanwar-12/PLANT-DISEASE-IDENTIFICATION-USING-CNN/assets/110081008/a0c63306-786a-4db7-9fcc-849f05b6f25e)



###  EVALUATION & PREDICTION ON TEST DATA
ACCURACY OF THE MODEL ON TEST DATA : 98.420%
### PREDICTION ON SOME SINGLE IMAGE OF TEST DATA
![image](https://github.com/Tanwar-12/PLANT-DISEASE-IDENTIFICATION-USING-CNN/assets/110081008/ceaa158a-c9b6-46b2-98d2-23616aa4b48b)
![image](https://github.com/Tanwar-12/PLANT-DISEASE-IDENTIFICATION-USING-CNN/assets/110081008/a4b17f10-26ff-411f-bae3-b46da49282e2)
![image](https://github.com/Tanwar-12/PLANT-DISEASE-IDENTIFICATION-USING-CNN/assets/110081008/7fba85ba-840f-41cb-bb7a-789ded4a3559)




 ## SAVING THE MODEL
