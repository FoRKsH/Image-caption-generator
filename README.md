# Image Caption Generator 
Generating captions using CNN & RNN

## Code is divided into 2 parts
### Part 1 : Download and prepare data for training (ON CPU TAB) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FoRKsH/Image-caption-generator/blob/main/Project%202%20Prepare%20Data.ipynb)
- Data was resized to freeup space (since colab in GPU tab doesn't offer large disk space )
- Passed through ResNet50 and extract feature map ( better use gpu for faster extraction )
- Dump all files and variables created into MagicFile.F for part 2

### Part 2 : Training and Testing (ON GPU TAB) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FoRKsH/Image-caption-generator/blob/main/Project2%20Train%20Model.ipynb)
- Load the MagicFile.F which include all dataset, important variables ... etc
- prepare Model
- Start Training 
- Testing the Model

## About the project
- This project is done as the second project of udacity computer vision nanodegree course
- Keras is mainly used ( on the course pytorch was recommended ! )
- COCO Dataset 2017 is used for the training process
- Training process was fully done on Google Colab 

