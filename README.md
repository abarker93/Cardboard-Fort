# Cardboard Fort
Data Entry and Storage program for graded cards.

Installation:
  Required interpretters will include:
    pip, openpyxl, tkinter, future, setuptools, wheel
    
  Ensure that you install these interpretters in the IDE where the program can find them!
  
  Topic - A PSA (Professional Sports Authenticator) card slab, also known as encapsulated cards, GUI/data space that can be manipulated, and allows for quick referencing. There are a few mobile applications that do this currently, but only provide clunky and subjective data. People in the trading card game marketspace would like an easier way to track their own values with their own frame of reference instead; I am among those people.
•	Name: Cardboard Fort V.03
•	Purpose: Keep track of graded cards from point of purchase price. Input current market price and it will be stored or replace the previous current market price. Displays these variables, as well as the percentage difference between the two prices.
•	Reason: The reason I am designing this application is because the TCG (trading card game) consumer-base, and the coinciding marketspace, are growing rapidly. Many people do not like the unreliable systems provided by current services as they are only accurate to their own portion of the market usually and thus do not generally reflect an accurate price. The user can use whatever methods they prefer to determine current market value, and input that to see the percentage difference between their initial purchase and the value they previously calculated.
•	Target Audience: Any consumer in the TCG marketspace that would like a simplified way of keeping track of their PSA graded cards without certain hassles. Typically, the “value” aspect of this hobby/market is only relevant to teenagers and adults.
Checking in Pt. 1/2:
	Things are moving along quite nicely. I started working on the structure I’d like first, and then started work on how to go about that in Python. As for data entry, which will come after I’ve built a completed version of the GUI-related things, I struggled to figure out how to link to an Excel doc. I do believe I found the solution in openpyxl for this, as it includes specific structure in the same way Tkinter does for GUI design. I also just added a dropdown box, and am playing around with a wheel. I’m hoping someone can let me know which they like better!
 
Checking in Pt. 3:
	My main concern this time around was getting openpyxl into Pycharm, writing code to create implement file creation, and store it. I was able to add an Exit button that completely closes the program without errors that I can find at this time. A background image was set up, with the main window frame being locked to the aspect ration of the image. I also managed to get the Submit button completed and functioning.
