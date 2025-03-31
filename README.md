# ROSE Screening – Event Management Platform

This project presents a web application developed to support the coordination of cervical cancer screening events for low-income individuals in Malaysia.

The goal of this project was to improve access to preventive healthcare by creating a digital platform that enables participants to book appointments, volunteers to contribute their time and skills, and administrators to manage events and resources efficiently.

## Overview

Access to preventive healthcare services can be limited by poor event coordination and communication. This project addresses these challenges by implementing a multi-user platform that offers:

- Participant self-registration and booking functionality
- Volunteer registration with skill-based event matching
- Administrator control over user management, event scheduling, and eligibility confirmation
- Sponsor registration for ongoing newsletter communication

The platform was built using React and includes a built-in chatbot for answering frequently asked questions.

## Methodology

- **Technology Stack**: React, Tailwind CSS  
- **Libraries Used**: `react-calendar`, `react-icons`, `react-chatbot-kit`, `react-hot-toast`, `html2canvas`, `jspdf`, `bcryptjs`

- **System Features**:
  - Role-based user accounts (Participant, Volunteer, Admin)
  - Event booking, waitlisting, cancellation, and rescheduling
  - Chatbot support for participant queries
  - PDF generation for administrative use
  - Email/password authentication with hashed credentials

- **User Access**:
  - Participants and volunteers register through public forms
  - Admin credentials are pre-generated for event oversight
  - Sponsors can sign up to receive newsletters

## Ethical Considerations

- **Healthcare Access**: The system supports underserved populations by offering free and accessible screening events through digital tools.
- **Data Protection**: All user data is stored securely and used solely for their intended purpose within the platform.
- **Volunteer Rights**: Volunteers retain control over their participation and can accept or decline assigned events.

## Future Work

- Add multilingual support to broaden accessibility
- Integrate automated SMS/email reminders for event bookings
- Expand chatbot functionality using NLP techniques
- Develop an accompanying mobile application for broader reach
- Implement document upload for eligibility verification

## Setup Instructions

To run this project locally, make sure you have the following dependencies installed:

- Node.js (version 14 or higher)
- npm (Node Package Manager)

Then follow these steps:

```bash
# Clone the repository
git clone https://github.com/yourusername/rose-screening.git
cd rose-screening

# Install dependencies
npm install
npm install html2canvas jspdf
npm install react-calendar
npm install react-icons --save
npm install react-chatbot-kit
npm install react-hot-toast
npm install bcryptjs
npm i -D

# If Tailwind CSS is not already configured, install:
npm install -D tailwindcss postcss autoprefixer

# Start the development server
npm run dev
```

## Demo Credentials

The following demo accounts can be used to explore role-based functionality:

| Role        | Email                    | Password       |
|-------------|--------------------------|----------------|
| Head Admin  | bobby@gmail.com          | bobby          |
| Admin       | katy@gmail.com           | katy           |
| Participant | farah@gmail.com          | farah          |
|             | aisha@gmail.com          | aisha          |
|             | sandra@gmail.com         | sandra         |
|             | rebecca@gmail.com        | rebecca        |
|             | alice@gmail.com          | alice          |
| Volunteer   | rahman.lee@gmail.com     | volunteer123   |

Users can log in via the top navigation bar. New accounts can also be created through the “Become a Participant” or “Become a Volunteer” forms.

## Acknowledgements

This project was developed as part of the **Team Project & Professionalism KV6002** module at Northumbria University to support cervical cancer screening initiatives in Malaysia.
