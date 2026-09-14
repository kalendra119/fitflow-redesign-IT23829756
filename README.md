# fitflow-redesign-IT23829756
FitFlow fitness application redesign developed for IT3060 HCI Lab 05
# FitFlow Redesign

FitFlow is a fitness application redesign developed for IT3060 Human Computer Interaction Lab 05.

The project applies the findings from Labs 1, 2, 3 and 4 to select a suitable technology stack and propose a high-level system architecture.

## Project Background

The research conducted during the previous labs identified several usability problems in the existing FitFlow application:

- Generic workout recommendations
- Lack of social support and motivation
- Difficult and time-consuming nutrition logging
- Limited user control over AI recommendations
- Poor visibility of progress information

The selected redesign uses an AI-first dashboard to provide personalized workout plans, faster nutrition logging, private community features and clear progress tracking.

## Selected Design

Variant A - AI-First Dashboard was selected in Lab 3 with a score of 23 out of 25.

The main screens are:

- AI-First Home Dashboard
- AI Workout Planner
- Nutrition Logger
- Community Feed
- Progress Tracking

## Lab 4 Usability Results

The usability evaluation produced the following results:

- System Usability Scale score: 81.2
- Overall task completion rate: 85.7%
- Average Single Ease Question score: 5.74 out of 7

The main recommended improvements were:

- Add a visible Change Exercise label
- Display a confirmation after accepting a workout plan
- Shorten onboarding and include a step indicator
- Allow users to correct food recognition results manually
- Display clear privacy labels on community groups
- Increase the size of progress chart text

## Selected Technology Stack

### Frontend

- React Native
- Expo
- React Native Web

### Backend

- Node.js
- Express
- Socket.IO

### Database and Authentication

- Firebase Firestore
- Firebase Authentication

### Artificial Intelligence

- TensorFlow Lite
- ML Kit
- Optional FastAPI cloud AI service

### Delivery

- GitHub Actions CI

## Project Structure

```text
fitflow-redesign/
├── frontend/
│   └── README.md
├── backend/
│   └── README.md
├── ai-service/
│   └── README.md
├── docs/
│   ├── architecture/
│   │   ├── ADR-001.md
│   │   └── fitflow-architecture-IT23829756.png
│   ├── comparison-matrix.md
│   └── tech-stack.md
├── .github/
│   └── workflows/
│       └── ci.yml
├── .gitignore
└── README.md

## HCI Traceability

- Lab 1 identified the stakeholders and collected user research data.
- Lab 2 converted the findings into themes, personas, user stories and requirements.
- Lab 3 produced alternative designs and selected the AI-First Dashboard.
- Lab 4 tested the prototype and identified usability improvements.
- Lab 5 selects the technology stack and proposes the system architecture.

## Student Details

- Student ID: IT23829756
- Module: IT3060 Human Computer Interaction
- Project: FitFlow Redesign
- Semester: Semester 2, 2026
