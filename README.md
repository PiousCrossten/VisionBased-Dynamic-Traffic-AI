# VisionBased-Dynamic-Traffic-AI
Welcome to the official repository for our AI-Based Dynamic Traffic Signal System, a project that merges Embedded Systems and Artificial Intelligence to bring real-time intelligence to urban traffic management.
This project aims to optimize traffic flow and minimize congestion by dynamically controlling traffic signals based on real-time vehicle density. It also introduces early-stage green corridor logic to prioritize emergency vehicles — representing a practical step toward smart city infrastructure.

The system was built using a combination of custom-trained deep learning models, embedded hardware execution on Raspberry Pi 5, and real-time image processing through a camera module.

 Key Highlights
🧠 Built with Embedded AI Principles: Integrates sensing, real-time decision-making, and actuation using lightweight edge processing on Raspberry Pi.

📷 Traffic Detection Accuracy: 98%: Achieved through training on a custom dataset using scaled-down Hot Wheels simulations to emulate real-world intersections.

🔁 Dynamic Signal Timings: Automatically adjusts green/red light durations based on traffic flow using computer vision.

🚑 Green Corridor Support (Prototype): Recognizes emergency vehicles and enables uninterrupted passage through intersections.

🌐 Firebase Integration: Syncs real-time data to the cloud for live monitoring and future route coordination.

🛠️ Tech Stack
Hardware: Raspberry Pi 5, Raspberry Pi Camera Module V5, GPIO Relay Module

Software:

Python

OpenCV for vehicle detection

TensorFlow Lite for lightweight on-device inference

Firebase (Realtime Database) for cloud sync

Custom-trained image dataset (Hot Wheels traffic simulation)


