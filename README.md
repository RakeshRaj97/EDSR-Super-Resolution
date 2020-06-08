# EDSR-Super-Resolution
This repository is an implementation of EDSR model using PyTorch 
Check the official [code](https://github.com/thstkdgus35/EDSR-PyTorch) and [paper](http://openaccess.thecvf.com/content_cvpr_2017_workshops/w12/papers/Lim_Enhanced_Deep_Residual_CVPR_2017_paper.pdf)
(The video input/output super-resolution will be added soon to the Master branch) 

This model was trained on NVIDIA P100 with ~4500 annotated satellite Low Resolution image pathches which were obtained by Image degradation and Image downsampling of the High Resolution images. You can download the dataset which I used for training the model [here](https://drive.google.com/drive/folders/1dbqh0lo5YAKhuPBXOlcUGsew5pL0T33O?usp=sharing)

# Required Dependencies
* Python 3.6
* PyTorch >= 1.0.0
* Pillow
* Utility
* Imageio
* tqdm
* scikit-image
* OpenCV (Only for Video input/output)
* matplotlib

# Quickstart (Demo)
You can test the pretrained model **EDSR_baseline_x2** by placing the images in `test` folder. The supported formats are **png** and **jpeg** files. The pretrained model can be downloaded using this [link]()

Run the script in `src` folder. Uncomment the appropriate line in `demo.sh` to test your image.
`sh demo.sh` 
The output images can be found under `experiment/test/results-Demo` folder.

# Output of the trained model

![image](https://user-images.githubusercontent.com/47710229/84050300-e1936580-a9f0-11ea-8a14-2e6236964ee7.png)

