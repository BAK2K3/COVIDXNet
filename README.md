# COVIDXNet

COVIDXNet is a convolutional neural network for COVID-19 symptom detection in chest x rays. Please see <https://baknet.herokuapp.com/cnn/covid> for an interactive demonstration of this model. 

This Network requires the "generated_dataset" obtained from the script here:

<https://www.kaggle.com/nabeelsajid917/covid-19-x-ray-10000-images/data>

This Jupyter Notebook takes the extracted images, splits them randomly into test and train folders, and uses TensorFlow Image Generators to train a deep CNN for COVID detection.

## Disclaimer
THIS IS A LEARNING PROJECT, NOT TO BE USED FOR RELIABLE MEDICAL ADVICE OR DIAGNOSIS. THIS HAS NOT BEEN SUBJECT TO GOVERNMENT OR MEDICAL TESTING, AND SHOULD NOT BE USED FOR RELIABLE SELF DIAGNOSIS. 


## Installation

To install the required dependencies to your current environment, run:

```bash
$ pip install -r requirements.txt
```
## Usage

The Jupyter Notebook provides step by step execution of the script, with a corresponding explanation of the process.

The dataset from the above kaggle link must be named "generated_dataset", as per the script description, and this folder must be placed in the root of this notebook.

## Example Models

An example .h5 file have been provided. This has been trained on a GPU and therefore may require GPU enabled TensorFlow to utilise.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Contact
Please contact me at benjamin.a.kavanagh@gmail.com for any queries. 