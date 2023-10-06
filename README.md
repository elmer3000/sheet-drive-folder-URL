# sheet-drive-folder-URL
This GAS runs from a Sheet, constructs the name of a Drive folder that has been created (in my case from a Jotform integration), grabs the URL of the folder and adds it to the last column of the row. It is trigged on Sheet EDIT.

Run the onSheetChange function manually once in order to set the Drive permissions.

Ensure that:
1. the sheet name corresponds to your Sheet tab name (line 24)
2. the creation of the Drive folder name is drawing from the correct columns (lines 34-36)
3. the amount of time you want the script to wait is correct (I've set it to wait for 1.5 minutes)
