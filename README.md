# Three Buttons Keyboard

## About this Project
This project limits the number of buttons on your keyboard to make it easier to use and simplifies your typing experience. You no longer have to worry about clicking too many buttons every day to type out anything, you can instead use just three buttons to do all of the same things you would do with all the regular keys.
There are three buttons wired to a T-Cobbler using a breadboard so that the program accepts the GPIO pins connected to the buttons as input. So, when each button is pressed, it performs a different function that writes in morse code and when the button is pressed that triggers the end of a word, it completes the morse code word translation and prints the word into the console. The program uses one module, the Rpi.GPIO module enables the buttons to function with the GPIO pins. The program also uses five functions, one to interpret the morse code and four to run when the buttons are pressed. Three are triggered when each button is pressed and the fourth is triggered after each button is pressed, to reset the button and stop sending power to it. Finally, there is a while statement that will run until the user manually stops the program. The while statement contains conditional statements that will check if any of the buttons have been pressed and when they are, it will call on the appropriate functions.


The project’s code does not yet work entirely correctly. If the code did function correctly, the dot, line, and translated code would appear once and they would type out the dots and lines before translating it into a more legible letter. However, the code is not entirely functioning yet, so the video attached displays what is does so far. 


## Materials
- Raspberry Pi
- Breadboard
- T-Cobbler
- Cable to connect Raspberry Pi to a desktop to access code
- Keyboard and mouse to use desktop  with Raspberry Pi
- Nine Male-Male Wires
- Three Button Switches

## Wiring
Insure T-Cobbler is properly connected to Raspberry Pi and Breadboard
Connect Raspberry Pi to Desktop, keyboard, and mouse
Organize wires by color either depending on the button they connect to or the specific function they control for the buttons. I chose to organize them by the latter. 
Insure each wire is connected correctly, 
