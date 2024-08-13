# Real-Time Location Sharing App

![image](https://github.com/user-attachments/assets/3b914320-bdc5-4862-b448-d4e2a68cff7c)


## Overview

This Real-Time Location Sharing App is a web application that allows users to share their live location with others in real-time. Users can create a unique sharing ID, share it with friends or colleagues, and see their location updates on an interactive map.

## Features

- **Live Location Updates:** See real-time location updates of users on an interactive map.
- **Sharing ID:** Each user is assigned a unique sharing ID for easy sharing and tracking.
- **Path History:** View the historical path of a user's location updates.
- **User-Friendly Interface:** Simple and intuitive interface for seamless user experience.

## Technologies Used

- **Node.js:** Backend server built with Node.js and Express.
- **Socket.IO:** Enables real-time communication between the server and clients.
- **Leaflet:** JavaScript library for interactive maps.
- **Bootstrap:** Frontend styling and layout.
- **jQuery:** Simplifies DOM manipulation and event handling.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/StrugglerSuryansh/realTimeTrackingSysytem.git
   cd realTimeTrackingSysytem```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Start the Server:**
   ```bash
   npm start
   ```

4. **Open in Browser:**
   Open your web browser and go to [http://localhost:80/](http://localhost:80/)

## Usage

1. **Share Location:**
   - Click on "Share My Location" to generate a unique sharing ID.
   - Share the ID with friends or colleagues.

2. **Watch Location:**
   - Visit [http://localhost:80/sharingid/{your-sharing-id}](http://localhost:80/sharingid/{your-sharing-id}) to watch a specific location.
   - View real-time location updates and historical path.

## Contributing

Contributions are welcome! Feel free to open issues and pull requests.
