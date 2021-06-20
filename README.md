#Meteorological Data
This project works around some meteorologic statistics in order to manipulate them in any desired way. An example is provided with an user interface featuring data for 10 major mexican cities. 

![Cover](/Assets/Background.png)
####Requirements:
- Jupiter Notenook SetUp
- Python 3 installed
- tkinter python library

####How to use:
In your Jupiter Notebook open the interface.ipynb file and execute the whole kernel. An interface will be displayed, giving you 10 optional cities to choose from. Dependeing on the selected city, the buttons of the screen will display major information about their humidity, temprerature, wind conditions and general data related to their distance to the nearest sea.
####Setting up your own system:
If you wish to have this system with your own selected cities, follow these steps.

- Go to https://openweathermap.org/api and check if the city you want to work with is available in the browser of the page.
- If so, open the First Capture.ipynb file and replace the names of the cities with your own set of names, then, replace the given links and just change two lines: the name of the city and the code of the country (for example, Virginia, us)
- Change all the name parameters to adjust them to your cities selected.
- Execute the notenook kernell for the data to be saved in the metada folder.
- At the Met Analysis.ipynb file change the same parameters to be the same as the ones you just changed in the previous steps, execute the notebook kernel. Note: You can play around the data: add more multiple linear regression, try to obtain new predictions, anything you want.
- It is necesary to go to the Met Data.ipynb file to change the file names and execute the kernel, for the data to be stored in the right way for the user interface to work.
- Finally, go to the Interface.ipynb file and change again all the name parameters, after that, execute the kernel for the interface to be displayed.
- Bonus: Go to the assets folder and check the images used fot the interface. Feel free to change the background, the buttons and any asset in order to match your style, your added options or language.
- Feel free to modify settings, add your own functions and play around with the data in order to obtain more and better results.