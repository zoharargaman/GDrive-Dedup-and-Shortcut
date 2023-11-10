# GDrive-Dedup-and-Shortcut
Google Drive Delete Duplicate files and create shortcut so all locations will have a link to the file
# Install
Create an empty Spreadshhet with 2 sheets names: Done, Drive
create App Script and copy code to Code.gs
# Run
run function listFilesBySize() - this will show all files sorted by size
and then run readSheetandGo() - this will iterate the files from largest, search for duplicates, and move to trash and create a shortcut.

# IMPORTANT
this script does not delete any file, it only moves it to the bin so you can find the dup files at the GDrive Bin
