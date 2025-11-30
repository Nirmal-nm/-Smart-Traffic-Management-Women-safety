🚦 Smart Traffic Management & Women Safety System
Team: Tech Vanguard | UP Hackathon Project

An AI-driven system designed to improve traffic management, detect violations, automate challans, and enhance women’s safety through a mobile SOS platform. This project integrates Computer Vision, Machine Learning, IoT, and Mobile App technologies for real-time intelligent decision-making.

----Live Prototype

 Traffic Management Demo:
https://traffic-management-1-ixd2.onrender.com/

----- Features
 1. Smart Traffic Signal Automation

Real-time traffic density detection

Dynamic signal timing (automatically adjusts green/red duration)

Reduces congestion, wait time, fuel consumption

Optional IoT sensor support

Interconnected junction system for smooth traffic flow

2. Traffic Violation Detection

Powered by YOLOv8 + Custom CNN + OpenCV

Detects:

 Red light jump

 No helmet

 Wrong-side driving

 No seatbelt

 Pedestrian violations

Enforcement:

Automatic number plate extraction (ANPR)

Vehicle identification

E-challan generation

Instant alert to authorities

Pipeline:
CCTV → Frame Extraction → Object Detection → Violation Logic → ANPR → Evidence → e-Challan

 3. Women Safety SOS App

Built with React Native + Google Maps API

Features:

 GPS-based live location sharing

 One-tap SOS to 1090

 Audio/Text complaint submission

CCTV evidence linked automatically

 Real-time info sent to authorities

 AI Model Development
Dataset Preparation

5000+ samples of Indian traffic

Annotation with LabelImg

Augmentation (rain, fog, rotation, scaling)

YOLOv8 Configuration

Image size: 640×640

Classes: Vehicles, helmets, pedestrians, seatbelts, signals

Transfer learning from pretrained weights

mAP, Precision, Recall monitoring

Custom CNN Layers

Helmet detection

Wrong-side detection

Seatbelt tracking

Direction analysis

ANPR

OpenALPR or custom CNN

Extracts license plate text from frames

Inference

TensorRT optimization

Cloud deployment for scalability

 Technologies Used
AI & CV

YOLOv8

TensorFlow

OpenCV

CNN

Scikit-learn

Mobile App

React Native

Google Maps API

Backend

Python / Node.js (for APIs)

FastAPI (optional)

Deployment

Render

TensorRT

Cloud GPU servers

 Team Members – Tech Vanguard

 Research References

AI-powered Smart Traffic Management

Women Safety Systems

YOLOv8 research

Smart City enhancement papers

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7341963/

https://journals.sagepub.com/doi/full/10.1177/0268396219882957

https://www.researchgate.net/publication/344280396_AI_powered_Smart_Traffic_Management_System_for_Women_Safety
