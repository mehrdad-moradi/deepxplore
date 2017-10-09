# DeepXplore

## Prerequisit
### Python
The code should be run using python 2.7.12
Latest to date (Tensorflow 1.3.0 and Keras 2.0.8) is supported

### Tensorflow
```bash
sudo pip install tensorflow
```
if you have gpu,
```bash
sudo pip install tensorflow
```
and then follow the instructions [here](https://www.tensorflow.org/install/install_linux) under *NVIDIA requirements to run TensorFlow with GPU support*

### Keras
```bash
sudo pip install keras
```

### Mimicus
Install from [here](https://github.com/srndic/mimicus)

## File structure
+ **MNIST** - MNIST dataset
+ **ImageNet** - ImageNet dataset
+ **Driving** - Udacity self-driving car dataset
+ **PDF** - Benign/malicious PDFs captured from VirusTotal/Contagio/Google provided by Mimicus
+ **Drebin** - Drebin Android malware dataset

# To run
Run
```bash
python neuron_coverage.py
```
In every directory

# Note
The trained weights are provided in each directory (if required).
Drebin's weights are too large, downladed [here](https://drive.google.com/open?id=0B5zIleLkN9FAS0pySkM2d3pzRXM)
