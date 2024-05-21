# mackworth-clock-test
mackworth clock test with js

Project Purpose:
To digitally adapt the Mackworth Clock Test to measure fatigue and attention levels. This involves testing users' attention levels over a specific period and recording the results.

Features:
Start Screen:

The test begins when the user presses the spacebar.
The screen enters fullscreen mode with a black background.
Test Screen:

The user follows signals that appear at specific intervals and presses the spacebar at the right time.
There must be a 5-second difference between the two main signals during the test period.
If the user presses the spacebar at the correct time, it is recorded as a success, and if at the wrong time, it is recorded as an error.
Result Screen:

When the test is complete, the user is shown the correct and incorrect presses, as well as missed signals.
The results can be downloaded as a JSON file.
Adjustable Parameters:

Parameters such as the frequency of signals and the total duration of the test can be adjusted according to user needs.
Technical Details:
HTML and CSS: Used for the page structure and style definitions.
JavaScript and jQuery: Manages the dynamic behaviors of the application, generates signals, and records user interactions.
Fullscreen Mode: Used to enhance the user experience.
JSON File Download: Used to provide the test results to the user.
You can further develop this structure to make the test work with different parameters. For example, you can customize the signal durations, the total duration of the test, and the feedback given to the user.
