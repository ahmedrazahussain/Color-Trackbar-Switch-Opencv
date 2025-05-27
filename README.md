#Color Trackbar With Switch using Opencv
This Opencv project demonstrates how to use trackbars to create and control colors dynamically. A switch is provided to toggle between displaying the selected color or a blank screen.
##Features
- Trackbars to control Blue, Green, and Red Color intensities (0-255)
- A switch (controlled by the key s) to turn color display On or Off
- Real-time color window display that updates based on trackbar values
##How It Works
- Uses 'cv2.createTrackbar()' to create B, G, R sliders
- A switch trackbar acts as an On/Off toggle
- When the switch is On (value=1), a color-filled window is displayed using the BGR values
- When the switch is Off (value=0), the window stays black
