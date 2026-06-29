# DPblaster! by DECS

Official Profile Picture Creator for DECS Students

![DPblaster Banner](dpblast_logo.png)

## Overview

DPblaster! is a responsive web application that allows students to generate official profile pictures for department-wide campaigns, semester launches, and organization activities.

Users can:

- Upload a profile photo
- Select a department frame
- Adjust image position and zoom
- Generate an official caption automatically
- Download a high-resolution profile picture
- Copy the generated caption with one click

The application is optimized for both desktop and mobile devices and runs entirely in the browser without requiring a backend server.

---

## Features

### 🖼️ Profile Picture Generator

- Upload custom profile images
- Live preview rendering
- High-resolution 1080×1080 output
- Instant frame application
- Mobile-friendly workflow

### 🎨 Frame Selection

- Computer Engineering (CpE) Frame
- Computer Science (CS) Frame
- Visual frame previews
- Active frame highlighting

### ⚙️ Image Adjustment Tools

- Zoom In / Zoom Out
- Move Up
- Move Down
- Move Left
- Move Right
- Reset Position

### ✍️ Caption Generator

Automatically generates an official DECS DP Blast caption using:

- Student Name
- Course Section

Includes:

- Department branding
- Welcome message
- Semester campaign message
- Official hashtags

### ⬇️ Download System

- One-click download
- Mobile long-press save support
- PNG output format

### 📱 User Experience

- Modern glassmorphism interface
- Responsive design
- Animated loading screen
- Sticky navigation header
- Browser compatibility detection
- Facebook/Messenger browser warning

### 👥 Visitor Tracking

- Local visitor counter
- Stored using LocalStorage
- No external analytics required

---

## Technology Stack

### Frontend

- HTML5
- CSS3
- Vanilla JavaScript

### Browser APIs

- Canvas API
- Clipboard API
- LocalStorage API
- File API
- Object URL API

### Design Features

- Responsive Layout
- Glassmorphism UI
- Mobile-First Design
- CSS Animations
- Accessibility Enhancements

---

## Project Structure

```text
DPblaster/
│
├── index.html
│
├── dpblast_logo.png
├── decs.png
├── decs_logo_small.png
├── acoes.png
├── ccss.png
│
├── cpe_frame.png
├── cs_frame.png
│
└── README.md
```

---

## Required Assets

| File | Purpose |
|--------|----------|
| dpblast_logo.png | Main application logo |
| decs.png | DECS logo |
| decs_logo_small.png | Floating badge logo |
| acoes.png | ACOES logo |
| ccss.png | CCSS logo |
| cpe_frame.png | Computer Engineering frame |
| cs_frame.png | Computer Science frame |

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/comsci-decs/DPblaster.git
cd DPblaster
```

### Run Locally

Open:

```text
index.html
```

or use a local web server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

---

## Usage

### Step 1
Enter your full name.

### Step 2
Select your course and section.

### Step 3
Choose a profile frame.

### Step 4
Upload your profile photo.

### Step 5
Adjust image placement and zoom if needed.

### Step 6
Download your generated profile picture.

### Step 7
Copy the generated caption and post it.

---

## Browser Support

### Recommended Browsers

- Google Chrome
- Microsoft Edge
- Safari
- Opera

### Limited Support

The application will display a warning when opened inside:

- Facebook Browser
- Messenger Browser

For best results, open the application in a standalone browser.

---

## Privacy

DPblaster processes all images locally in the user's browser.

- No photos are uploaded to a server.
- No personal information is collected.
- No account is required.
- Visitor counts are stored locally using browser LocalStorage.

---

## Credits

### Development

**Michael Ordenes**

### Graphics

- Ickoh Gecolea
- Angelic Napa

### Organizations

- Department of Engineering and Computer Studies (DECS)
- Association of Computer Engineering Students (ACOES)
- Council of Computer Science Students (CCSS)

---

## License

This project is intended for educational and organizational use.

All organization logos, branding materials, and campaign assets remain the property of their respective organizations.

© DECS • ACOES • CCSS • All Rights Reserved
