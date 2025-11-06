# Overview

## OCR video player, for TAFE AP 2025-semester 2 project
M.H. J336025.  From 28/10/2025.

Purpose: Create a video player which can run OCR on selected frames, for text-to-voice.

Server uses fastAPI, allows client to upload a frame for OCR, and get the text back.

Possible Clients
- Web-enabled video player, for local or remote video files, including Youtube.
- An esp32cam based device, which can:
    - take a photo
    - run OCR on the server, 
    - display the text on a small screen
    - read the text aloud using local TTS or web API such as Google
- (stretch goal) a Chrome Extension  


Server Requires:
-    "fastapi[standard]>=0.120.1",
-    "opencv-python>=4.12.0.88",
-    "pillow>=12.0.0",
-    "pytesseract>=0.3.13",
- tesseract binary


Client (Player) requires:
- "pyqt6>=6.10.0"
- "pyqt6-webengine>=6.10.0"
- "python-vlc>=3.0.21203"




