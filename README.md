# An Intelligent Crowd Risk Management System

## Overview

An Intelligent Crowd Risk Management System is an AI-powered surveillance solution designed to monitor crowd density in real time using Computer Vision and Deep Learning. The system leverages the YOLOv8 object detection model to accurately detect people, estimate crowd density, identify high-risk congestion zones, and generate instant alerts. By automating crowd monitoring, the system enables proactive decision-making, improves emergency response, and enhances public safety in crowded environments.

## Problem Statement

Traditional surveillance systems rely on continuous human monitoring, making it difficult to detect overcrowding and respond promptly during emergencies. Delayed identification of crowd congestion can result in accidents, stampedes, and public safety risks. This project addresses these challenges through intelligent, automated crowd analysis and real-time alert generation.

## Objectives

- Monitor crowd density in real time.
- Detect overcrowded areas using AI-based object detection.
- Generate instant alerts when predefined safety thresholds are exceeded.
- Reduce dependency on manual surveillance.
- Improve response time during crowd-related emergencies.

## Features

- Real-time crowd monitoring
- AI-powered people detection using YOLOv8
- Crowd density estimation
- Risk zone identification
- Automated Telegram alert notifications
- Live monitoring through a web interface
- Scalable and cost-effective deployment

## Technology Stack

### Programming Languages
- Python
- JavaScript
- HTML
- CSS

### AI/ML Technologies
- YOLOv8
- Computer Vision
- Deep Learning

### Frameworks and Libraries
- Flask
- OpenCV
- NumPy
- Pandas

### Tools
- Visual Studio Code
- Git
- GitHub
- Telegram Bot API

## System Workflow

1. Capture live video from an IP camera or CCTV.
2. Process each frame using the YOLOv8 object detection model.
3. Detect and count the number of people.
4. Estimate crowd density based on detection results.
5. Compare crowd density with predefined threshold values.
6. Generate Telegram alerts when overcrowding is detected.
7. Display the live monitoring results through the web dashboard.

## Project Architecture

```
IP Camera / CCTV
        │
        ▼
 Video Capture
        │
        ▼
YOLOv8 Object Detection
        │
        ▼
 Crowd Density Analysis
        │
        ▼
 Risk Detection
        │
   ┌────┴────┐
   ▼         ▼
Dashboard  Telegram Alerts
```

## Applications

- Smart City Surveillance
- Railway Stations
- Airports
- Stadiums
- Shopping Malls
- Religious Gatherings
- Public Events
- Educational Institutions
- Corporate Campuses

## Project Structure

```
An-Intelligent-Crowd-Risk-Management-System/
│
├── static/
├── templates/
├── models/
├── utils/
├── app.py
├── detect.py
├── requirements.txt
├── README.md
└── LICENSE
```

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/An-Intelligent-Crowd-Risk-Management-System.git
```

### Navigate to the Project Directory

```bash
cd An-Intelligent-Crowd-Risk-Management-System
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

## Results

The system successfully performs real-time people detection and crowd density estimation using YOLOv8. It identifies overcrowded regions with high accuracy, sends instant Telegram notifications, and provides continuous monitoring through a web-based dashboard. The solution reduces manual effort while enabling faster and more effective crowd risk management.

## Future Enhancements

- Multi-camera support
- Crowd movement prediction
- Heatmap visualization
- Edge AI deployment
- Cloud-based monitoring
- Mobile application integration
- Predictive crowd analytics

## Contributors

- Backend Development
- AI/ML Model Development
- Frontend Development
- System Integration
- Testing and Deployment

## License

This project is developed for academic and research purposes.
