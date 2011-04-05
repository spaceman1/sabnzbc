SABnzbc
===============

SABnzbd+ queue manager

Launching from the command line
--------------------------------

If you're connecting to a server on the local machine you don't need to supply any options.
To connect to a remote machine use sabnzbc IP:PORT YOUR_API_KEY

Usage
-----

You can bring up the quick help dialog with the `h' command.

Item commands work on ranges of items. e.g. :
c 12-25 tv
m 12-25 0
Will change the category of items 12 through 25 to `tv' and move them to the top of the queue.
The space after the command character is optional.
You can also run a command on a single item (e.g. d 13 deletes item 13)

To Do and Known Issues
----------------------
* add queue Add... command
* make Textbox handle control characters
* history view + commands
* Remember which columns are visible between runs
* Allow column re-ordering
* Turn queue win into a pad so we can view large lists in small windows
* Allow window resizing
