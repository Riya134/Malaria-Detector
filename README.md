# Malaria-Detector
Malaria-Detection-using-Keras
This project uses Keras to detect Malaria from Images. The model used is trained from scratch. The dataset is obtained from the National Library of Medicine. It can be available here:https://lhncbc.nlm.nih.gov/publication/pub9932. The images in this dataset is divided into to categories:

### Parasitized 

### Uninfected</br>

[![Parasitized and Uninfected Cells](https://miro.medium.com/max/2632/1*dEu2ZRQZUMQE3bejURfO7g.png)]

Below are the steps:-</br>
1.Upload Image: The user can upload the medical test image through a workstation running on Windows OS. The image should be in jpeg, png or jpg format.</br>
2.Read Image: The image will be scanned before augmentation takes place.</br>
3.Evaluate image using saved model: The saved custom model creates a feature map of the uploaded medical test image and predicts the output.</br>
4.Determine and Analyze the Output: The predicted output is then analyzed and converted to a user friendly language.</br>
5.Display the Output: The analyzed result is then displayed to the user.

