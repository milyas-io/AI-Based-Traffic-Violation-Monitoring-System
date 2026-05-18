# AI-Based Traffic Violation Monitoring System

## Overview

This project is an end-to-end AI-powered traffic violation monitoring platform. It uses computer vision, object detection, object tracking, OCR, backend APIs, and a web dashboard to detect traffic violations and generate evidence records.

## Key Features

- Vehicle detection using computer vision
- Vehicle tracking across video frames
- Number plate detection and OCR
- Traffic violation rule engine
- Evidence image and video generation
- Violation history dashboard
- REST APIs for violation records
- PostgreSQL-based data storage
- Postman collection for API testing
- Docker-based deployment support

## Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Axios
- Chart.js or Recharts

### Backend
- Python
- FastAPI
- PostgreSQL
- SQLAlchemy
- JWT Authentication

### AI / Computer Vision
- OpenCV
- YOLO
- EasyOCR or PaddleOCR
- SORT / DeepSORT for tracking

### DevOps / Tools
- GitHub
- Postman
- Docker
- VS Code

## Project Structure

```text
backend/        Backend APIs and business logic
frontend/       Web dashboard
ai-models/      AI models, notebooks, and detection pipeline
sample-videos/  Test videos for model validation
evidence/       Generated violation screenshots, clips, and reports
docs/           Architecture, API docs, database design, and roadmap
postman/        API testing collection
docker/         Docker setup files
