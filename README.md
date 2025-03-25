# F1 Race Companion

**F1 Race Companion** is an project aimed at enhancing the Formula 1 race-watching experience for fans—especially those on the go. The ultimate vision is to develop a **CarPlay**-compatible version, allowing users to safely stay updated on live race events whilst driving, through audio commentary and minimal visual cues without the distraction of watching a full video.

---

## **Project Overview**

- **Objective:**  
  Build a system that processes Formula 1 race video and audio to extract key events (e.g., overtakes, crashes) and display corresponding highlights in a driver-friendly, CarPlay-compatible interface.

- **Key Components:**
  - **Audio Extraction:** Extracting the race's audio from raw video using FFmpeg.
  - **Transcription:** Utilizing machine learning (OpenAI’s Whisper) to generate an accurate transcript with timestamps.
  - **Event Detection:** Analyzing transcripts and audio features to detect significant events (with initial focus on overtakes).
  - **Key Frame Extraction:** Capturing representative images (key frames) from the video for each detected event.
  - **User Interface:** Integrating audio playback with visual overlays to highlight events—ultimately designed for CarPlay, ensuring minimal driver distraction.

---

## **Project Progress & Milestones**

- **Folder Structure & Environment Setup:**
  - Established a robust project structure separating raw data, processed data, transcripts, key frames, and code.

- **Audio Extraction:**
  - Successfully extracted audio from the race video using FFmpeg.

- **Transcription:**
  - Re-transcribed audio with improved accuracy using OpenAI’s Whisper (transcription_v2.json).

- **Event Detection (Overtakes Focus):**
  - Developed initial prototypes to detect race events, specifically overtakes, based on transcript keywords and audio analysis.
  - **Note:** Transcript events detection still requires further refinement.

- **Key Frame Extraction:**
  - Implemented a method to extract key frames from the video corresponding to detected events.
  - **Observation:** Current extraction results are not yet fully accurate and need additional tuning.

- **User Interface Prototype:**
  - Built a basic Flask web application that integrates audio playback and event overlays.
  - The UI is a stepping stone towards a fully CarPlay-adapted interface.

---

## **Current Status & Next Steps**

- **Project Status:**  
  The project is currently on hold due to challenges in achieving reliable event detection and accurate key frame extraction.

- **What’s Next:**
  - **Refinement:** Further improve transcript processing and event detection logic, particularly for overtake events.
  - **Enhancement:** Fine-tune key frame extraction for better visual accuracy.
  - **CarPlay Integration:** Develop a more sophisticated, driver-safe UI that meets CarPlay standards.
  - **Expansion:** Broaden the scope to detect additional race events such as crashes, pit stops, etc.

- **Why We Paused:**  
  The current prototypes for event detection and key frame extraction are not sufficiently reliable, necessitating additional development and testing before moving towards the CarPlay version.

---

## **Acknowledgements**

- **Tools & Technologies:**  
  - FFmpeg for audio extraction.
  - OpenAI’s Whisper for transcription.
  - Librosa and OpenCV for audio analysis and frame extraction.
  - Flask for building the web interface.

---

## **Contact**

For more information or to contribute, please contact:  
[Vinayak CM / cmvinayak04@gmail.com]
