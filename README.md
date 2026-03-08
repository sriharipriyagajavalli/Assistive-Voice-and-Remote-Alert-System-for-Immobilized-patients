Assistive Voice and Remote Alert System for Immobilized Patients

OVERVIEW:
This project provides an assistive voice interface for immobilized patients, enabling them to communicate simple commands through voice input. It also includes a remote alert system to notify caregivers or family members via mobile notifications when assistance is required. The system aims to improve patient safety, independence, and response time in emergency situations.

Features:
Voice Command Recognition: Patients can trigger alerts using simple voice commands.
Remote Alerts: Sends notifications to caregivers via mobile applications (Telegram/SMS).
User-Friendly Interface: Simple design suitable for patients with limited mobility.
IoT-Enabled: Optionally integrates with IoT devices for smart home or hospital settings.

Technologies Used:
Programming Languages: Python
Libraries: SpeechRecognition, pyttsx3, requests (for notifications)
Notification Platform: Telegram Bot API / SMS Gateway (configurable)
Optional Hardware: Microcontroller (Arduino/Raspberry Pi) for sensor integration

Installation:
Clone the repository:
git clone https://github.com/your-username/assistive-voice-alert.git
Navigate to the project directory:
cd assistive-voice-alert
Install dependencies:
pip install -r requirements.txt
Configure the notification system (Telegram Bot Token or SMS Gateway credentials).
Usage
Run the main application:
python main.py
Speak commands to trigger alerts.
Caregivers will receive notifications instantly when the system detects a request for help.

Future Enhancements:
Integrate multiple languages for voice recognition
Add wearable sensor support for automatic emergency detection
Implement cloud-based logging for patient activity and alerts
Mobile app for caregivers with real-time notifications
