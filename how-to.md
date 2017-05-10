---
layout: page
title: How To
---
**How to add files/open MD5 files?**

1. Use Add command (menu item or toolbar button)
1. Or drag-and-drop files/folders to main window
1. Or use paths as command line parameters to launch Md5Checker
1. Md5Checker can be integrated with the Shell, check out the Options &gt; Integration

**How to include only specific types of files while adding folders?**

1. In Options dialog, fill out the Add folders options
1. Or fill out these settings in the Open File dialog upon adding

**How to calculate MD5 hashes of files?**

1. Add files you want to calculate their MD5 hashes
1. Use Start command (menu item or toolbar button)
1. Waiting until all Unknown md5 items get checked

**How to understand states of md5 items?**

* Not available (N/A): Invalid file path, file is missing or inaccessible
* Unknown: Current MD5 hash of file has not been calculated
* New: File only has current MD5 hash
* Failed: Current MD5 hash of file is different than saved MD5 hash
* Passed: Current MD5 hash of file is equal to saved MD5 hash

**How to recheck N/A md5 items to see if they are available now?**

Just check files again, every N/A md5 item will be rechecked

**How to verify files?**

Add the .md5 file which includes all md5 items of files you want to verify, these md5 items will be loaded and verified

**How to save New md5 items?**

Just use Save/Save To command

**How to discard New md5 items?**

1. Just exit Md5Checker
1. Or remove them before saving

**How to update Failed md5 items?**

Just use Save/Save To command

**How to discard Failed md5 items?**

1. Just exist Md5Checker
1. Or remove them before saving

**How to remove saved md5 items from .md5 files?**

1. Load md5 items from existing .md5 files
1. Select md5 items you want to remove
1. Use Discarded command (menu item) to make them discarded
1. Save

Note: If you loaded md5 items from file A, discard them and save the result into file B, md5 items in file A will not be removed

**How to save md5 items per folders?**

Just use Save command

**How to save/create MD5 file for each file?**

Just use Save Each command

**How to save md5 items to one .md5 file?**

Just use Save To command

It is useful for: There are inaccessible target folders for Save command; Save MD5 hashes of files under multiple sub-folders into a parent folder, and you can check all of them by one double click next time

