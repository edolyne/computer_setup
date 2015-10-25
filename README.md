# Sync Fonts With DropBox

### Source Mac

(The Mac you want to copy your Fonts folder from)

    Launch Terminal in Applications/Utilities/
    Run cd ~/Library to open your user Library.
    Run sudo mv Fonts ~/Dropbox to move your Fonts folder to your Dropbox.*
    Enter your password when prompted.
    Run ln -s ~/Dropbox/Fonts to create a symbolic link in your User Library.*

### Destination Mac

(Any Mac you want to copy your Fonts folder to. NOTE: This will DELETE your user Fonts folder.)

    Launch Terminal in Applications/Utilities/
    Run cd ~/Library to open your user Library.
    Run sudo rm -r Fonts to delete your user fonts folder.
    Enter your password when prompted.
    Run ln -s ~/Dropbox/Fonts to create a symbolic link in your User Library.*
