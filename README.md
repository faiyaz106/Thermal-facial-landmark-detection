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
For training and testing the U-net model, open the `train_unet_predictor.ipynb` notebook and run cells.

4. **U-net model**
```
python unet_predict_image.py --dataset dataset/gray/test --model  models/ 
```





## References:
[SF-TL54: A Thermal Facial Landmark Dataset with Visual Pairs](https://ieeexplore.ieee.org/abstract/document/9708901)


