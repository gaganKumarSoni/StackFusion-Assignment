# StackFusion-Assignment
Number Plate Detection and Extracting Text from it

The NumberPlateOCR.ipynb notebook contain code to build the dataset, train the cnn on it.
The dataset is build using mnist and A-Z Handwritten Alphabet dataset.
The data feeded to network for prediction is firstly pre processed using openCV techniques which allows to extract only number plate region of image.
After extracting only number plate region using openCv the text is then isolated into characters form.
Finally the trained network will then use to make prediction on character extracted from openCv technique.
