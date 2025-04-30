# Fitphile - AI-Powered Exercise Tracker
Overview
Fitphile is a Flask-based AI-powered fitness tracking application that uses MediaPipe Pose to track and count exercise reps in real-time. It supports exercises such as push-ups, squats, lunges, and planks while providing real-time feedback and voice notifications.

Features
Real-time Exercise Tracking using OpenCV & MediaPipe Pose
Push-up, Squat, Lunge, and Plank Recognition
Live Camera Feed for Workout Monitoring
Voice Feedback for Milestones
Flask Web App Interface
Exercise Counter with Reset Feature
Project Structure
/finali guess
│── /templates
│   │── index.html
│── lunges.py
│── plank.py   
│── pushups.py 
│── server.py   
│── squats.py
│── requirements.txt  # Python dependencies
Installation
1. Clone the repository
git clone https://github.com/your-username/Fitphile.git
cd Fitphile
2. Create a Virtual Environment (Recommended)
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
3. Install Dependencies
pip install -r requirements.txt
4. Run the Flask App
python app.py
5. Open in Browser
Once the server starts, open a browser and go to:

http://127.0.0.1:5000/
Usage
Select an exercise from the homepage.
The live camera feed starts tracking your movement.
Perform the exercise, and the counter will update automatically.
Receive voice feedback at milestones.
Use the Reset button to restart the counter.
Dependencies
Ensure you have the following installed:

Python 3.7+ (Recommended: 3.7 for compatibility)
Flask
OpenCV (cv2)
NumPy
MediaPipe
pyttsx3 (for voice feedback)
To install them, use:

pip install flask opencv-python numpy mediapipe pyttsx3
Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

License
MIT License
