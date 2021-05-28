Nautilus batch script based of off https://www.pling.com/s/Gnome/p/1007701/

# Installation

# Ubuntu 20.04
Install python2

```sudo apt install python```

Move the script to nautilus script folders.
Create the directory if it doesn't exist

```mkdir -p $HOME/.local/share/nautilus/scripts```

Download the file nautilus-renamer.py, copy script and make it executable

```cp nautilus-renamer.py $HOME/.local/share/nautilus/scripts/ && chmod u+x $HOME/.local/share/nautilus/scripts/nautilus-renamer.py```

You should now be able to right click multiple files/folder and select the script from right-click Nautilus menu.
