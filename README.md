THE STOPWATCH

⏱️ Za Warudo Stopwatch
A simple, lightweight desktop stopwatch app built with Python 3.13 and PyQt5. I built this to have a super high-visibility digital display that tracks time right down to the centisecond (10ms intervals). It uses an event-driven timer so it doesn't hog your CPU while running in the background.
🌟 Features
• Super Accurate: Tracks time down to 10-millisecond intervals.
• High-Visibility UI: A clean, bright red digital panel that you can see from across the room.
• Responsive Layout: The buttons stretch and adapt nicely if you resize the window.
• Custom Styling: Cleaned up the default Windows look using custom Calibri font styling and clean padding.
🚀 How to Get It Running
📋 What you need<img width="1366" height="768" alt="Screenshot (9)" src="https://github.com/user-attachments/assets/79239370-8184-495a-979f-ef34b0e1c213" />

• Python 3.13+
• PyQt5
📥 Setup Guide
1. Grab the code
Save the script on your computer as stopwatch_app.py.
2. Install PyQt5
If you try to run it and get a ModuleNotFoundError: No module named 'PyQt5' error, you just need to install the library. Open up your Command Prompt and type:
cmd
python -m pip install PyQt5
Use code with caution.
(Note: If your system path is acting up and giving you a "pip is not recognized" error, use the global launcher instead: py -m pip install PyQt5)
3. Run the App
You can launch it from your terminal:
cmd
python stopwatch_app.py
Use code with caution.
Or just open the file inside Python's IDLE editor and hit F5.
🔧 Bugs I Fixed Along the Way
• The Lowercase Class Crash: I originally wrote the class name in lowercase (class stopwatch) and then named the application instance the exact same thing (stopwatch = stopwatch()). This accidentally deleted the class reference in Python and crashed the script. I fixed it by changing the class to standard uppercase PascalCase (class Stopwatch).
• IDLE Shell Syntax Errors: I kept getting SyntaxError: invalid decimal literal when trying to test blocks of code. Turns out pasting multiline loops/classes directly into the live IDLE Interactive Shell (>>>) ruins the indentation. I fixed this by always writing code in a proper script file (File -> New File) instead of the live terminal
