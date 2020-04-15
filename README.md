# DogBreed-Image-Classifier
## Description
In these notebooks we build convolutional neural networks with TensorFlow/Keras. One notebook does it from "scratch" and the other utilizes Transfer Learning with the pretrained Xception network.

The accuracy difference between both approaches is huge:

|Notebook       | Accuracy|
| :------------- |:-------------:|
| DogBreed Classifier.ipynb| 37 %|
| DogBreed Classifier TransferLearning.ipynb| 94 %|

## Dataset
The dataset, called ![ImageWoof](https://github.com/fastai/imagenette), is a subset of dog pictures from ImageNet and consists of 10,000 training and 3,000 test data. It contains the dog breeds
* Australian Terrier
* Border Terrier
* Samoyed
* Beagle
* Shih-Tzu
* English Foxhound
* Rhodesian Ridgeback
* Dingo
* Golden Retriever
* Old English Sheepdog.
