# OneSensorKeyboard
## About the Project
- This project limits the number of buttons on your keyboard to make it easier to use and similifies your typing expierince. You no longer have to worry about clicking too many buttons evey day to type out anything, you can instead use just three buttons to do all of the same things you would do with all the regular keys.

- There are three buttons wired to a T-Cobbler using a breadboard so that the program accepts the GPIO pins connected to the buttons as input. So, when each button is pressed, it preforms a different fucntion that writes in morse code and when the button is pressed that triggers the end of a word, it compltes the morse code word translation and prints the word into the console. The program uses one module, the Rpi.GPIO module enables the buttons to fucntion with the GPIO pins. The program also uses five functions, one to interperet the morse code and four to run when the buttons are pressed. Three are triggered when each button is pressed and the fourth is triggered after each button is pressed, to reset the button and stop sending power to it. Finally, there is a while statement that will run until the user manually stops the program.  The while statement contains conditional statements that will check if any of the buttons have been pressed and when they are, it will call on the appropriate functions. 

- Supplies Needed
1. Raspberry Pi
2. Breadboard
3. T-Cobbler
4. Nine Male-Male Wires
5. Three Button Switches
