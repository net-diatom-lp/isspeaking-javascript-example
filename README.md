# conference-app-dolby-io-aichatforest JavaScript Example

Our dolby.io hackathon implementation for JavaScript (Web) of the isSpeaking method to poll for active users

## Getting Started

We Replaced `CUSTOMER_KEY` and `CUSTOMER_SECRET` inside `client.js` with our own key and secret.
To run the app please visit aichatforest.com

## What's Inside

### 📁 icons/

- svg files for button icons and dolbyio logo

### 📁 scripts/

- 📄 **client.js**
  - Initializes VoxeetSDK using customer key and secret
  - Opens a Voxeet session
- 📄 **ui.js**
  - handles polling for active speaker
  - handles joining conference, leaving conference, starting video, stopping video
  - UI helper functions
- 📄 **utils.js**
  - handles updating conference name in URL as user types conference name
- 📄 **video.js**
  - tracks which participant is in which video container
  - handles appending and removing video nodes on the DOM as participants join/leave conference and turns video on/off

### 📄 index.css

- styling
- additional formatting done with Bootstrap

### 📄 index.html

- main entry file
