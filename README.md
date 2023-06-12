# SF-TL54: Thermal Facial Landmark Dataset with Visual Pairs
The dataset contains 2,556 thermal-visual image pairs of 142 subjects with manually annotated face bounding boxes and 54 facial landmarks. The dataset was constructed from our large-scale [SpeakingFaces dataset](https://github.com/IS2AI/SpeakingFaces).

<img src= "https://raw.githubusercontent.com/IS2AI/thermal-facial-landmarks-detection/main/figures/example.png"> 


## The facial landmarks are ordered as follows:

<img src= "https://raw.githubusercontent.com/IS2AI/thermal-facial-landmarks-detection/main/figures/land_conf.png"> 

## Download the repository:
```
git clone https://github.com/IS2AI/thermal-facial-landmarks-detection.git
```
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





## Link for research paper from which U-Net Architecture trained for facial landmark detection
[SF-TL54: A Thermal Facial Landmark Dataset with Visual Pairs](https://ieeexplore.ieee.org/abstract/document/9708901)


