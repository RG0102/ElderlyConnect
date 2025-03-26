# ElderlyConnect

ElderlyConnect is a user friendly platform designed to help elderly individuals combat loneliness by connecting them with others who share similar interests. The app not only allows users to communicate with one another though chat and group discussions but also provides a Volunteer Feature where seniors can request various types of help, from tech support to grocery assistance. 

![image](https://github.com/user-attachments/assets/84d08276-d6d6-4bfd-a4c7-a11cad4a0890)

## Overview
ElderlyConnect brings together a community of elderly users and volunteers, enabling:
### Social Connectivity:
1. Chat with peers and join interest-based groups.
2. Features include message editing, deletion, and saving.

### Volunteer Support:
1. A dedicated Volunteer Login lets senior request assistance
2. Services include TechHelp, GroceryHelp, Bingo, AppointmentReminder and Book Appointment.
3. Book Appointment: User can book edit, cancel and delete appointments for volunteer services, with all updates being reflected in Firebase in real time.

### Speech Synthesis Integration:
1. Voice Command Support (e.g. Saying "Go to Home Page navigates to the "Home Page").
2. Spoken feedback for errors during login, enhancing usability.

### Role-Based Access Control:
1. Access to specific pages is granted based on user roles, ensuring a secure and organized experience.

### Features
### Chat Application:
1. One-on-one and group chats.
2. Options to edit, delete and save message.

### Volunteer Assistance & Book Appointment:
1. Dedicated Volunteer Login for service reqeusts.
2. Book appointments for various support services, such as TechHelp, GroceryHelp, Bingo, AppointmentReminder, and Book Appointment.
3. Manage appointments by booking, editing, canceling, or deleting them.
4. All appointments changes update Firebase in real-time to keep data synchronized.
   
### Speech Synthesis Integration:
1. Voice commands to navigate the app.
2. Audio feedback for login errors and other notifications.

### User-Centric Design:
1. Simple and Accessible UI tailored for elderly users
2. Easy navigation with clear visual cues and voice guidance.

## Technology Stack
1. Frontend: React, Bootstrap
2. Backend: Node.js
3. Database: Firebase (NoSQL)

## Getting Started

### Prerequisites

1. Node.js (latest stable version recommended)
2. npm or yarn package manager
3. A modern web browser (Chrome, FireFox, Safari, etc)

### Installation
1. Clone the Repository:
git clone https://github.com/RG0102/elderlyconnect.git
cd elderlyconnect

2. Install Dependencies:
For frontend:
cd frontend
npm install

For backend:
cd ../backend
npm install

3. Configuration:
1. Update configuration files (e.g. API keys, Firebase settings) in the /config directory.
2. Ensure that role-based access settings are correctly configured as per your deployment environment.

4. Run the Application:
For development, start both frontend and backend servers:

1. Frontend:
npm start

2. Backend:
npm start

3. Open your browser and navigate to http://localhost:3000 (or your specified port).

## Contact 
For any questions or support, please reach out at suppport@elderlyconnect.org




