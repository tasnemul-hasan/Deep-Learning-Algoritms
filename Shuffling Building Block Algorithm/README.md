Datasets used to test this architecture:

## Microscopic Image Dataset
Blood sample of 150 P. falciparum-infected and 50 healthy patients were collected by a research team at Chittagong Medical College Hospital, Bangladesh. The images were then annotated manually in Bangkok. The complete dataset is provided by Lister Hill National Center for Biomedical Communications (LHNCBC) which is a part of National Library of Medicine (NLM). This dataset contains 2 classes, Parasitized infected cell and Uninfected cell. The classes have balanced distribution containing 13,780 Blood Cell images per class. All the images are in PNG format with different pixels size.


## MRI Image Dataset
The dataset is consisting of three classes of tumor images- Glioma (926 Images), Meningioma (937 Images) and Pituitary (901 Images). All the images are in JPG format but in different pixels size. This open-source dataset is collected from Kaggle website.


## pathMNIST Image Dataset
pathMNIST is one of ten open medical datasets of MedMNIST. The dataset was very large for the hardware we had during the training process. It took a very long time to train one architecture. That’s why with this architecture we only trained one of our proposed architecture “SPE” which has minimum trainable parameter (3,877,277). We have trained the model in two methods - using pre-processed ready to train PathMNIST dataset direct from the source and using our custom shuffling & splitting method. We used custom shuffling & splitting method to remove any bias in the dataset.


## Xray Image Dataset
We have created a custom dataset that contains four classes of chest X-Ray images- Covid-19, Lung Opacity, Normal and Pneumonia. And each class has 3,560 images. It is a combination of 2 open-source datasets which are taken from Kaggle website. The dataset of Covid-19, Lung Opacity and Normal is created by a team of researchers and medical doctors from around the world and became the Winner of Kaggle Community Dataset Award for COVID-19. The images are in 299 x 299 pixels and in PNG format. And the “Pneumonia” images are in different pixels and in JPEG format.
