# Quiet
## Summary
Command line tool to silently launch a process.

## Warranty
See [Warranty](http://www.joeware.net/freetools/warranty.htm)

## Platforms
* Windows NT
* Windows 2000
* Windows Server 2003
* Windows XP

## Current Version
Version 1.01.00 - April 27, 2002

## Modification(s) from previous version
* Added ability to specify params

## Security Requirements
None.

## Language
C++. Compiled with Borland Builder 6.0

## Source Code Availability
None

## Story
This tool is a real quick and dirty program that I whipped up in about 5 minutes (took longer to set compiler options than write the code) which uses ShellExecuteEx to spawn a "detached" process. It is actually just a hidden process that doesn't appear on the task bar but it does appear in task manager or anything that enumerates processes. I wrote it because of a post in microsoft.public.win2000.cmdprompt.admin. Simply specify quiet "command" and it will run whatever it is hidden. If the program doesn't exist it will pop a dialog box which is annoying but if the program is in the path somewhere it will execute it. Please note that logging off will kill the process as it may be hidden from the user but it isn't hidden from the system.

## Download
[Download Now]()