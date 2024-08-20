# Face-Recognition-Attendance-System
The Face Recognition-Based Attendance System automates attendance recording using facial recognition. Developed with Python and OpenCV, it captures images via a camera and compares them to a database for seamless attendance marking, ensuring accurate identification even in challenging conditions like low light or when wearing glasses.

## Installation

1. Clone the repository to your local machine. ``` git clone https://github.com/para8ox-deb/Face-Recognition-Attendance-System.git```
2. Install the required packages using ```pip install -r requirements.txt```.
3. Download the dlib models from https://drive.google.com/drive/folders/1KiBEAYL_w6GfmHo5aBfPCzfR7a6kv7b-?usp=sharing and place the data folder inside the repo

    
## Usage

1. Collect Faces Dataset:
Run the following command to collect face images for the dataset:
```python get_faces_from_camera.py```

2. Extract Features and Convert to CSV:
Convert the dataset into a CSV file by running:
```python features_extraction_to_csv.py```

3. Take Attendance:
To take attendance, use the command:
```python attendance_taker.py```

4. Check the Database:
View the recorded attendance by running the web application:
```python app.py```


## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please feel free to submit a pull request or open an issue.


