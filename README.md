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

Core AI / ML :
TechnologyVersionRoleMediaPipe HandsLatest (CDN)21-point 3D hand landmark detection via WASM + WebGLTensorFlow.jsLatest (CDN)ML runtime, tensor operations, custom model inference

Web APIs (Browser-Native) :
APIRolegetUserMedia() / MediaDevices APIWebcam access and video stream captureWeb Speech APIVoice feedback — speaks detected gesture name aloudMediaRecorder APIRecords the gesture session as a .webm videoHTML5 Canvas APIRenders landmarks, skeleton, particles, drawing overlaylocalStorage APIPersists settings, theme, and future custom gesturesRequestAnimationFrame60fps render loop synchronization

UI & Visualization : 
TechnologyRoleTailwind CSS (CDN)Utility-first styling, dark theme, responsive layoutChart.js (CDN)Live confidence score graph over timeHTML5 CanvasParticle system, drawing engine, landmark overlay

Audio : 
TechnologyRoleTone.js (CDN)Synthesized sound effects triggered by gesturesWeb Audio APIUnderlying audio context for real-time audio generation

Deployment : 
PlatformRoleNetlifyStatic site hosting with instant CDN deliveryGitHubVersion control and source repository

🛡 Privacy First
Because this application uses Edge AI, the camera feed is processed locally using your GPU/CPU. No video or image data is ever uploaded or stored on a server.
