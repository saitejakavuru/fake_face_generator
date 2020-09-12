<h3 align="center">
  <img src="assets/face_generator_icon_web.png" width="300">
</h3>

# Face Generator

Python notebook containing TensorFlow DCGAN implementation. It was trained on a [Celebrities](https://www.kaggle.com/greg115/celebrities-100k) dataset.

Check out corresponding Medium article: [Face Generator - Generating Artificial Faces with Machine Learning 🧑](https://towardsdatascience.com/face-generator-generating-artificial-faces-with-machine-learning-9e8c3d6c1ead).

Check out corresponding Kaggle kernel: [Face Generator](https://www.kaggle.com/greg115/face-generator-dcgan-celebrities).


## DCGAN
Network architecture by [Radford et al., 2015](https://arxiv.org/abs/1511.06434).
<img src="assets/model.png">

## Training
Visualization of training with the following hyperparameteres.
<img src="assets/epochs.gif">

	DATASET_SIZE = 100000
	IMAGE_SIZE = 128
	NOISE_SIZE = 100
	LR_D = 0.00004
	LR_G = 0.0002
	BATCH_SIZE = 64
	EPOCHS = 20
	BETA1 = 0.5
	WEIGHT_INIT_STDDEV = 0.02
	EPSILON = 0.00005
Here considering the computational power, we will be running only 20 epochs ratehr than 60 epochs. Instead you can view the result after running 60 epochs which has been ran on a different machine with higher computational capability.

## Results

Generated samples after 60 epochs of training.

<img src="assets/final_grid.png">





