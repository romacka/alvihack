# Alvihack

# Predict the movement of fingers from muscle activity.

## Data:

input: 8 channel EMG signal\
output: 3D Hand position (Hand Tracking Oculus Quest 2)\
size of the dataset: 50 minutes
## Metrics:
The average deviation between the prediction and the real position. MAE metric will be used for this.\
Need to create a solution that predict hand's fingers positions (described as quaterions) based on data taken from electrodes on myo armband.\

## Our work(full in pdf):
1) classic ml
2) dl: resnet + augmentation + denoise model
