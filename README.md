# pg_app

Created by: Tyler Kay

This application uses the csv menu file to load the website and generate word documents of the menu.

### Editing prices

Open up the menu.csv file and edit the prices of each item. Save the csv file.

### Generating word document menu:

- On Windows:
  - Run the driver.exe executable. An Output directory should be created where the word documents were generated.
- On Google Drive:
  - Click the driver.ipynb file. This will take you to a google colabatory workspace. Click the play button. An Output directory should be created where the word documents were generated.
- Running through python. Run python3 driver.py. An Output directory should be created where the word documents were generated.

### Configuration:

To configure the files, edit the config.ini file. This file is responsible for the input/output file names, name of the new directory created, and where the template word documents are located.

#### Other Notes:

- To compile into .exe, install pyinstaller. Run the command pyinstaller --onefile driver.py

#### Github Repository: https://github.com/TylerKay/Panda_Garden_Menu

#### Last updated: 8/20/2022
