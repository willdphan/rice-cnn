# Rice CNN

## Description

Rice, which is among the most widely produced grain products worldwide, has many genetic varieties. These varieties are separated from each other due to some of their features. These are usually features such as texture, shape, and color. With these features that distinguish rice varieties, it is possible to classify and evaluate the quality of seeds. 

In this study, Arborio, Basmati, Ipsala, Jasmine and Karacadag, which are five different varieties of rice often grown in Turkey, were used. A total of 75,000 grain images, 15,000 from each of these varieties, are included in the dataset. A second dataset with 106 features including 12 morphological, 4 shape and 90 color features obtained from these images was used.

This notebook focuses on the rice image dataset on [Kaggle](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset), consisting of images of different rice varieties. The objective is to develop a machine learning model for accurate classification of rice images into their respective categories.

## Objective
The goal is to build a robust machine learning model capable of accurately classifying rice images into their respective varieties. This can assist in various applications such as agricultural research, crop management, and quality control in the rice industry.

## Steps to CNN
1. Import Libraries
2. Open Dataset and Define Classes
3. Get Image and Data Size
4. Define Device
5. Define Hyperparameters
6. Create Transform Variable
7. Split into Train, Test, Valid Datsets
8. Use DataLoader for Batch Size
9. Display Images
10 CNN Model
11. Save Model to Device
12. Define Loss and Optimizer
13. Train Function
14. Validation Function
15. Define Loss Function and Optimizer
16. Test Model with Image from Test Dataset


[Code](Rice_Classifier_CNN.ipynb)

## License

This script is open-source and licensed under the MIT License. For more details, check the [LICENSE](LICENSE) file.
