VI Snippets
	Programmatically import/export VI Snippets PNG images.

Author: Ryan Pacini (c)2022

Instructions:
	1. Copy "VI Snippets.llb" to
		"<LabVIEW>\project\VI Snippets\VI Snippets.llb"
			Note: Make sure to copy the LLB to the "..\VI Snippets\" sub-directory.
	2. Restart LabVIEW
		Note: The library is embedded as a Tools menu option:
		Tools > VI Snippets >
			Browse... - Dialog to quickly import a VI Snippet PNG image
			Export... - Export the current VI as a VI Snippet PNG image
			Import... - Import a VI Snippet PNG image to a new VI

Usage:
	Export
		From a VI select "Tools > VI Snippets > Export..." to export the VI as a VI Snippet
	Import
		Select "Tools > VI Snippets > Import...", navigate to a VI Snippet PNG file and select "Import"
	Browse
		VI Snippets are saved to "C:\ProgramData\VI Snippets" by default, select "Tools > VI Snippets > Browse..." to open the pop-up dialog to browse the exported VI Snippets.
			Select "Copy to new VI" to create a new VI (including VI properties, icon, etc.)
			Select "Copy to clipboard" to copy the diagram content and paste into an existing VI.
			
Details:
	VI Snippets are PNG images with the VI embedded in a PNG chunk. This library loads and imports the VI PNG chuck through VI Scripting to manipulate VI Snippets programmatically.

