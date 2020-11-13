# CapsuleNet-ECE570
Course project for ECE 570 Artificial Intelligence, Purdue University

Which code has been modified? None. Just inspired! 

Which code were you inspired from? 

I had chosen to implement NIPS 2017 publication on ['Dynamic Routing between Capsules'](https://papers.nips.cc/paper/2017/file/2cad8fa47bbef282badbb8de5374b894-Paper.pdf). I was inspired from [Gram-AI's](https://github.com/gram-ai/capsule-networks) repository to originally code myself for my course project implementation on 'Dynamic Routing between Capsules'. This repository consists of 2 sets of 3 different files. It contains the .py and .ipynb notebook files of 

1. Capsule Network over a grayscaled image dataset - MNIST
2. Capsule Network over an RGB image dataset - CIFAR-10
3. Capsule Network over a timeseries dataset - WISDM

How to run datasets? 

You could either import the .ipynb files directly to Google Colab or Jupyter to run the codes cell by cell, or run the .py file as such in your console. For starters, to learn how each function works, I would suggest looking the code cell by cell in the .ipynb notebook. 

This repository will give you an idea about the types of datasets, the Capsule Networks can be used for image / text classification. This is the second implementation of Capsule Network on timeseries dataset directly after [TimeCaps](https://arxiv.org/abs/1911.11800) for ECG data. The segmentation codes present in the 'activity_tracking' file are entirely mine without any inspiration. 

The [WISDM (Wireless Sensor Data Mining)](https://www.cis.fordham.edu/wisdm/dataset.php) consists of 3-axis accelerometer values along with the ground truth on the type of activity performed at a frequency of 20 Hz. The 6 activities performed are: 
1. Walking 
2. Standing
3. Sitting
4. Moving upwards
5. Moving downwards
6. Jogging

