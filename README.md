https://alfanrizkyw.github.io/employe-activity-detector/

🧠 Employee Activity Detector

Employee Activity Detector is an intelligent web-based monitoring system that uses a webcam and AI-powered face detection (via TensorFlow.js BlazeFace) to determine if a user is present in front of the camera.

When the user disappears from view, the system automatically displays a full-screen warning text “USER NOT DETECTED” and continuously plays a loud Google-like voice alert until the user returns.
It accurately logs the time when the user leaves and when they return, providing a detailed session record that can be downloaded as a CSV file.

🚀 Key Features

🎥 Real-time camera monitoring using TensorFlow.js BlazeFace

🔊 Voice alert system that repeats “User Not Detected” until the user comes back

🕒 Accurate timestamp logs for disappearance and return events

💾 Built-in session log viewer and CSV export

🌐 Fully client-side — no server required

🧊 Modern, responsive, and glassmorphic UI design

🪞 Lightweight and privacy-friendly (no data stored externally)

🖋️ Watermark: Project by Paan

⚙️ How It Works

Open the web page and grant camera access.

The AI model runs locally in your browser to detect your face.

If the system fails to detect a face, it triggers an alert (visual + voice).

When you return, the alert stops automatically, and both events are logged.

🧩 Technology Stack

HTML5, CSS3, JavaScript (ES6)

TensorFlow.js

BlazeFace Model

Web Speech API for text-to-speech

👤 Author

Developed by Paan (Alfan Rizky W.)
© 2025 – Open-source personal project for AI-based employee monitoring and productivity awareness.
