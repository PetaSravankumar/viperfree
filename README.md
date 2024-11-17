# AI-Powered Rain Vision System (Viper-Free) with Adaptive Tinting 🚗🌧️
This project implements an AI-powered rain vision system to enhance vehicle visibility and safety during adverse weather conditions. It combines adaptive tinting, AR/VR overlays, and machine learning-based predictive adjustments to eliminate traditional wiper systems and improve the driving experience.

Features
Adaptive Tinting: Dynamically adjusts windshield transparency based on rain intensity, ambient light, and glare levels.
AR/VR Overlays:
Displays lane markers to assist in maintaining road alignment.
Overlays real-time data (rain intensity, ambient light, glare levels) for situational awareness.
Predictive AI Adjustments:
Machine learning predicts optimal tinting levels based on historical sensor data.
Simulated Environment:
Demonstrates functionality using OpenCV for AR/VR overlays.
Requirements
Before running the code, ensure the following dependencies are installed:

Python 3.7 or above
Required Python packages:
bash
Copy code
pip install numpy scikit-learn opencv-python
Installation
Clone this repository:

bash
Copy code
git clone https://github.com/your-username/ai-powered-rain-vision.git
cd ai-powered-rain-vision
Install the dependencies:

pip install -r requirements.txt
Run the project:

python main.py
Usage
The system continuously simulates real-time sensor data (rain, ambient light, glare) and adjusts the following:

Tinting Transparency: Ensures optimal visibility by modifying the windshield transparency.
AR/VR Overlays: Displays visual guidance and environmental data on a simulated screen.
AI Predictive Adjustments: Learns from previous data to optimize future visibility enhancements.
The AR/VR overlay simulates a heads-up display (HUD) using OpenCV and presents:

Lane markers for road guidance.
Real-time rain, light, and glare statistics.
Key Components
Sensor Simulation:
Generates real-time data for rain intensity, ambient light, and glare.
Adaptive Tinting:
Adjusts windshield transparency dynamically.
AR/VR Overlay:
Visual guidance and data overlays for improved driver visibility.
Predictive AI:
Uses historical data to predict optimal adjustments.
Example Output
AR/VR Overlay:
![Screenshot 2024-11-17 112920](https://github.com/user-attachments/assets/4a59f3d5-e4f4-45b6-9fc5-1bddc5009716)

Future Enhancements
Integration with actual hardware for real-world deployment (e.g., HUDs, smart windshields).
Adding features like obstacle detection and advanced AR guidance.
Voice control for customization and driver interaction.
Integration with traffic and weather APIs for real-time updates.
Contributing
Contributions are welcome! Feel free to fork the repository and subm
