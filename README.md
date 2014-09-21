systemstech-Eagle-Library
=========================

Eagle-Library

Eagle 6.5 format!

Don't click on the files!

<a href="https://github.com/systemstech/systemstech-Eagle-Library/zipball/master">Click here</a> to download this as a zip file. to download this as a zip file.

Installation

Open Eagle and select the Control Panel window.
Choose Options and from the drop down that appears, Directories.
Change the Libraries line from: $EAGLEDIR/lbr to something like:

$EAGLEDIR/lbr:$HOME/external_lbrs (for OS X)

$EAGLEDIR\lbr;$HOME\external_lbrs (for Windows)
Click OK to save your changes.

Eagle will prompt to create the directory if it does not already exist. Note the location and choose Yes to create the directory.

On OS X, $HOME/external_lbrs changes to: /Users/mosfet/external_lbrs/

On Windows, $HOME\external_lbrs changes to: C:\Users\Mosfet\Documents\external_lbrs
Find and open the external_lbrs folder. Unzip and drag railman.lbr into the new external_lbrs folder.

Restart Eagle. The library should be now be usable.
