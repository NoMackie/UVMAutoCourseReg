# UVMAutoCourseReg
A barely function program by a novice programmer that automatically registers you for your courses based on CRNs.
Made by Gabe Lattanzi, inspired by Aaron Perkel

Note: I'm assuming this is probably against University policy somehow so please don't actually use this! Or if you do, don't use the scheduled submission, only the one that does it instantly.
Note 2: Again for now please only use the "now" registration type, as this program is also not built to handle refreshing the page to make sure you're on the correct page.


Directions:

1. Choose test run or official run
	A test run will NOT hit enter after typing in CRNs. This is to make sure your mouse pointer correctly gets the position of the text boxes.
	An official run WILL hit enter after typing in CRNs. Only use this when you're actually registering, or you're on a simulation site.

2. Enter your number of courses, and their respective CRNs.

3. Hover your mouse over the FIRST CRN box on the registration site and hit enter. DO NOT MOVE the window for course registration after calibrating the textbox position, and make sure you still have the program selected when you hit enter so that it actually detects the position.

4. Choose if you'd like to register now or later (type "now" or "later")
	Registering now will literally register now, with a 3 second delay. 
	Registering later will let you schedule a time to register. Use format MM/DD/YYYY with time format HH:MM:SS. Include a AM/PM after your time selection.
		If you're registering for later, allow some padding. System time may not match up with website time. 

5. If you ran a test run and it worked, you can do an official run.



If you choose to use this and it messes up your course registration do not harass me, I've tested it several times on both the official website and a test site to ensure that it functions properly. If it doesn't function for you make sure you've correctly calibrated the mouse position, not moved the registration window after calibration, and kept the registration window tabbed in and open.

The window detection looks for "add/drop/withdrawal" or "course registration" to know which window to type into. If your registration page says something different, this may not work for you.





