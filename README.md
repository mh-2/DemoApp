Demo App!!!
Learn GitHub
by Mitch Hogue

<a href='http://pluralsight.com'><img src='https://gillcleerenpluralsight.blob.core.windows.net/files/pluralsight.png' height='60' alt='Pluralsight Logo'/></a> Starter Course on GitHub

###The basics of README.md syntax
-1
-2
-3

Open Git Bash
COMMANDS
Command to setup username: git config --global user.name "Mitch Hogue"
Setup email: git config --global user.email "mitch.hogue@radianttech.net"
See global settings in .gitconfig: git config --edit --global
Configure a system properties/Advanced/Environment Variables/double click "path variable"...
browse, then select notepadd++ main folder.
...now Notepad++ will open by using the command: notepad++
Configure editor: git config core.editor "notepad++ -multiInst -nosession"

    $ git config (configure tooling)
    	$ git init (initialize a git local repo)
    	$ git clone (clone a repository into local directory... download from remote)
    	$ git add (prepare a file -to staging)
    	$ git commit -m "comment"(commit a file to the repo)

    	$ ls -la (see all files in directory)
    	$ git status (tells you if you are master branch, commits, staged, etc...)
    	$ code (opens VS code, use code fileName.ex to open specific file in Code)
    	$ code README.md (creates a readme file)

    	$ git add README.md (or name of new file) (stages file)(to remove use git rm --cached<file>)
    	$ git add . (add all new files to staging area)
    	$ git commit -m "Initial Commit"
    	$ git push origin master (send from local to GitHub)
    		if error (bc of changes on remote)...

    	$ git fetch (peaks at GitHub to see if anything new has been added)
    		Not destructive, just downloaded changes from remote into local.
    	$ git merge...
    	$ git push origin master


OR

    	$ git pull (performs a fetch and a merge, from GitHub/remote to local.)
    		CAUTION!!!
    	$ git push origin master
