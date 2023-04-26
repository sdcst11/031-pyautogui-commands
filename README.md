## SDSS Computing Studies Python Assignment
### Assignment #9 Pyaugotui and Automation (Marks 10)

Objectives:
* Use pyautogui locate image functions
* Use pyautogui mouse controls
* Use pyautogui pixel commands
* Solve a complex problem through planning using code structures
* Make use of prebuilt modules not native to the Python basic installation
* Have programs receive automatic inputs.

Screenshots are one of the most important parts of this project. You will need to keep a collection of **assets** that are screen shots.  Pyautogui will be able to search for them on your screen, and then retrieve the coordinates where they can be found.  We will use this to move the mouse cursor to those  locations and then use the click command to activate them.

#### How to Take Screenshots ####
* windows-I to open up your settings
* search for "print screen".  The option to have print screen to take a screenshot should be found
* open up the link and change the print screen to take a screen shot option to checked (it's a button)
* to save a screenshot to your clipboard, press print-screen button (BlueFn > Print Screen)
* it should give you the option to open snip and sketch where you can save it. You may need to open your notification center

#### Locate Image Commands ####
example1:
using the pyautogui locate image commands

example1a:
how to restrict your image search to a specific region of the screen (speeds up the search)

example1b:
how to make the search "less strict". Sometimes pixelation in the image result in the image not being found. Lowering the confidence can help find images, but lowering it too much can find false positives, especially with numbers. For example, a 0 could be mistaken for an 8 if you're too loose in your confidence

#### Getting Input ####
Look at some of the commands on https://pyautogui.readthedocs.io/en/latest/msgbox.html.  Try experimenting with some of them to get user input while your autobot is running.

#### Mouse Commands ####
Take a look at: https://pyautogui.readthedocs.io/en/latest/mouse.html
Some of the most important commands are:
* pyautogui.position() - gets the current coordinates of the mouse
* pyautogui.click() - clicks the mouse at the current location or you can specificy the location as a tuple
* pyautogui.mouseDown() - presses the mouse button down (but does not release it)
* pyautogui.mouseUp() - releases the mouse button if it is down
* pyautogui.moveTo() - moves the mouse to a specific coordinate

