GestureAI EDGE: Real-Time Hand Tracking & Control
Live Demo: https://airealtimegesturecontrol.netlify.app

GestureAI EDGE is an advanced browser-based interaction system that allows users to control digital interfaces through hand gestures. Built with Edge AI principles, all processing happens locally on the user's device, ensuring maximum privacy and low-latency performance.

🖐️ Interactive Gesture Guide
The system recognizes a variety of gestures to trigger specific actions:

✌️ Peace: Take a Screenshot

👍 Thumbs Up: Success Action

✊ Fist: Pause/Resume

✋ Open Palm: Particle Effects

☝️ Point Up/Down: Scroll Navigation

🤙 Call Me: Toggle Theme

👌 OK Sign: Confetti Celebration

🫶 Heart Hands: Love/Hearts Effect

🚀 Key Features
Edge AI Processing: Zero server-side data transfer. Your video feed never leaves your computer.

Real-Time Analytics: Track gesture confidence scores, session time, and detection frequency via the live dashboard.

Canvas Drawing Mode: Use your hand as a virtual brush to draw directly on the screen.

Confidence Over Time: Integrated charts to visualize the model's accuracy during your session.

Voice Integration: Utilizes the Web Speech API for multimodal feedback.

🛠 Tech Stack
Core AI: MediaPipe (Hand Landmarker), TensorFlow.js

Frontend: React.js, Tailwind CSS

Analytics: Recharts (for confidence tracking)

APIs: Web Speech API (Voice), MediaDevices API (Camera)

Deployment: Netlify

🛡 Privacy First
Because this application uses Edge AI, the camera feed is processed locally using your GPU/CPU. No video or image data is ever uploaded or stored on a server.
