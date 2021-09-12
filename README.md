#  histopathology images classification-Deeplearn
**About**

The goal of this project is to train a DNN model, using images of colorectal cancer histology inorder to classifiy histopathology images.
Another goal is to display the classification results clearly,side by side with the original histopathology image, using color-class correlation, alogside tumer epithelium

**The Data**
* 5000 colorectal histology images, 150x150 RGB, classified
![Class labels](https://user-images.githubusercontent.com/78749321/132136482-c52c142e-7ae7-4eb2-99f7-49c137457bb1.png)

* 10 histopathology images, 5000x5000 RGB, unclassified

**The Steps**
* Part 1- Loading the 5000 colorectal cancer histology images data from Keras and processing them for ease of use/training
* Part 2- Training several models, using diffrent architectures/data augmentation/techniques, all the models are VGG16 or VGG-like
* Part 3- Plotting and showing confusion matrix together with the acticated features in the optimal model
* Part 4- color the large histopathology images(5000x5000x3) and Displaying the classification results,tumer epithlium alogside the original image

**Results**

* a VGG16 with a new top, transfer/fine-tune learning technique and data agumentation the model achieve 94.6% test accuracy 

![image](https://user-images.githubusercontent.com/78749321/133000765-d65df6ed-f6fd-4d61-874b-02a7f8f951f0.png)
![image](https://user-images.githubusercontent.com/78749321/133000826-0e46c207-3b9a-4ade-a66c-74c2043aacd9.png)
![image](https://user-images.githubusercontent.com/78749321/132359182-95f32b76-9777-48d0-a497-7a13c524bf43.png)



