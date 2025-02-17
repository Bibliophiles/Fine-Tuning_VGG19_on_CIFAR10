# Fine-Tuning VGG19 on the CIFAR10 Dataset

### Model Overview
<img width="808" alt="Screenshot 2025-02-17 at 16 44 10" src="https://github.com/user-attachments/assets/b7b9e3e9-bd14-418f-b510-e422c8d996c7" />

### Description
This model uses [VGG19](https://www.tensorflow.org/api_docs/python/tf/keras/applications/VGG19) which is an already trained AI model on the
[Imagenet Dataset](https://www.image-net.org/challenges/LSVRC/index.php) as a base-model. It then trains the base-model - taking a number of layers - on the [CIFAR10 DATASET](https://www.cs.toronto.edu/~kriz/cifar.html) to make predictions on 10 classes.  


### Usage
**Clone the Project**

To clone this repository, use the following command:

```bash
git clone https://github.com/Bibliophiles/Fine-Tuning_VGG19.git
