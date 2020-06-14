# Git Bash

## How to change Home Directory in Git Bash so when you open Git Bash it is in the folder you use for documents, etc - this might not be the default folder.

1. Find GitBash in the Start Menu. Right Click - More - Open in folder
2. Right click on GitBash shortcut file - Properties
Change Start in to the folder you want GitBash to start in
Remove --cd-to-home from the Target field. 
Close and reopen GitBash.

To check - echo $HOME will tell you what the home folder is. 
cd ~ will now navigate you to this folder
