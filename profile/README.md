# ScoreOBE+: MIS for Outcome-Based Education


## Project Overview

ScoreOBE+ is a comprehensive platform developed specifically for the Faculty of Engineering at Chiang Mai University. This platform revolutionizes the way student exam results and homework assessments are managed and analyzed, providing a centralized system for accessing scores across various courses.

## Purpose

The primary goal of ScoreOBE+ is to enhance the educational assessment process through Outcome-Based Education (OBE) principles. The platform enables faculty to:

- Centralize and streamline access to student scores across all programs
- Evaluate student performance against Program Learning Outcomes (PLOs)
- Organize assessment data by department for better administrative oversight
- Utilize statistical analysis and score histograms to calibrate exam and homework difficulty
- Ensure students achieve specific Course Learning Objectives (CLOs)
- Generate and analyze TQF 3 and TQF 5 documents automatically based on uploaded scores


## OBE-frontend

### Description

The official frontend repository for ScoreOBE+, a comprehensive outcome-based education assessment platform developed for the Faculty of Engineering at Chiang Mai University. This React-based application provides an intuitive interface for students to access their exam results and for instructors to analyze learning outcomes, generate statistical reports, and visualize student performance data.

### Key Features

- Interactive dashboards for visualizing student performance metrics
- Score distribution histograms with statistical analysis tools
- PLO (Program Learning Outcome) and CLO (Course Learning Objective) tracking interfaces
- TQF document generation and management system
- Responsive design optimized for both desktop and mobile devices
- Role-based access control for students, instructors, and administrators


### Technology Stack

- **Framework**: React with Vite-based setup
- **Language**: TypeScript
- **UI Components**: Mantine UI
- **State Management**: Redux
- **Routing**: React Router
- **API Communication**: Axios
- **Styling**: Tailwind CSS
- **Data Visualization**: Chart.js & Recharts
- **Animations**: Framer Motion
- **Utilities**: Moment.js & Lodash


---

## OBE-backend

### Description

The core backend service powering ScoreOBE+, providing robust API endpoints, data processing, and business logic for the outcome-based education assessment platform. This repository contains the server-side implementation that handles authentication, data storage, report generation, and integration with university systems for the Faculty of Engineering at Chiang Mai University.

### Key Features

- RESTful API endpoints with comprehensive documentation
- Secure authentication and authorization system
- Automated TQF 3 and TQF 5 document generation
- Statistical analysis engine for score processing
- Data aggregation for PLO and CLO assessment
- Batch processing for handling large datasets
- PDF report generation for administrative purposes
- Integration points with existing university systems


### Technology Stack

- **Framework**: NestJS
- **Language**: TypeScript
- **Database**: MongoDB
- **ODM**: Mongoose
- **Authentication**: Passport.js & JWT
- **API Documentation**: Swagger
- **PDF Generation**: PDFKit
- **Utilities**: Moment.js & Lodash


## Key Benefits

- **Improved Assessment**: Provides detailed insights into student learning outcomes
- **Data-Driven Teaching**: Helps instructors adjust teaching methods based on performance metrics
- **Streamlined Documentation**: Automates the creation of required educational documentation
- **Centralized Management**: Offers a single platform for all assessment-related activities
- **Enhanced Transparency**: Gives students clear access to their performance metrics

