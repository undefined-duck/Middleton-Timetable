# Middleton-Timetable
## Info
A timetable program for Middleton built using the [Godot](https://godotengine.org/) game engine.\
A [legacy version](https://github.com/undefined-duck/Middleton-Timetable/releases/tag/Release5) is available which made using python and with the tkinter graphics library.\
Below is information purely about the Godot version of the program.

## Download
To download the latest Godot version go to the [releases page](https://github.com/undefined-duck/Middleton-Timetable/releases/latest) and download the portable or installer versions.

## Links to sections
- [Importing from Kamar](#importing-from-kamar)
- [Saving and loading timetables](#saving-and-loading-timetables)

## Importing from [Kamar](https://middleton.school.kiwi/)
Timetables are created by importing a valid `.ics` file either through downloading and manually importing or inserting the URL to the file from [Kamar](https://middleton.school.kiwi/).
> This can be found within in the Save/Load menu.

The preferred way of importing `.ics` files is through using the URL method.\
The process to do this is as follows:
1. The URL to the `.ics` file can be found in the attendance page on [Kamar](https://middleton.school.kiwi/).
2. Copy the link from the bottom of the attendance page which says: *"Enter this URL into iCal, Google Calendar, Outlook:"*
3. Paste the URL into the Save/Load menu under the section which says: *"Import timetable from Kamar:"*
4. Click download and the timetable should be automatically imported.

## Saving and loading timetables
- The saving and loading of timetables can be done within the file menu.
- The file extension for middleton timetable files is `.mtt`.
- The default save location in found in `%appdata%\middleton_timetable`
- The timetable automatically saves the currently loaded timetable to `autosave.mtt` after every action.
