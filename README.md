# ScenceRecognition
### CTPN+CRNN
This project is besed on [text-detection-ctpn](https://github.com/qq919056489/text-detection-ctpn) and [sceneReco](https://github.com/bear63/sceneReco).
## environment
- [x]  ubuntu16.04

- [x]  anaconda3

- [x] opencv3

- [x] tensorflow

- [x] pytorch

- [x] warp_ctc_pytorch

## about paper
CTPN:[Detecting Text in Natural Image with
Connectionist Text Proposal Network](https://arxiv.org/pdf/1609.03605.pdf)

CRNN:[An End-to-End Trainable Neural Network for Image-based Sequence Recognition and Its Application to Scene Text Recognition](https://arxiv.org/pdf/1507.05717.pdf)

## How to use
There has three directories and a file at the root directory of this project:

type | name | description
---|---|---
directory|ctpn|the module of ctpn
directory|crnn|the module of crnn
directory|imgs|the images that will be processed
file|demo.py|the main function of this project

# First

Download the model for crnn from baidu yun:[here](https://pan.baidu.com/s/1nvBV5FV).Then put it into **crnn/models**

# Second

There are two methods to run this project.

- If you want to recognize man
