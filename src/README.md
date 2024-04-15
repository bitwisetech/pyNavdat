pyNavdat

  A derivation of https://github.com/robertjkeller/PyARINC424 with modified record map

  This repo is an overlay for files from PyARINC424 database tool that creates a posegrsql database
from Flightgear's nav.dat, XP810 format  
  
Install PyARINC424 from:  https://github.com/robertjkeller/PyARINC424
  Modify PyARINC424/src/config.ini to taste and run PyARINC424/src/main.py
  to create ARINC424 database
  
Then copy PyARINC424 and subfolders to a new pyNavdat folder tree. Copy the files from this repo:
  config.ini and record_maps.py into pyNavdat/src, modify config.ini and run pyNavdat/src/main.py
  to create a new xp810 database.
