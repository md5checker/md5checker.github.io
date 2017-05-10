---
layout: page
title: What's New
---
**Version 3.3**

* New: Check new md5 items only option
* New: Check new files in Md5Checker Shell context menu item
* New: Be able to recognize and skip comments in an MD5 file
* New: Displays last opened folder/last opened/saved MD5 file in the title bar
* New: Save Options dialog
* New: Save | Md5 item delimiter options
* New: Save | Line feed options
* New: Save | Path delimiter options
* New: Save | Save To | Always save full path option
* New: Hand cursor for Hyper Link control
* Improve: New wildcards matching algorithm - Adding large folder is about three times faster  
  Please update *.* to * if you have such settings of previous versions. *.* only matches files which name contains dot explicitly, i.e., has extension name.
* Improve: Be able to read MD5 files in various formats, including leading spaces, various comment delimiters, leading zeros omitted from MD5 checksums and various md5 item delimiters
* Fix: Count of checked items in the status bar is incorrect if there are md5 items in the Loaded category
* Fix: Progress bar should be reset to 0 when shows up
* Update: Load all MD5 files by default while adding folders  
  If you do not want to check those loaded md5 items, use the Check new md5 items only option when add folders.
* Update: Default values of Add | Add folders | Include option
* Update: Start, Stop and Locate toolbar button icon
* Update: Default window size
* Minor changes

*Version 3.2.4*

* Fix: Accelerators (hot keys) may cause exception if no md5 item is focused in the list view.

*Version 3.2.3*

* New: Check for Updates command.
* Fix: Compare MD5 dialog should recognize lower case characters.
* Fix: Combo boxes should not be fix width.
* Update: Separate Unknown category into Unknown &amp; Loaded.
* Update: Add *.zip &amp; *.rar by default.

*Version 3.2.2*

* New: Compare MD5 dialog allows to compare one file's MD5 checksum with another, automatically.

*Version 3.2.1*

* New: 'Save Each' command allows to create one MD5 file for each checked file when save.
* Improve: 'Store last folder used' option
* Fix: Three minor UI bugs

*Version 3.2*

* New: 'Code page' option
* New: 'Add to Send To menu' option
* Improve: Add files in background
* Fix: Load MD5 checksum of file from MD5 file will clear its calculated MD5 checksum
* Fix: No new line character is written when save md5 item if its path contains characters that system code page cannot recognize
* Fix: Could not discard saved MD5 checksum of md5 item if its path is a folder
* Fix: Height of dropdown list is too narrow in the Win9x version
* Update: 'Folder context menu' option -&gt; 'Add to Shell context menu', work for both folders and files
* Update: 'Checking in low priority' option -&gt; 'Work in low priority', work for both adding and checking
* Update: Removed Adding File dialog. (Use Stop button to stop adding)
* Update: Removed Unicode features from the Win9x version (Not supported)

*Version 3.1.1*

* New: 'Add Options' dialog for files only
* Improved: Use Combo box instead of Edit box for the Include option
* Improved: Reuse the 'Save settings' check box which has been replaced in version 3.1
* Fixed: When hold the Shift key down to bring the 'Add Options' dialog out, Md5Checker would not become the foreground window

*Version 3.1*

* New: 'Add Options' dialog for command line and drag-and-drop file adding (Default is hidden, hold the Shift key down to show)
* New: 'Folder context menu' option
* New: 'Hide dialogs' option
* New: Self-check command
* Improved: Use Save and Default buttons instead of 'Save settings' check box in the 'Add Options' dialog
* Improved: Added Homepage and Download links in the About dialog
* Fixed: Md5Checker may crash when adding files/folders via command line
* Updated: URL of the online help
* Updated: 'Checking in low priority' option is off by default
* Minor improvements and fixes

*Version 3.0.1*

* Fixed bug: Md5Checker may crash when dragging and dropping lots of files into it at one time

*Version 3.0*

* Re-implemented the core - faster, and take less CPU and memory usage
* Simplified the operational flow, more intuitive
* Removed unnecessary prompts
* Can remove saved items from .md5 files
* Provided an adding files progress dialog, can abort adding at any time
* Enhanced Open File dialog allows you to add folder and change adding settings
* Display count of md5 items for each category in the View toolbar
* 'Checking in low priority' option
* New UI mechanism - no delay when process large numbers of items
* New threading algorithm - faster
* Support both Multibyte character sets (MBCS) and Unicode well
* Provided for Win9x versions
* Provided versions in other languages

*Version 2.4*

* New Save Per Folders feature - Save files to multiple .md5 files per folders without prompt for file names. The Saving | Preferred file name options will be used.  
  Save command: Only create one .md5 file in a "root" folder, use this .md5 file to check all files at one time; Save Per Folders command: Create multiple .md5 files, one .md5 file per folder, which only includes the files within this folder, use these .md5 files to check files as needed.
* New Use Save Per Folders button in toolbar option - Use Save Per Folders button instead of Save button in toolbar if you are accustomed to non-prompt per-folders saving. It displays as Save'.
* New Create shortcut to the Programs menu option - Md5Checker now has capability to add a shortcut to/remove it from the Programs menu for convenient access.
* New user interface - New options and toolbar have been implemented.
* Other enhancements and bug fixes

*Version 2.3*

* New multithreading algorithm - Faster, smoother and more stable.
* New New files options - Choose to pass, discard or prompt for New files upon saving.
* New Hide old MD5s in the All view option - Be able to hide Not Available and Unknown files' annoying (old) MD5s in All view.
* New user interface - New prompts and text have been implemented.
* New Help - A brand new help has been implemented.
* Other enhancements and bug fixes

*Version 2.2*

* New Smart location feature - Md5Checker will browse from a "smart" path in all Open File, Save File and Browse for Folder dialog boxes instead of from 'My Desktop' every time.
* New Preferred file name options - Choose which type of preferred file name will be provided when saving.
* New user interface - New icons, text, menus, toolbars, dialog boxes and etc. have been implemented.
* Merged Old into Unknown state
* Separated Update command to Refresh and Pass commands
* Other enhancements and bug fixes

*Version 2.1.1*

* New Preferred file name feature - When saving, Md5Checker will provide a preferred file name rather than 'Untitled'. You can use it directly or specify another one then.
* Other enhancements

*Version 2.1*

* New Move command - Be able to re-specify selected files' paths.
* Added Help
* Few bug fixes

