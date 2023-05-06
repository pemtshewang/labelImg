# Windows + Anaconda
^^^^^^^^^^^^^^^^^^
To the group members
```shell
Before using the anaconda, 
1.Go to search bar and search anaconda prompt 
2.Open the anaconda prompt with administrative priviledges
3. The prompt opens with default directory as system32
3.Copy the full path of your desktop and cd into that path
4. Execute the commands below now
1. git clone https://github.com/pemtshewang/labelImg.git
2. cd labelImg
3. Execute the commands below
a.conda install pyqt=5
b.conda install -c anaconda lxml
c.pyrcc5 -o libs/resources.py resources.qrc
d.python labelImg.py # starts the GUI
4. Please separate the original image and labeled images as mentioned earlier in the gdrive
```


Hotkeys
~~~~~~~

+--------------------+--------------------------------------------+
| Ctrl + u           | Load all of the images from a directory    |
+--------------------+--------------------------------------------+
| Ctrl + r           | Change the default annotation target dir   |
+--------------------+--------------------------------------------+
| Ctrl + s           | Save                                       |
+--------------------+--------------------------------------------+
| Ctrl + d           | Copy the current label and rect box        |
+--------------------+--------------------------------------------+
| Ctrl + Shift + d   | Delete the current image                   |
+--------------------+--------------------------------------------+
| Space              | Flag the current image as verified         |
+--------------------+--------------------------------------------+
| w                  | Create a rect box                          |
+--------------------+--------------------------------------------+
| d                  | Next image                                 |
+--------------------+--------------------------------------------+
| a                  | Previous image                             |
+--------------------+--------------------------------------------+
| del                | Delete the selected rect box               |
+--------------------+--------------------------------------------+
| Ctrl++             | Zoom in                                    |
+--------------------+--------------------------------------------+
| Ctrl--             | Zoom out                                   |
+--------------------+--------------------------------------------+
| ↑→↓←               | Keyboard arrows to move selected rect box  |
+--------------------+--------------------------------------------+
