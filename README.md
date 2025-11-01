# Gesture-Voice-Eye-Controller
A multi-modal human-computer interaction system combining gesture recognition, voice commands, and eye tracking for seamless virtual control.

# Features

## VoiceBot Controls :
  -  Hi / Hello / What is your name
  -  Current Date and Time                           
  -  Google Search/ Open Chrome
  -  Find Location
  -  File Navigation 
  -  Copy and Paste
  -  Sleep/Wake-up
  -  open calculator / notepad
  -  Launch gesture / Start gesture - Start gesture control
  -  Stop gesture / Close gesture - Stop gesture control

exit commands : "Bye" / "Goodbye" / "Exit" / "Quit" - Close voice assistant

## KeyBoard Controls :
🖐 Open Hand - Move cursor over keys

✌ Index + Middle Finger Pinch - Click/select key
Bring index finger (8) and middle finger (12) close together (< 30px distance) to "press" a key

## Eye Movement controls :
👀 Look at Screen - Cursor follows your gaze

😉 Left Wink - Left click

😉 Right Wink - Right click

😑 Double Blink - Double click

👁 Stare/Hold Gaze - Click and drag

## Gesture Controller (MediaPipe - Hand Tracking) :
Basic Mouse Controls:
🖐 PALM (Open Hand)
Action: No specific action
Description: Default resting state

✌ V_GEST (Victory/Two Fingers)
Action: Move cursor
Description: Index and middle finger extended (like peace sign) moves the mouse pointer

✊ FIST (Closed Hand)
Action: Mouse drag/hold
Description: Clenched fist acts like holding mouse button down for dragging

👆 INDEX (Index Finger Only)
Action: Right-click
Description: Single index finger extended performs right-click

🤟 MID (Middle Finger)
Action: Left-click
Description: Specific gesture triggers left-click

✌ TWO_FINGER_CLOSED
Action: Double-click
Description: Two fingers close together performs double-click

🤏 PINCH_MINOR (Minor Pinch)
Action: Scroll (vertical/horizontal)
Vertical Scroll: Pinch movement up/down
Horizontal Scroll: Pinch movement left/right with Shift+Ctrl

🤏 PINCH_MAJOR (Major Pinch)
Action: System controls
Vertical: Adjust system volume
Horizontal: Adjust screen brightness

## Procedure

Open Anaconda Prompt and clone the repository 
```bash
https://github.com/Akhila1908/Gesture-Voice-Eye-Controller.git
```
Step 1:
```bash
  conda create --name gest python=3.9.24    
```
( instead of 3.9.24 place your python version )
for python version : 
```bash
python --version
``` 
Step 2:
```bash
  conda activate gest
```
Step 3:
```bash
  pip install -r requirements.txt
```
Step 4:
```bash
  conda install PyAudio

  conda install pywin32
```
Step 5:
```bash
  cd to the GitHub Repo till src folder
```
Command may look like: cd C:\Users\.....\Gesture-Controlled-Virtual-Mouse\src

Step 6:
For running GUI:
```bash
  python main.py
```


# Output : 
(mouse) C:\Users\..\Gesture-Controlled-Virtual-Mouse-and-Keyboard\src>python main.py
✅ main.py started
✅ Camera is accessible
Testing TTS...
TTS test done.
✅ Speech recognition available
✅ App module available
✅ Imported all modules successfully.
✅ App icon loaded
✅ Loaded bot.png
✅ Loaded keyboard.png
✅ Loaded hand.png
✅ Loaded eye.jpeg
✅ Loaded exit.png
✅ GUI setup complete, launching window...
🖐 Gesture Control started
👁 Eye Control started
👁 Starting Eye Controlled Mouse...
Controls:
😉 Left Wink - Left click
😉 Right Wink - Right click
😑 Double Blink - Double click
👁 Stare/Hold Gaze (1.5s) - Click and drag
Press 'Q' to quit
model with a single signature inference. Disabling support for feedback tensors.
📝 Key pressed: .
📝 Key pressed: /
📝 Key pressed: K
📝 Key pressed: J
📝 Key pressed: N
📝 Key pressed: B
📝 Key pressed: F
📝 Key pressed: D
📝 Key pressed: C
📝 Key pressed: D
📝 Key pressed: S
📝 Key pressed: R
🎹 Virtual Keyboard Closed
✅ Window closed

# Images : 

## 1.Main Page : 
<img width="498" height="320" alt="Screenshot 2025-11-02 010259" src="https://github.com/user-attachments/assets/dc266db5-9959-4c33-b3dc-5ced804e49e1" />

## 2. Keyboard working :

<img width="632" height="381" alt="Screenshot 2025-11-02 010433" src="https://github.com/user-attachments/assets/acb241ba-cc82-440a-bd2d-3a140d7ad81c" />

<img width="638" height="380" alt="Screenshot 2025-11-02 010540" src="https://github.com/user-attachments/assets/379c9911-411a-4a1c-ae31-203fbf23dcb5" />

## 3. Voice Assistant Working :

<img width="395" height="488" alt="Screenshot 2025-11-02 010756" src="https://github.com/user-attachments/assets/5dd39adc-1813-4d9f-994b-5a56cc089b41" />
<img width="903" height="495" alt="Screenshot 2025-11-02 011055" src="https://github.com/user-attachments/assets/b9830502-be49-4ee2-8024-2fcc94dd676c" />

