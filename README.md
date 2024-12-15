# Video Chat Website

A simple video chat application built using HTML, CSS, and JavaScript, utilizing the Agora SDK for real-time video and audio communication.

## Features
- Real-time video and audio streaming
- Join and leave video chat sessions
- Mute/unmute microphone
- Enable/disable camera
- Responsive user interface design

## How to Run

### Prerequisites
- A web browser (e.g., Chrome, Firefox, or Edge)
- A valid Agora App ID and Token

### Steps
1. Download or clone the repository:
   ```bash
   git clone https://github.com/xenon1919/Videochat-Website/tree/main
   cd VIDEOCHAT WEBSITE
   ```

2. Replace the Agora configuration in `script.js` with your own:
   ```javascript
   let config = {
       appid: 'YOUR_APP_ID',
       token: 'YOUR_TOKEN',
       uid: null,
       channel: 'livechat'
   };
   ```

3. Open the `index.html` file in your browser.

4. Enter your name and click "Join Stream" to start the video chat.

## Project Structure
```
├── index.html         # Main HTML file
├── style.css          # Styling for the app
├── script.js          # JavaScript logic for video chat
├── assets/            # Icons and assets for the UI (not included in uploaded files)
```

## Technologies Used
- HTML5
- CSS3
- JavaScript (ES6)
- [Agora RTC SDK](https://www.agora.io/)

## Project Details
- The application uses Agora RTC SDK for video and audio streaming.
- Users can toggle their camera and microphone during a session.
- The UI is styled using `style.css` for a clean and modern look.

## License
This project is open-source and available under the [MIT License](LICENSE).

---
Feel free to modify and improve the project. Contributions are welcome!
