
# Image Classification Web App

This is a simple Flask web application that uses a pre-trained neural network to classify images into one of three categories: Adidas, Converse, or Nike. Users can upload an image and the model will predict which category the image belongs to.

## Requirements

To run this web app, you will need:

- Python 3.6 or higher
- Flask 1.1.2 or higher
- TensorFlow 2.0 or higher
- Numpy
- Pillow

You can install these dependencies using pip:

pip install flask tensorflow numpy pillow


## Usage

To start the web app, run the following command in your terminal:

python app.py

This will start the Flask server on `http://localhost:5000/`. You can then open a web browser and go to `http://localhost:5000/` to access the web app.

## File structure

The file structure of this project is as follows:

app.py # Flask web app code

saved_model/ # Pre-trained neural network model

static/ # Static files (CSS, JS, images)

templates/ # HTML templates

README.md # Project description and instructions


## Credits

The pre-trained neural network used in this web app was created using TensorFlow and the [Keras API](https://keras.io/). The image dataset used to train the model was obtained from [Kaggle]([https://www.kaggle.com/datamine/adidas-converse-nike](https://www.kaggle.com/datasets/die9origephit/nike-adidas-and-converse-imaged)). 



