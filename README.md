# proton-ge-update

Based largely on work by laedit (Jérémie Bertrand) [https://laedit.net/2024/08/04/installing-and-updating-ge-proton-automatically.html](https://laedit.net/2024/08/04/installing-and-updating-ge-proton-automatically.html)
Run proton-ge-update.bash script to automatically download the latest version of Proton GE [https://github.com/GloriousEggroll/proton-ge-custom/](https://github.com/GloriousEggroll/proton-ge-custom/) . May work on Steam Deck, probably needs adjustments to at least the guide below.

Restart Steam to have it update the list of Protons that are available (since this Proton is externally added by you).

Git clone this repo to where you want to run the script from.

Run from terminal
``` bash proton-ge-update.bash ```

or 
give the file executable permission for your user
``` chmod u+x proton-ge-update.bash ```
and run from the terminal
``` ./proton-ge-update.bash ```

NB! I have not tested this for the Steam flatpak version, should still work but not sure. This script may stop working in the future and need updating.
