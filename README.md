# Signature Verification using different Neural Networks

This project aims to explore different neural networks for signature verification. Five types of neural networks are implemented and compared, including Convolutional Neural Networks (CNN), Siamese Neural Networks (Siamese NN), Recurrent Neural Networks (RNN), Convolutional Recurrent Neural Networks (C-RNN), and Bidirectional Recurrent Neural Networks (B-RNN).

Three publicly available datasets are used for training and evaluation: Kaggle Datasets, CEDAR Dataset, and ICDAR Dataset.

## Requirements

* Python 3.6 or later
* TensorFlow 2.0 or later
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook (optional)

## Installation

* Clone this repository: ```git clone https://github.com/yourusername/signature-verification.git```
* Install the required packages: ```pip install -r requirements.txt```


## Usage

* Download the datasets from the following sources:
	* Kaggle Datasets: https://www.kaggle.com/divyanshrai/handwritten-signatures
	* CEDAR Dataset: https://cedar.buffalo.edu/NIJ/data/signature/index.html
	* ICDAR Dataset: https://www.iapr-tc11.org/mediawiki/index.php/ICDAR_2011_Signature_Verification_Competition_(SigComp2011)

* Preprocess the datasets (e.g., resizing, normalization) using the preprocess.py script.

* Train the neural networks. Choose the desired network architecture and dataset using command-line arguments.

* Evaluate the trained model.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

* The authors of the CEDAR and ICDAR datasets for providing the data.
* The TensorFlow team for providing the software library for training and deploying machine learning models.
