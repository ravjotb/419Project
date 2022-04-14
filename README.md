# Detecting Cringe Facial Expressions

## About the Project

The use of the word cringe to describe uncomfortable, awkward, and even embarrassing phenomena has become increasingly popular in Western society. Currently, there is limited research around the facial expression that is induced by modern cringe definitions, making it hard to distinguish from neighboring expressions. We address this by differentiating action units induced from cringe-worthy scenarios to other nearby social signals, such as pain and disgust. We collected dynamic samples of facial expressions as a result of cringe, pain, and disgust and trained a Support Vector Machine using this data.

### Built With
* Python
* FFMPEG
* OpenFace

## Getting Started

Since this code is saved as IPYNB files, the best way to run the code would be to download Jupyter Notebook and Python3. This allows the user to clearly distinguish different sections of the code and better understand the project in its entirety. 

The three files that contain the project code are CringevsPain.ipynb, CringevsDisgust.ipynb, and CringevsPainvsDisgust.ipynb. The first of these files attempts to detect cringe facial expressions from pain facial expressions. Similarly, the second file compares cringe facial expressions with disgust facial expressions. Finally, the last file tries to detect between the three different types of facial expressions. 

The dynamic data has already been collected from sources, such as YouTube and Giphy. In addition, this data has been processed through OpenFace, which extracts features such as action units, from the videos. The dynamic samples were edited and cropped so that only one face is annotated per sample. The FeatureExtraction.ipynb is the code used to run samples through OpenFace. This file first installs OpenFace and then passes in the relevant mp4 files. This dataset is available in the Dataset(.csv) folder where the csv files are separated for each emotion. 

### Example Data
#### Cringe

https://user-images.githubusercontent.com/51034700/163469103-f6d10550-39be-4373-b513-7fc15c4703a5.mp4

#### Pain

https://user-images.githubusercontent.com/51034700/163468905-1bf3b816-e044-4f8d-a306-c955b7893f88.mp4


## Self Evaluation



