# Smart Accident Detector – YOLOv8 Model

> 🚨 **Stay one step ahead of danger!** Harnessing the blazing-fast precision of YOLOv8, this system continuously monitors video feeds to spot collisions, near-misses, and unusual road events in real time. Whether you’re building smarter traffic control, enhancing fleet safety, or researching accident patterns, our detector delivers instant alerts, rich analytics, and crystal-clear visualizations—so you can react faster, learn more, and save lives.  

## 🚗 Overview

This project implements a real-time accident detection system using the YOLOv8 object detection model. It processes video feeds to identify potential accidents and triggers alerts upon detection.

## 🎯 Features

* **Real-Time Detection**: Processes live video streams to detect accidents as they occur.
* **YOLOv8 Integration**: Utilizes the advanced YOLOv8 model for accurate object detection.
* **Custom Dataset Training**: Trained on a custom dataset tailored for accident scenarios.
* **Alert System**: Plays an alert sound (`alert.mp3`) when an accident is detected.
* **Output Recording**: Saves the detection results in `detection_output.mp4` for review.

## 🗂️ Repository Structure

```plaintext
├── CV_train_yolov8_object_detection_on_custom_dataset.ipynb  # Training notebook
├── accident.mp4                                              # Sample input video
├── accident12.mp4                                            # Additional sample video
├── accident_incident_clip.mp4                                # Another sample clip
├── detection_output.mp4                                      # Output video with detections
├── alert.mp3                                                 # Alert sound file
├── output.txt                                                # Log file with detection details
```



## 🛠️ Setup Instructions

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/coded-with-aryan0426/Smart-Accident-Detector-YOLOv8-Model.git
   cd Smart-Accident-Detector-YOLOv8-Model
   ```



2. **Create a Virtual Environment** (Optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```



3. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```



*Note*: If `requirements.txt` is not present, ensure you have the following packages installed:

```bash
pip install ultralytics opencv-python
```



4. **Run the Detection Script**:

   ```bash
   python detect_accidents.py --source accident.mp4 --output detection_output.mp4
   ```



*Note*: Replace `accident.mp4` with your input video file.

## 📊 Training the Model

The `CV_train_yolov8_object_detection_on_custom_dataset.ipynb` notebook provides a step-by-step guide to train the YOLOv8 model on a custom dataset. It covers data preparation, model training, and evaluation.

## 🔔 Alert System

Upon detecting an accident, the system plays an alert sound (`alert.mp3`) to notify users. Ensure your system's audio is enabled to hear the alerts.

## 📁 Sample Videos

The repository includes several sample videos:

* `accident.mp4`
* `accident12.mp4`
* `accident_incident_clip.mp4`

These can be used to test the detection capabilities of the model.

## 📄 Output

The detection results are saved in `detection_output.mp4`, showcasing the model's performance. Additionally, `output.txt` logs the detection details for further analysis.

## 🤝 Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.

## 📧 Contact

For any queries or feedback, please contact [aryansuthar890@gmail.com](mailto:aryansuthar890@gmail.com).

---

*This project is a demonstration of integrating YOLOv8 for accident detection in video feeds. It's intended for educational and research purposes.*

---

Feel free to customize the contact information and any other sections as needed. Let me know if you need further assistance!
