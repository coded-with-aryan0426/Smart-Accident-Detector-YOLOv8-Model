# Smart Accident Detector using YOLOv8

This project implements a smart accident detection system using YOLOv8 object detection model. The system can detect accidents in real-time video feeds and includes additional features like fire detection.

## Project Structure

```
├── acident validate.v2i.yolov8/     # Accident detection dataset
├── fire2.v1i.yolov8/                # Fire detection dataset
├── j23s45q2-fgkj th 2.v1-kepakai.yolov8/  # Additional accident dataset
├── assets/                          # Project media assets
├── exported_models/                 # Trained model exports
├── runs/                           # Training runs and results
├── CV_train_yolov8_object_detection_on_custom_dataset.ipynb  # Training notebook
└── yolov8s.pt                      # YOLOv8 base model
```

## Dataset Information

### Accident Detection Dataset
- Contains 820 annotated images
- Classes: accident, non-accident
- Images pre-processed to 640x640 resolution
- Annotated in YOLOv8 format

### Fire Detection Dataset
- Single class: fire
- Includes train, validation, and test splits
- Licensed under CC BY 4.0

## Model Training

The project uses YOLOv8 architecture for both accident and fire detection. Training details and configurations can be found in the Jupyter notebook.

## Files Description

- `CV_train_yolov8_object_detection_on_custom_dataset.ipynb`: Main training notebook
- `Project_Working_Video.mkv`: Demo video of the working project
- `alert.mp3`: Audio alert for detected incidents
- Various test videos for validation

## License

Datasets used in this project are licensed under CC BY 4.0.

## Acknowledgments

- Roboflow for dataset management and preprocessing
- YOLOv8 for the object detection architecture