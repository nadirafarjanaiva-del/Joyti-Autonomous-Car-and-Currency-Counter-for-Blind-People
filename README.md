# AI-powered assistive system for visually impaired individuals integrating autonomous navigation, AI-based currency recognition, GPS tracking, and safety features.
Joity: AI-Powered Assistive System for Visually Impaired Individuals
Overview
Joity is an integrated assistive technology platform designed to enhance the independence, safety, and social inclusion of visually impaired individuals. The system combines autonomous navigation, AI-based currency recognition, GPS tracking, and safety features into a unified prototype.
The project was developed using Raspberry Pi, Arduino, Computer Vision, Deep Learning, GPS/GSM communication, and IoT technologies to support outdoor mobility, financial management, and real-time monitoring.

Funding Acknowledgement
This project was developed as part of a government-funded research and innovation initiative, selected through a competitive funding process under the ICT Division, Government of the People’s Republic of Bangladesh.
The project received financial and institutional support from the ICT Division to facilitate the research, development, and prototyping of an assistive technology system aimed at improving the independence, safety, and mobility of visually impaired individuals.
We gratefully acknowledge the ICT Division, Government of the People’s Republic of Bangladesh, for its valuable support and funding, which enabled the successful development and implementation of this socially impactful project.

# Project Features

Joity is an integrated assistive technology system developed to support the independent mobility, financial management, safety, and remote monitoring of visually impaired individuals. The project combines autonomous vehicle technology, computer vision, machine learning, GPS/GSM communication, and multiple safety mechanisms into a unified prototype. Its autonomous car uses Raspberry Pi-based image processing for lane detection and navigation, while YOLOv8 enables real-time stop-sign and obstacle detection. The system also incorporates an AI-based currency counter that evolved from a color-sensor-based approach to Haar Cascade, and finally YOLOv11-based currency recognition, enabling multiple Bangladeshi currency notes to be detected from a single frame with improved accuracy. For remote monitoring, GPS and GSM technologies provide real-time location information through SMS, calls, and the Traccar tracking platform, allowing family members or caregivers to monitor the user's location. In addition, automated door locking, fire detection, and anti-theft mechanisms are integrated to enhance the overall safety and security of the user. Together, these features provide a comprehensive assistive platform aimed at improving independence, accessibility, and confidence in the daily activities of visually impaired individuals.

# The key features of the project are listed below:

# Autonomous Navigation System
•	Lane detection using image processing and OpenCV
•	Bird's-eye view transformation for road analysis
•	Real-time steering control
•	Automatic U-turn functionality
•	Stop sign detection using YOLOv8
•	Obstacle detection and avoidance
•	Raspberry Pi-based autonomous driving prototype
# AI-Based Currency Recognition
# Three-stage evolution of the currency recognition system:
# Stage 1: Arduino + Color Sensor
•	Taka note recognition using TCS3200 sensor
•	Wallet balance management
•	Audio feedback for users
# Stage 2: Machine Learning Approach
•	Haar Cascade Classifier implementation
•	Raspberry Pi-based image processing
# Stage 3: Deep Learning Enhancement
•	Currency detection using YOLOv11
•	Multiple note recognition in a single frame
•	Detection accuracy: 87.3% – 99.5%
•	Dataset annotation using Label Studio
•	Model training using Google Colab
# GPS Tracking and Monitoring
•	Real-time location tracking
•	GPS-based coordinate acquisition
•	GSM communication module
•	SMS location sharing
•	Google Maps integration
•	Remote monitoring using Traccar
# Safety Features
•	Automatic door lock system
•	Fire detection and alarm
•	Anti-theft protection
•	User presence detection
•	Servo-controlled access mechanism

System Architecture
Hardware Components
•	Raspberry Pi 5
•	Raspberry Pi 3B+
•	Arduino Uno
•	Raspberry Pi Camera Modules
•	L298N Motor Driver
•	GPS Module
•	GSM Module
•	Ultrasonic Sensors
•	Infrared Sensors
•	Servo Motors
•	LCD Display
•	Flame Sensor
•	Speaker Module

Software and AI Technologies
•	Python
•	OpenCV
•	YOLOv8
•	YOLOv11
•	Haar Cascade Classifier
•	Google Colab
•	Label Studio
•	Traccar Platform
 
Research Contributions
•	Development of an integrated assistive technology platform for visually impaired individuals.
•	Application of computer vision and deep learning for autonomous navigation.
•	AI-based Bangladeshi currency recognition system.
•	GPS and GSM-enabled real-time monitoring.
•	Multi-functional prototype combining mobility, finance, and safety support.

Future Work
•	Real-world autonomous mobility implementation
•	PID-based closed-loop speed control
•	Integration with digital maps and navigation services
•	Improved obstacle avoidance
•	Mobile application development
•	Cloud-based monitoring and analytics

Contact
For collaborations, research discussions, or project inquiries:
Nadira Farjana
Email: nadirafarjanaiva@gmail.com 
Rabeya Khan
Email: rabeyakhan592@gmail.com 
