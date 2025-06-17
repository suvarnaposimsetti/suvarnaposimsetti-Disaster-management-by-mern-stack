📖 Overview
This project is an AI-powered Disaster Management System designed to address the challenges of disaster response, resource allocation, and real-time alerts. It leverages Google Gemini AI, geospatial visualization, and real-time data to provide efficient disaster predictions, resource tracking, and automated communication.

✨ Features
✅ Real-Time Disaster Tracking – Interactive 2D & 3D maps powered by Mapbox GL JS & COBE ✅ AI-Powered Predictions – Uses Google Gemini & LSTM models for disaster forecasting ✅ Smart Resource Management – PostgreSQL + PostGIS for tracking food, medical aid, and rescue teams ✅ Automated Alerts – Twilio & Firebase Push Notifications for SMS, IVR & app alerts ✅ Multilingual AI Chatbot – Gemini-powered chatbot for community interaction ✅ Crowdsourced Incident Reports – Citizens can submit geo-tagged photos & text ✅ Team Coordination & Task Assignment – AI-optimized response prioritization ✅ Scalable Cloud Infrastructure – Hosted on Google Cloud with load balancing

🛠️ Tech Stack
Frontend & UI
Framework: React (Latest Version) + TypeScript
Styling: Tailwind CSS, ShadCN
Icons: Lucide React
State Management: Zustand
Mapping & Data Visualization
Mapping: Mapbox GL JS, React Map GL
Geospatial Visualization: COBE (3D Globe)
Charts & Analytics: Chart.js, React-Chartjs-2
Backend & Database
Database: PostgreSQL + PostGIS (Geospatial Support)
Backend Services: Supabase (with Row Level Security & real-time subscriptions)
Task Management: Custom AI-powered engine
AI & Machine Learning
AI Model: Google Gemini (for disaster prediction, misinformation detection, and resource optimization)
Algorithms: LSTM (for time-series analysis), Decision Trees (for response prioritization)
Data Sources: OpenWeather API, IMD, NASA, Citizen Reports
Communication & Alerts
Notifications: Twilio (SMS, IVR), Firebase Push Notifications
Multilingual AI Chatbot: Gemini API-powered
Cloud Infrastructure & Deployment
Hosting: Google Cloud (Scalable backend, AI processing)
Load Balancer: For handling peak traffic during disasters
Development & Optimization
Build Tools: Vite (for fast builds)
Date Handling: date-fns (Efficient date/time manipulation)
Linting & Code Quality: ESLint, TypeScript ESLint
📌 Installation & Setup
Clone the repository:

  git clone 
Install dependencies 

  npm install
Run the development server:

  npm run dev
🚀 Future Enhancements
Blockchain-based relief fund tracking
AI-driven disaster impact assessment
Integration with government disaster response APIs
Edge computing for low-connectivity regions
