# COVIDXNet

COVIDXNet is a convolutional neural network for COVID-19 detection in chest x rays. Please see <https://baknet.herokuapp.com/cnn/covid> for an interactive demonstration of this model. 

This Network requires the dataset obtained from:

<https://www.kaggle.com/nabeelsajid917/covid-19-x-ray-10000-images/data>

This Jupyter Notebook takes the extracted images, splits them randomly into test and train folders, and uses TensorFlow Image Generators to train a deep CNN for COVID detection.


## Installation

To install the required dependencies to your current environment, run:

```bash
$ pip install -r requirements.txt
```
## Usage

The Jupyter Notebook provides step by step execution of the script, with a corresponding explanation of the process.

## Example Models

An example .h5 file have been provided. This has been trained on a GPU and therefore may require GPU enabled TensorFlow to utilise.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Author
My name is Benjamin Kavanagh, and I am an aspiring python developer. Please contact me at benjamin.a.kavanagh@gmail.com for any queries. 