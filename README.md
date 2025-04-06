# PopUpWindows5000
A customizable program designed to simply run one chosen file.
Includes state of the art Yes and No buttons by stock configuration.
//

By default, the program will have a Yes and No button, along with epic placeholder central text.
In settings, you may customize the central text to your liking and set the file location for the program to follow.
Saving changes, the 'Yes' button will attempt to open your linked file, while the 'No' button will close the program.

Changes are saved in config.xml, this file contains additional exclusive customization options if the user wishes to edit them.
The program requires this config file in order for any changes to persist after closing, including the set file path.
If one is not available, the program will create a config in the current directory on startup.

If the user wishes to move the program launch location, it is recommended to do so by creating a shortcut.
