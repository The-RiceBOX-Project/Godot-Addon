This is the Source code for the Godot addon used for the RiceBOX Controller.


# How to use
1. Download godot mono
2. Download .NET if you don't have it
3. Open the project
4. Project -> Tools -> c# -> create c# solution
5. Open the project directory in a terminal or CMD
6. Type the following command: `dotnet add package System.IO.Ports --version 7.0.0`
7. When finished, close the terminal
8. In the editor, create a folder "addons" without quotes, case sensitive
9. Put the addon file inside it
10. Save
11. Project -> Project settings -> Plugins -> enable it
12. Select and add the arduino node
13. Make sure the name of the arduino node in the scene tree is in lower case
14. Click on it and set its baud rate and port name through the inspector
15. Wire the signal to the node that has the script in which you want to use the arduino information
16. Profit
