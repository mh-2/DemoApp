Demo App!!!

HTML CSS GIT GITHUB

Learn GitHub
by Mitch Hogue

<a href='http://pluralsight.com'><img src='https://gillcleerenpluralsight.blob.core.windows.net/files/pluralsight.png' height='60' alt='Pluralsight Logo'/></a> Starter Course on GitHub



Configure system properties/advanced/environment variables

        ...double click "path variable"...
        
        ...browse, then select notepadd++ main folder.
        
        $ git notepad++ ($ git code)
        
        $ git config core.editor "notepad++ -multiInst -nosession"
        


Open Git Bash
COMMANDS

        $ git config --global user.name "Mitch Hogue" (setup username)

        $ git config --global user.email "mitch.hogue@radianttech.net" (setup email)

        $ git config --edit --global (see global settings in .gitconfig)

    	$ git config (configure tooling)
    	$ git init (initialize a git local repo)
    	$ git clone (clone a repository into local directory... download from remote)
    	$ git add (prepare a file -to staging)
    	$ git commit -m "comment"(commit a file to the repo)
        
    If moving a new local repository to GitHub for the first time...
    
        $ git remote add origin remote repository URL# Sets the new remote
        $ git remote -v
        # Verifies the new remote URL
        
    Then push the changes...
    
        $ git push origin master
        # Pushes the changes in your local repository up to the remote repository you specified as the origin

    	$ ls -la (see all files in directory)
    	$ git status (tells you if you are master branch, commits, staged, etc...)
    	$ code (opens VS code, use code fileName.ex to open specific file in Code)
    	$ code README.md (creates a readme file)

    	$ git add README.md (or name of new file) (stages file)(to remove use git rm --cached<file>)
    	$ git add . (add all new files to staging area)
    	$ git commit -m "Initial Commit"
    	$ git push origin master (send from local to GitHub)

    If error (bc of changes on remote)...

    	$ git fetch (peaks at GitHub to see if anything new has been added)
    		Not destructive, just downloaded changes from remote into local.
    	$ git merge...
    	$ git push origin master


    	OR

    	$ git pull (performs a fetch and a merge, from GitHub/remote to local.)
    		CAUTION!!!
    	$ git push origin master
        
COMMANDS for Branching...
        
        $ git status (see if master or which branch)
        $ git checkout -b "new branch name" (creates new branch and enters locally)
        $ code "new file name.exe"
        $ git push -u origin branch-name
        $ git push -u [origin] [branch]
        $ git branch [branch-name] (create a branch)
        $ git checkout [branch-name] (change branches)
        
