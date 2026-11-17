# Practical 1: Study of Deep Learning Packages

- TensorFlow
- Keras
- Theano
- PyTorch
- Distinct features and functionality of each package

# Practical 2: Feedforward Neural Network using Keras and TensorFlow

- Import necessary packages
- Load training and testing data
- MNIST / CIFAR10 dataset
- Define network architecture using Keras
- Train the model using SGD
- Evaluate the network
- Plot training loss
- Plot training accuracy

# Practical 3: Image Classification Model

- Loading image data
- Preprocessing image data
- Defining model architecture
- Training the model
- Estimating model performance

# Practical 4: Autoencoder for Anomaly Detection

- Import required libraries
- Upload / access dataset
- Encoder
- Latent representation
- Decoder
- Reconstruction of original input
- Optimizer
- Loss function
- Evaluation metrics
- Anomaly detection

# Practical 5: Continuous Bag of Words (CBOW) Model

- Data preparation
- Generate training data
- Train the CBOW model
- Generate output

# Practical 6: Object Detection using Transfer Learning of CNN Architectures

- Load a pre-trained CNN model
- Pre-trained model trained on a large dataset
- Freeze lower convolutional layer weights
- Add custom classifier
- Train classifier layers
- Fine-tune hyperparameters
- Unfreeze additional layers
- Fine-tune the model

# Windows

```bash
python -m venv dl_env
dl_env\Scripts\activate
python -m pip install --upgrade pip
pip install jupyter ipykernel
pip install tensorflow
python -m ipykernel install --user --name=dl_env --display-name "Python (Deep Learning)"
jupyter notebook
```

# Ubuntu

```bash
sudo apt update
sudo apt install python3 python3-pip python3-venv -y
python3 -m venv dl_env
source dl_env/bin/activate
python -m pip install --upgrade pip
pip install jupyter ipykernel
pip install tensorflow
python -m ipykernel install --user --name=dl_env --display-name "Python (Deep Learning)"
jupyter notebook
```
