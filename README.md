# Traffic Flow Analysis

This project performs **traffic monitoring and analysis** using the YOLO object detection model, OpenCV, and additional filtering algorithms.  
It can detect vehicles from traffic videos, count them, and provide insights such as traffic density and vehicle tracking.

## Features
- **Vehicle Detection** – Detects cars, bikes, buses, and trucks using YOLO.
- **Video Source Flexibility** – Works with:
  - Local video files
  - YouTube video links
  - Live camera streams
- **Object Tracking** – Uses Kalman Filter and SORT for better tracking.
- **Data Collection** – Saves detection results into CSV for further analysis.
- **Traffic Density Analysis** – Provides statistics on vehicle count and movement.

### Run in Jupyter Notebook
1. Open the notebook:
   ```bash
   jupyter notebook Traffic_analysis.ipynb
   ```
2. Provide the video source (local file or YouTube link).
3. Run all cells to process the video and generate results.


## Output
- **Processed Video** – Displays detected and tracked vehicles with bounding boxes.
- **CSV File** – Contains frame-wise detection results:
  - Vehicle type
  - Coordinates
  - Confidence score
- **Statistics** – Total vehicles counted, vehicle type distribution.

Output:
```
Lane 1: 167
Lane 2: 234
Lane 3: 2360
```

##  Technologies Used
- **YOLO** – Object Detection
- **OpenCV** – Image & Video Processing
- **Pandas** – Data Handling
- **FilterPy** – Kalman Filter for tracking
- **SciPy** – Scientific Computations
- **yt-dlp** – YouTube video downloading

## Future Improvements
- Real-time traffic violation detection
- Speed estimation of vehicles
- Integration with traffic light control system
- Web dashboard for live monitoring

## Video Link:
[Watch the demo video]([google drive link](https://drive.google.com/file/d/1FSqH9NI9qzuoaq-G8AsQZzWMbsTkJqAL/view?usp=drive_link))

