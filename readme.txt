
Clipboard CLI Logger - CBCL
-------------------------------

	Application to log all the text that the clipboard is updated to.
	These are actions made by the user in the UI such as copy via Ctrl+C or
	copy in mouse context menus.
	Non-interactive, CLI interface configuration.
	It is a CLI utility that is meant to be run in its own terminal|console window.
	CB text is written to STDOUT or text file.


Options
------------

	-bSkipDupes 1

		If set to 1, doesn't logs duplicates.

	-ofn FILENAME

		Sets file name to write the logs to.

	-nLogLevel NUM

		If set to 0, shows fewer messages in STDERR.
		Use 8 to show most messages - the default.

	-anPrefix TEXT
	-anSuffix TEXT

		Sets optional prefix and suffix to include in the output.

	-bForceSingleLine NUM

		Optional. Sets how to replace new-line characters in the output.
		NUM can be set to the value: 1-4.

	-nMaxCaptures NUM

		Perform this many NUM of captures then exit.

