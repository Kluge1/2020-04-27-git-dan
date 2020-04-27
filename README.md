#2020-04-27

SETUP
git config --global user.name "USERNAME" to set global username
git config --global user.email "USER_EMAIL" to set global email address
	-these (or perhaps just USERNAME) must match Github info in order
		for any contributions from you to be credited to that
		Github repository. Maybe start a professional account?
git config --global core.editor "nano -w" --to change from VI default

USAGE
git init: create a git repository in the current directory
	-Should only do this once in a repository
	-can't create a repository of a (no nested git repos) subdirectory; 
		must use "modulesto do that?
git status: tells you what is going on
git add "FILE" : adds a file or file version to staging area from where
	it can be committed
git commit : commits file(s) in staging to the repository with a message
git commit -m "COMMIT MESSAGE"
	-allows addition of simple commit message w/o using editor
git log : look at the commit history
git log --oneline : simple one line log view
git diff : look at differences between current state and what git knows
git remote: a place where git repo is stored
git remote add origin <URL> : add a remote
git push origin master : to push the master branch on local computer to 
	the remote repo

