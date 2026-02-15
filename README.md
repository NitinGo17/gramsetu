## GramSetu — Smart Government Scheme Access Platform
GramSetu is a smart, multilingual digital platform designed to bridge the gap between rural citizens and government welfare schemes. It simplifies discovery, eligibility checking, document verification, and application tracking — all in one place.
This prototype demonstrates how technology can make government services more accessible, transparent, and user-friendly, especially for farmers and rural communities.

## Problem Statement
Millions of eligible citizens, especially in rural areas, fail to access government schemes due to:
- Lack of awareness
- Complex application processes
- Language barriers
- Document verification issues
- No centralized tracking system
GramSetu solves these problems with a unified, simple, and intelligent interface.

## Solution Overview
GramSetu provides a centralized platform where users can:
- Check scheme eligibility instantly
- Connect DigiLocker for automatic document verification
- Subscribe to relevant schemes
- Receive real-time SMS-style notifications
- Track application status
- Access everything in their preferred language

## Key Features

## Smart User Profile
- Simple eligibility form
- Stores user data locally
- Personalized scheme recommendations

## DigiLocker Integration (Prototype Simulation)
- Auto-verification of Aadhaar, Income Certificate, Farmer ID
- Eliminates manual document upload

## Real-Time Notification System
- SMS-style alerts
- Notification history panel
- Subscription alerts

## Full Multilingual Support
Supports multiple Indian languages:
- English
- Hindi
- Bengali
- Marathi
- Telugu
- Punjabi
- Kannada
- Malayalam
- Gujarati
Includes a custom-built translation engine.

## Application Tracking System
- Visual progress tracker
- Submitted → Under Review → Approved stages

## Fully Responsive Design
- Works on desktop and mobile
- Mobile navigation support

## Technical Highlights
- Pure HTML, CSS, and JavaScript
- No external backend required
- LocalStorage used for persistent state
- Custom Translation Engine (GlobalTranslator + TranslationEnforcer)
- Modular architecture
- Notification simulation system
- Dynamic UI rendering

## Architecture
User
↓
Eligibility Form
↓
Profile Creation
↓
Scheme Recommendation Engine
↓
DigiLocker Verification Layer
↓
Subscription System
↓
Notification Engine
↓
Application Tracker

## Project Structure
gramsetu/
│
├── index.html # Complete prototype
├── README.md # Project documentation

Everything runs from a single file prototype for simplicity.

## Design Goals
- Simple and intuitive interface
- Government-style clean UI
- Accessible for low-tech users
- Mobile friendly
- Fast and lightweight
  
## Future Scope
Possible real-world extensions:
- Real DigiLocker API integration
- Real SMS gateway integration
- Aadhaar authentication
- Backend database integration
- Real government scheme APIs
- AI-based scheme recommendation

## Developed By
Team Salvatores  
Hackathon Prototype Project  

## Conclusion
GramSetu demonstrates how technology can simplify access to government welfare schemes and improve transparency, accessibility, and efficiency.
This prototype shows the potential for a scalable, real-world digital public infrastructure solution.
