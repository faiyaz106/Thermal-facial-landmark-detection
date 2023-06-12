## This repository uses U-Net Architecture to detect the 54 facial landmarks.
## The facial landmarks are ordered as follows:

<img src= "https://raw.githubusercontent.com/IS2AI/thermal-facial-landmarks-detection/main/figures/land_conf.png"> 

## Requirements
- imutils
- OpenCV
- NumPy
- Pandas
- dlib
- Tensorflow 2

## Training and testing the U-net model
1. **First step is to generate the mask against annotated**: Run the `unet_generate_masks.ipynb` notebook

2. **For training and testing the U-net model**: Run `train_unet_predictor.ipynb` notebook.

3. **Predicting the landmarks**
```
python unet_predict_image.py --dataset dataset/gray --model  models/ 
```


## References:
[SF-TL54: A Thermal Facial Landmark Dataset with Visual Pairs](https://ieeexplore.ieee.org/abstract/document/9708901)


