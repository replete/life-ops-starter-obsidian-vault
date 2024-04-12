# Replete's life ops starter vault

This is your new *life ops starter vault*.
https://github.com/replete/life-ops-starter-obsidian-vault

## Installation

1) Install obsidian.md from https://obsidian.md
2) 'Open folder as vault' in Obsidian, and then choose this folder

## Folders

- Assets
	- Templates live here. This folder serves purpose of hiding non-content files related to the vault.
- Daily
	- Your daily notes live here 
	- Each daily note has a filename of the format YYYY-MM-DD
	- To make or open today's note either; tap ALT+D, click a date on the right calendar, open the command palette (CMD+P) and start typing daily note
	- View the [[Daily Note]] template in source view (ALT+TAB on mac) to see how the template works, and edit as desired for your daily note
	- Bonus:
		- Under the 'Day planner' heading, adding a list item that starts with a time like `- 14:00 - 18:00` will show up in the right Day Planner plugin panel, useful for time-blocking. Also you can subscribe to public .ics calendar entries for scheduled things and see them inline.
- Journal
	- Your journal entries
	- Each journal entry has a filename of the format YYYY-MM-DD
	- To make a new journal entry either; tap ALT+J, or tap ALT+Q and select Journal
- Meditations
	- This folder could contain daily devotionals broken up by day in format of MMDD.md, or collections that could be included randomly in your daily note, included via templater syntax within the relevant template
- Notes
	- The idea here is atomic notes. Think of them as Fleeting Notes ('Zettelkasten' terminology). Whenever I want to note anything, I make a fleeting note using QuickAdd (ALT+Q) or set up a direct hotkey (settings > hotkeys)
- Reference
	- Reference notes are different to fleeting notes in that they would hold notes you might take for literary material, or a youtube video.

## Hotkeys (Mac)
 
 `ALT + TAB`– Toggles source view for the open file. Useful when working on templates.
 `ALT + D` – Creates or opens a daily note for today
 `ALT + Q` – Opens 'QuickAdd' - where you can create a new Journal Entry, Note, Reference note, Daily Note

## Enabled plugins

- Advanced URI 
	- This isn't used in this vault, but is useful for deeply integrating with your OS. For instance, you could:
		- open the command palette (CMD+P) type 'advanced uri: copy URI for command'
		- select 'Don't specify a file'
		- type 'Daily note' and select 'Periodic Notes: Open daily note'
		- a URI like `obsidian://advanced-uri?vault=replete-obsidian-vault&commandid=periodic-notes%253Aopen-daily-note` will be copied to the clipboard
		- You could use this URI with an app like 'BetterTouchTool' to bind this URI to a keypress on your keyboard, and automatically switch to obsidian and open your daily note - even if obsidian isn't already open or focused
- Calendar
	- This calendar plugin displays in the bottom right and works with periodic notes to create daily notes on click
- Commander
	- Allows us to add commands as icons in places like the header and status bar (delete button in note view for instance
- DataView
	- This plugin is often a dependency of many others because it allows you to query your markdown notes like a database with JS or SQL-like queries. I think Periodic notes requires this...
- Day Planner
	- This plugin is super cool. It's the panel to the right showing a day calendar. This lets you time block your day(s) and display your progress. Just add list-items under `Day planner` heading in your daily note and they will show for whatever daily note you are looking at. You can plugin in .ics calendars too so you can see whats happening for that day.
- Excalidraw
	- This is another gem of obsidian, a great mindmap/drawing tool that you can use for conceptualizing and scribbling. It lets you embed notes (without including them) allowing for amazing visual note-taking
- Iconize
	- This plugin lets you assign icons to folders and files in the file explorer
- Minimal Theme settings
	- 'Minimal Theme' is the best non-default theme for obsidian made by the CEO of Obsidian. It has lots of cool features, including multiple colour schemes - some you will recognize as classic text editor colour themes like 'solarized'. You can pick a dark or light theme through the command palette. 
- MySnippets
	- This plugin allows you to toggle CSS snippets for obsidian (which can affect UI, editor, plugins etc) through an icon in the bottom right of the status bar.  I have used this capability to load CSS Snippets to deliver a suite of Obsidian customizations to provide the experience I want from a life ops application. 
		- I released [a repo of CSS snippets](https://github.com/replete/obsidian-minimal-theme-css-snippets) based on Minimal Theme, and these snippets are included with this vault. Click the bottom right statusbar icon to see whats enabled already.
		- The CSS snippets that are currently enabled improve obsidian UI behaviour and provide some better styles for the editor and daily note template
- QuickAdd
	- This essential plugin lets us make notes in certain folders using templates and assign hotkeys to them
- OmniSearch
	- This is a search plugin that is basically an enhanced 'quick switcher' plugin that can also be enabled to search within PDFs. I've reconfigured the hotkey to 'CMD+O' to replace the quick switcher.
- Periodic Notes
	- This does the daily note 
-  Templater
	- is the plugin we use for templating. This one allows us to use JS in our templates to do more fancy things than the built-in one is capable of. If you poke around the templates and view source (ALT+TAB on Mac) you'll get a feel for how it works.