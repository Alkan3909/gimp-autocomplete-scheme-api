##GIMP Auto-Complete Scheme API for Sublime Text

This auto-complete package covers _1000+_ Procedures and Constants available in GIMP's Plugin API. Yes, all these procedures and constants are now just a few keys away. Simply type some letters of the procedure you want to use in your code. When you press the`Enter`key, the procedure, together with parenthesis and arguments(if any) shall appear at cursor location. You could cycle through the arguments by pressing the`Tab`key.


###Examples


 Text Entered   |  Result
--------------- | ------------------------------------------------------------------------------
 `undst`        |   `(gimp-image-undo-group-start image)`
 `flu`          |   `(gimp-displays-flush)`
 `thaw`         |   `(gimp-image-thaw-layers image)`
 `getal`        |   `(gimp-image-get-active-layer image)`
 `itsn`         |   `(gimp-item-set-name item name)`
 `gau`          |   `(plug-in-gauss run-mode image drawable horizontal vertical method)`
 `cub`          |   `(plug-in-cubism run-mode image drawable tile-size tile-saturation bg-color)`
 `cndraw`       |   `SF-DRAWABLE`
 `cnra`         |   `RGBA-IMAGE`
 `cnt`          |   `TRUE`
 `cnno`         |   `RUN-NONINTERACTIVE`


###Installation

Download the package: https://github.com/civAnimal/gimp-autocomplete-scheme-api/archive/master.zip
After extraction, copy`gimp-autocomplete-scheme-api`folder to Sublime Text's installed packages folder. You can locate this folder from Sublime Text by using the menu command: _Preferences_ → _Browse Packages_.


###Notes

The data is based upon GIMP 2.10.20.01.
This package has been shared in good faith. It is a _gift_ to my fellow Scheme programmers who are bravely exploring the wonderful world of GIMP. I hope it will make their coding-experience a bit more pleasant.
Happy car-ing.

Copyright © 2020 civAnimal ... civanimal@gmail.com ...`civAnimal Twitter`
