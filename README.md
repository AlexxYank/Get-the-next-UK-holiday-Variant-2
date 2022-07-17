# Get the next UK holiday - Varian 2
UiPath Project

## Purpose
Shows the next UK holiday by given date and country

## Input
User fills a specific date and country(only countries that are part of the United Kingdom) in the "Assign the input date and country" sequence in the Main.xaml.
  The default assigned values are: 
  * Date: "01-July-2022"
  * Country: "england-and-wales"

## Process Steps
1. Gets the holidays as JSON from the official UK government API using an HTTP Request.
2. (Using UiPath Activities) Finds the next holiday after the given date.
3. Shows the result in a Message Box.

## Error Log
In the ErrorLog.xaml you can assign a log file name and a folder path.
By default are assigned to:
* File name: "log.txt"
* Folder path: "C:\UK holidays log\"
