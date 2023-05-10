# Small project: Substances Chatbot
Python program (.ipynb) which utilizes a chatbot takes as input the name of any substance and provides back all the necessary information (dosage, side effects, etc.) from Wikipedia.
The program can run in Jupyter Notebook, and the only pre-requirement is to install Wikipedia module beforehand via pip method.
The program runs quickly and gives the information feedback rather quickly.
The code is efficient because it implements a caching mechanism which stores the substance information in dictionary, thus when user inputs the same substance later, the information will be retrieved from the cache instead of making another API request which would make it slower.
