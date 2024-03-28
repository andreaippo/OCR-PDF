# OCR&PDF
Dolphin Service Menu entry to OCR&amp;PDF image files

# Pre-requisites
tesseract must be installed on your system

# Manual install
Copy the .desktop file to `$HOME/.local/share/kio/servicemenus/`

# KDE install via the `Get New...` feature
Open Dolphin and go to `Configure` -> `Configure Dolphin...` (or press `CTRL + SHIFT + ,`)
Then go to the `Context Menu` section and click the button `Download New Services...` and search for OCR&PDF, then click `Install`

# Changing the lannguage used for OCT
Go to the install path, open the `.desktop` file corresponding to this Service Menu entry with any text editor, and change the value of `tesseract`'s `-l` argument from `eng` to the one of your liking (3-character ISO 639-2 code)
