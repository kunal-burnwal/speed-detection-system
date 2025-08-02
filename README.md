# Speed Detection System 

A real-time vehicle speed monitoring system using Python and OpenCV.

Features
- Detects moving vehicles in video footage.
- Calculates vehicle speed using Euclidean distance.
- Records speed violations and saves data.
- Generates visual analytics using Matplotlib.
- Notifies violations (email/SMS logic can be extended).

Tech Stack
- Python
- OpenCV
- NumPy
- Matplotlib
- File Handling

Project Structure
### project/
1. main.py # Main script to process video and track speed
2. objTracker.py # Contains the object tracking class and logic
3. resources/ # Folder for storing input/output files
      a. Traffic_video.mp4 # (google drive link is being added below)
4. output/ # showing thw outputs for better understanding
5. README.md # This file



Demo Video
🔗 [Click here to watch the traffic video on Google Drive](https://drive.google.com/file/d/1MDTofMRCRphl3LHk2Q_DB4Uh2xLg6h1l/view?usp=drive_link)

How Speed is Calculated
1. The system tracks vehicle position frame-by-frame.
2. Computes distance between two frames.
3. Divides distance by time to get speed in px/s.

Output
- CSV or text log of vehicles and speeds
- Graphs showing speed violations

Future Improvements
- Integrate license plate recognition.
- Connect to database and deploy to cloud.
- Extend with notification APIs (Twilio, SMTP, etc.)

Author
Kunal Burnwal

