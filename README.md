#

#Demo App
##Learn GitHub
####by Mitch Hogue

# <a href='http://pluralsight.com'><img src='https://gillcleerenpluralsight.blob.core.windows.net/files/pluralsight.png' height='60' alt='Pluralsight Logo' /></a> Starter Course on GitHub

###The basics of README.md syntax
-1
-2
-3
-...

### Open Git Bash

### Command to setup username: git config --global user.name "Mitch Hogue"

### Setup email: git config --global user.email "mitch.hogue@radianttech.net"

### See global settings in .gitconfig: git config --edit --global

### Configure a system properties/Advanced/Environment Variables/double click "path variable"...

    	####...browse, then select notepadd++ main folder.
    	####...now Notepad++ will open by using the command: notepad++
    	###Configure editor: git config core.editor "notepad++ -multiInst -nosession"
    	###$ git
    	###$ git config (configure tooling)
    	###$ git init (create/initialize a git local repo)
    	###$ git clone (clone a repository into local directory... download from remote)
    	###$ git add (prepare a file -to staging)
    	###$ git commit (commit a file to the repo)

    	###$ ls -la (see all files in directory)
    	###$ git status (tells you if you are master branch, commits, staged, etc...)
    	###$ code (opens VS code, default editor)
    	###$ code ____ (code + file name opens new file in VS code)
    	###$ code README.md (creates a readme file)
    	###...then save in there
    	###...Back in Git Bash...
    	###$ git add README.md (or name of new file) (stages file)(to remove use git rm --cached<file>)
    	###$ git add . (add all new files to staging area)
    	###$ git commit -m "Initial Commit"
    ###$ git push origin master (send from local to GitHub)
