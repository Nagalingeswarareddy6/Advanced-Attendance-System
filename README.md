# Advanced-Attendance-System

**Overview**

This is a comprehensive attendance tracking system that combines:

1.Face recognition technology

2.QR code scanning

3.Attendance record management

4.User registration

**Features**

1. **Face Recognition Attendance**

Real-time face detection using camera feed

Visual overlay for detected faces

Manual capture option

Status indicators for system readiness

2. **QR Code Attendance**

QR code scanning functionality

Personal QR code generation for each user

Downloadable QR codes

Visual scanning animation

3. **Attendance Records**

Filterable by method (face/QR) and date

Paginated display

Detailed record view with:

User information

Timestamp

Attendance method

Status

4. **User Registration**

Form for collecting user details

Face sample capture interface

Multiple angle requirements for better recognition

**Technical Implementation**

**Frontend**

Built with HTML5, CSS3, and JavaScript

Uses Tailwind CSS for styling

Font Awesome for icons

jsQR library for QR code scanning/generation

**Data Management**

Uses localStorage for data persistence (simulates database in demo)

Mock database with:

User management

Attendance recording

Data filtering

**Setup Instructions**

Clone the repository or download the files

Open index.html in a modern web browser

The system should work without any server requirements (runs client-side)

**Usage Notes**

1.**Face Recognition Tab:**

Requires camera access

Simulates face detection (no actual recognition in demo)

2.**QR Code Tab:**

Click "Start Scanning" to begin QR code detection

Your personal QR code is automatically generated

3.**Attendance Records:**

View all attendance records

Filter by method or date

Navigate through pages

4.**Register New User:**

Fill in user details

Capture multiple face samples

Submit to register new user

**Browser Compatibility**

1.Works best in modern browsers (Chrome, Firefox, Edge)

2.Requires camera access permissions

3.May not work on some mobile browsers

**Limitations (Demo Version)**

1.Face recognition is simulated

2.No actual face matching algorithms

3.Data persists only in browser localStorage

4.No user authentication
