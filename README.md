# -Waterloo-Fall-2020-CS680-Kaggle-competition

Your task is to classify e-commerce products into 27 categories. You will be scored according to classification accuracy (see the "Evaluation" tab on the left). The data includes categorical features, a noisy text description and a noisy image for each product. The dataset and further information about it can be found under the "Data" tab.

The data consists of e-commerce products. Each product as a unique id and a category. Your job is to predict the category of theach product based on categorical features, a noisy text description and a noisy image.

File descriptions
train.csv - the training set
test.csv - the test set
sample_submission.csv - a sample submission file in the correct format
shuffled-images - a directory containing noisy images (filenames are IDs of the corresponding product)
etc...
Data fields
id - a unique id for each product
category - a string describing the category of each product
gender - a string describing the target gender for this product
baseColour - the base colour of this product (note that the base colour may be different than the colour in the image of this product)
season - a string describing the target season for this product
usage - a string describing the target usage for this product
noisyTextDescription - a string of words corresponding to a noisy display name of the product
Images
For each product, there is a noisy image of the product in the directory "shuffled-images". The filename of each image is the product id. The images are 60x80x3 jpeg images in RGB format (i.e., each pixel intensity is an integer in {0,1,2,...,255}).
