Batch-data-parse-csv-import
===========================

This script is used to parse multiple data files (with the same x column values, different y column values) into one csv file that can be easily imported into excel or graphpad. Originally developed for data created by SPCImage (http://www.becker-hickl.com/ | http://www.becker-hickl.com/software/tcspc/softwaretcspcspecial.htm), but will work for any .asc file (or anything with a few edits).

Latest version is 3.0

How to make this work
=====================

1. Copy in your data files (.asc) into a folder called 'data' (e.g. C://Work/FLIM/data). IMPORTANT: this data will be renamed and modified, so make sure the data is copied and not your only copy in case anything goes wrong... you have been warned!!!
2. Make sure that FLIMerge.pl and FLIMerge.sh are all in a folder a level up from 'data' (e.g. C://Work/FLIM/).
3. Open up the terminal and navigate to your working folder where the scripts are located
4. Run the script by entering 'bash FLIMerge.sh' in the terminal.
5. Your data will be in the output.csv file

Who to thank
============

This script was written by Dr Inge Seim... bug tested and GitHub'd by me. 

Send your Bitcoins to Inge at: 1Hvsw4SYYbofjbyZA4BxdYEM31Kta3y1vY
