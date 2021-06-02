# Fruit-rotten-or-not
Identify weather the fruit in the photo is rotten or fresh using Image classification.


## Aim of the project

    1. To Identify which fruit is in the picture.(Classification)
    2. Also detects weather the fruit is rotton or not.
    3. Uses a webbased interface developed using flask, HTML, javascript, CSS and Bootstrap.

Note: Kindly do not push any changes to Main or Master Branch. Create a New Branch and push all the changes to that branch.



# Table Content
* About Project
* Dataset
* Language or Framework used
* Setup



## About Project

First the input image will be provided to the model using the web interface then the image will be classified into its fruit type and weather it is rotten or not

This project is based on deep learning / neural networking which is a sub-branch of machine learning.
Deep learning is an artificial intelligence (AI) function that imitates the workings of the human brain in processing data and creating patterns for use in decision making.  
This project will detect weather weather the fruit is rotten or not by processing the provided picture of fruit using deep learning.


## Dataset

This dataset is divided into two sub parts :
* Training dataset
* Testing dataset

The training dataset contains a total of 1212 images and the testing data set contains a total of 300 images.
<br>
<br>

Each of these data sets are further divided into 6 more sub types :
* Fresh Apples
* Fresh Banana
* Fresh Oranges
* Rotten Apples
* Rotten Banana
* Rotten Oranges


## Language and Framework used

* Python: language
* NumPy: library for numerical calculations
* Pandas: library for data manipulation and analysis
* Tensorflow: library for large numerical computations without keeping deep learning in mind
* Keras: neural network library
* Flask: It is a micro web framework written in Pythonn used for web based applications 


## Setup
1. Clone the repository.
2. If you are working on a local machine then :
    * Create an active virtual environment for the project. 
            
    * Install all the necessary libraries mentioned above using the command :
                ```$ pip install```
    
3. Code Orange detection.ipynb in your local machine and save the model.
4. Make the necessary changes in app.py and other template files.
5. Run the command :
                ``` python "app.py" '''
6. Now your webserver will be up and running.
7. Paste the web address from the terminal to your web browser to use the app.
