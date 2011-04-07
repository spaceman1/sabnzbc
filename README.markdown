SABnzbc
===============

SABnzbd+ queue manager

Launching from the command line
--------------------------------

If you're connecting to a server on the local machine you don't need to supply any options.
To connect to a remote machine use sabnzbc IP:PORT YOUR-API-KEY

Usage
-----

You can bring up the quick help dialog with the `h` command.

Item commands work on ranges of items. e.g. :

	c 12-25 tv
	m 12-25 0

Will change the category of items 12 through 25 to tv and move them to the top of the queue.
The space after the command character is optional.
You can also run a command on a single item (e.g. `d 13` deletes item 13)

Command Arguments
----------------------

Delete, Pause, Resume, Shutdown, Quit, Toggle Help: none

Move: The index of the row the first item should move to.

Change Script: The name of the script to use in post-processing

Change Options: Skip: 0
+Repair: 1
+Repair/Unpack: 2
+Repair/Unpack/Delete: 3

Change Priority: Force/High/Normal/Low

Toggle Column: The abbreviation of the column to toggle. See the help window for abbreviations

To Do and Known Issues
----------------------
* Add a queue Add... command
* History commands
* Remember which columns are visible between runs
* Allow column re-ordering
* Turn queue win into a pad so we can view large lists in small windows
* Window echoes junk during a resize
* Restore prompt contents after resize
* Stop column headers and main headers from line wrapping
* Fix up colour scheme
* Pause for time interval
* Command history
