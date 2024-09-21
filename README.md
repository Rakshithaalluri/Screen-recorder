## Screen Recorder
A simple web-based screen recorder that allows users to record their screen, capture images, and apply filters in real-time. The project uses HTML, CSS, and JavaScript, utilizing the MediaRecorder API for recording and canvas manipulation for capturing images.

### Features
Record Video: Users can record their screen in mp4 format and download the video.
Capture Images: Users can take screenshots of the current screen and save them as images (jpeg).
Filters: Apply different filters to the screen for image capture or during recording.
Timer: Displays a timer while recording.
Responsive Design: Optimized for various screen sizes, including mobile and tablet devices.

Live Demo
https://screen-recorder-eosin.vercel.app/

### Technologies Used
HTML5: Structure of the application.
CSS3: For styling, animations, and media queries.
JavaScript: Core logic for video recording, capturing, and applying filters.
MediaRecorder API: To capture the user's screen as a video.
Canvas API: For capturing screenshots from the video.

## How to Use
### 1.Clone the repository:
git clone https://github.com/yourusername/screen-recorder.git
### 2.Navigate to the project directory:
cd screen-recorder
### 3.Open the index.html file in your browser:
open index.html
4.Grant screen permissions for the recorder to access your screen.
5.Use the Record button to start recording and the Capture button to take a screenshot. The files will be automatically downloaded.

## File Structure
screen-recorder/
│
├── index.html          # Main HTML file
├── style.css           # CSS file for styling
├── index.js            # JavaScript logic
└── README.md           # Project documentation

## Future Improvements
Add audio recording: Currently, the screen recorder only captures video.
Multiple filter options: Allow users to apply more filter options dynamically.
Custom file names: Let users specify custom names for the downloaded files.

