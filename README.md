✨ **Neon Hand Constellation**

A fun and interactive hand tracking web app that captures your hand movements and displays them as glowing neon constellations!

## Features 🎯

- 🖐️ **Real-time Hand Detection** - Uses MediaPipe to detect and track both hands
- ✨ **Neon Effects** - Glowing dots and lines with beautiful shadow effects
- 📹 **Webcam Integration** - Live video feed with hand landmarks overlay
- 🎨 **Dark theme** - Sleek dark UI with golden neon accents
- 📱 **Responsive** - Works on different screen sizes

## How It Works 🔧

The app uses:
- **Flask** - Lightweight Python web server
- **MediaPipe Hands** - Google's hand detection ML model
- **Canvas API** - For drawing glowing hand constellations

## Installation 🚀

1. Clone the repository:
```bash
git clone https://github.com/yourusername/neon-hand-constellation.git
cd neon-hand-constellation
```

2. Create a virtual environment:
```bash
python -m venv .venv
.venv\Scripts\activate  # Windows
source .venv/bin/activate  # Mac/Linux
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the app:
```bash
python app.py
```

5. Open your browser and go to:
```
http://127.0.0.1:5000
```

## Usage 💡

1. Allow the browser to access your webcam when prompted
2. Hold your hand(s) in front of the camera
3. Watch your hand transform into a neon constellation!
4. The app detects up to 2 hands simultaneously

## What You'll See 👀

- Yellow glowing dots on each hand landmark (21 points per hand)
- Glowing neon lines connecting the landmarks
- Real-time hand detection with status updates
- Smooth animations and glow effects

## Requirements 📋

- Python 3.7+
- Webcam/Camera
- Modern web browser (Chrome, Firefox, Edge, Safari)

## Project Structure 📁

```
neon-hand-constellation/
├── app.py                          # Flask application
├── requirements.txt                # Python dependencies
├── README.md                       # This file
├── static/
│   └── style.css                  # Optional: Shared styles
└── templates/
    └── hand_constellation.html    # Main interactive page
```

## How to Deploy 🌐

### Deploy on Heroku:
```bash
heroku create your-app-name
heroku config:set FLASK_ENV=production
git push heroku main
```

### Deploy on Replit:
- Fork this repo to Replit
- Install dependencies
- Run `python app.py`
- Share the live link!

## Browser Permissions ⚠️

Make sure to:
1. Allow camera access when the browser asks
2. Use HTTPS for secure camera access (required by most browsers)
3. If using localhost, HTTP works fine for testing

## Troubleshooting 🔍

**Camera not working?**
- Check browser camera permissions
- Try a different browser
- Ensure lighting is adequate

**Hand not detecting?**
- Make sure your hand is fully visible
- Try moving closer to the camera
- Rotate your hand if needed

**Slow performance?**
- Check browser console for errors
- Try reducing the video quality
- Close other applications

## Fun Ideas 🎪

- Use it for presentations (make your hand glow while presenting!)
- Use it in games or interactive art projects
- Combine it with other ML models for gesture detection
- Create a multiplayer hand constellation viewer

## Credits 🙌

- [MediaPipe](https://mediapipe.dev/) - Hand detection model
- [Flask](https://flask.palletsprojects.com/) - Web framework
- Neon design inspiration from cyberpunk aesthetics

## License 📜

MIT License - Feel free to use, modify, and share!

## Connect 🤝

Have fun with the hand constellation! Feel free to fork, star, and create your own version. Share your creative uses on social media!

---

**Made with ✨ and Python**
