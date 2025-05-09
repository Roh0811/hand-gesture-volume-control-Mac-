# Hand Gesture Volume Control 🎛️

Control your system volume using hand gestures with a webcam and Streamlit-based interface.  
Built with OpenCV, MediaPipe, and Streamlit WebRTC.


## 🚀 Features

- Adjust system volume using thumb-index finger distance
- Lower your pinky finger to confirm the change
- Real-time webcam feed with hand tracking
- Works on macOS (osascript-based volume control)


## 📦 Requirements

- Python 3.7+
- Webcam access
- Streamlit and supporting libraries


## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/your-username/hand-gesture-volume-control.git
cd hand-gesture-volume-control

# Create a virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
