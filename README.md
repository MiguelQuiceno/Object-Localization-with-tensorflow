# Object-Localization-with-tensorflow(Written in english)
![image](https://user-images.githubusercontent.com/60410581/127754204-a52c58a6-ced8-485b-b31e-db4f378017c0.png)

This is a beginner computer vision project with convolutional neural networks.
## Project explanation:
The idea is to localize emojis with a bounding box, but is not like a normal computer vision project where we train the model with images and move a sliding window through the image and find the object, we calculate the intersection over the union between the grounding boxes and then train the model according to the IoU metric.

## Steps of the project:
- Download and visualize data.
- Create examples for training.
- Bounding boxes plotting.
- Data generator.
- Model creation.
- Custom metric: Intersection over union.
- Compile the model.
- Custom callback and model testing.
- Model training.
