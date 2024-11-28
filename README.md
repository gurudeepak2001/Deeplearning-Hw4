# Deeplearning-Hw4
Home Work 4
This repository provides implementations of three Generative Adversarial Network (GAN) models: DCGAN (Deep Convolutional GAN), WGAN (Wasserstein GAN), and ACGAN (Auxiliary Classifier GAN), trained on the CIFAR-10 dataset. These models showcase different techniques to generate high-quality synthetic images and address common challenges like mode collapse and instability.

- dcganhw4_Deepak.ipynb: Contains the detailed implementation of DCGAN, including architecture, layers, hyperparameters, and FID scores analysis.

wgan_Deepak.ipynb: Contains the implementation of WGAN, focusing on the Wasserstein loss and stability improvements. The file includes performance metrics and FID evaluations.

acgan_deepak (1).ipynb: Includes the implementation of ACGAN with class labels for conditional generation. The notebook tracks both adversarial and classification losses along with FID score analysis.

FID_Performance.ipynb for the performance comparision of the three models.

Installation and Testing

Clone the Repository:

git clone <repository-url>

Install Dependencies:

pip install -r requirements.txt

Run the Notebooks: Use Jupyter Notebook to run the .ipynb files sequentially for training.

Evaluation

FID scores are tracked to evaluate and compare model performance in generating realistic images.




