###  Project Overview
<img src="https://github.com/m4556/neural_image_captioning/blob/main/img/sample.png" width="600" >
This project is demonstration of  neural network architecture with both CNNs and LSTMs to automatically generate captions from images.

### Model architecture
The core architecture used to achieve this task follows an encoder-decoder architecture, where the encoder is a pretrained Inception, and the decoder is a basic one-layer LSTM.

<img src="https://github.com/m4556/neural_image_captioning/blob/main/img/encoder-decoder.png" width="1200" >

### Setup

##### 1. Clone the Repository:  
git clone https://github.com/m4556/neural_image_captioning.git  
cd neural_image_captioning

##### 2. Create Conda Environment:
Create and activate the environment using the following commands:  
conda create --n lang_translation_env  
conda activate lang_translation_env

##### 3. Dataset:
Download the dataset [flickr8k](https://www.kaggle.com/dataset/e1cd22253a9b23b073794872bf565648ddbe4f17e7fa9e74766ad3707141adeb).
Place the downloaded dataset in the same folder

##### 4. Install Dependencies:  
pip install -r requirements.txt

##### 5. Run code: 
Run below file to start training the model:  
python train.py 




