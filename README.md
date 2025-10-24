Python Alarm Clock
A simple alarm clock app I made with Python and Tkinter while learning about GUI development and threading.
What it does
Set a time using the dropdown menus, and when that time hits, it plays a sound. That's pretty much it — nothing fancy, but it works.
I built this mostly to understand how Tkinter works and how to keep a GUI responsive while waiting for something to happen in the background. Turns out threading makes that way easier than I thought.
Features

Set hours, minutes, and seconds with dropdown menus
Plays a .wav file when the alarm goes off
Runs in the background without freezing the interface
Uses only built-in Python libraries

What I used

Python 3
Tkinter for the GUI
Threading to keep things responsive
winsound for the alarm sound (Windows only, unfortunately)

How to run it
Clone the repo and run the script:
bashgit clone https://github.com/gomes26avelino/python-alarm-clock.git
cd python-alarm-clock
python alarm_clock.py
Make sure you have a .wav file for the alarm sound, or update the code to point to your own sound file.
Notes

Only works on Windows because of winsound
If you're on Mac or Linux, you'll need to swap winsound for something like pygame or playsound
The UI is pretty basic — I focused more on functionality than design

Sound Note
This project uses a sound alert when the alarm time is reached.

If you don't have a `sound.wav` file:
- Either replace the sound line with a simple beep (`winsound.Beep(1000, 1000)`)
- Or print a message instead.
- print(" Time’s up! Alarm triggered.")


You can download any free `.wav` sound from [Pixabay](https://pixabay.com/sound-effects/) and place it in the same folder.
