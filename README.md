# open-terminal-in-folder-ubuntu
Steps for opening terminal in any folder automatically

**Reference** : [Keyboard shortcut for “open a terminal here”]         (http://askubuntu.com/questions/68078/keyboard-shortcut-for-open-a-terminal-here)

## Steps :

* Open the terminal.
* Install **dconf tools** using the following command.

  ```  sudo apt-get install dconf-tools nautilus-open-terminal  ```
  
* Then, run **dconf editor** by using the following command.

  ```  dconf-editor  ```
* Now **dconf editor** window opens, go to **org** -> **gnome** -> **desktop** -> **interface** and enable **can-change-accels** value and close the window.
* Now run the following command in the terminal.

  ```  nautilus -q  ```
* Now, you can see **Open in Termianl** option by right clicking in any folder.
