# Binary-Clock
Imports:

The script imports necessary modules such as tkinter for GUI, BytesIO for handling byte data, pygame for audio playback, time for time-related operations, and gTTS from gtts for text-to-speech conversion.
Initialization:

Pygame and its mixer are initialized to enable sound playback.
Text-to-Speech Function:

The speak function takes text as input and converts it to speech using the Google Text-to-Speech (gTTS) API. The speech output is then played using Pygame mixer.
Time Functions:

timeInWords: Converts the current time into words (e.g., "five minutes past ten AM").
update_time: Updates the binary clock and the time label every second. It also checks the current time format (AM/PM) and adjusts the binary clock accordingly.
GUI Creation:

A Tkinter window is created with a title "Binary Clock" and specific dimensions.
Labels representing the binary representation of hours and minutes are placed on the window.
Labels for "am" and "pm" indicators are placed.
A label for displaying the current time is added.
A button labeled "What's Time Now" is added, which triggers the speak function when clicked.
Button Functionality:

Clicking the "What's Time Now" button triggers the speak function, converting the current time into speech.
Time Update:

The update_time function is called to start updating the time label and binary clock continuously.
Main Loop:

The Tkinter event loop (mainloop()) is started to run the GUI application.
This script creates a visually appealing binary clock and provides an option to hear the current time spoken aloud.
