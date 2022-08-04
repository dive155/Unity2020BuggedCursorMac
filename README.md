# Unity2020BuggedCursorMac

There is a bug with mouse that occurs on Unity 2020.

Case 1:
1) Build the app with Unity 2019
2) Open the app, stretch the window to 16:9 or wider
3) Try to click on buttons in the rightmost region of the screen

Observer result: The button under the pointer is clicked.


Case 2:
1) Build the app with Unity 2019
2) Open the app, stretch the window to 16:9 or wider
3) Try to click on buttons in the rightmost region of the screen

Observer result: The button below and to the right of the pointer is clicked
Expected result: The button under the pointer is clicked.