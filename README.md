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
	-can't create a repository of a subdirectory; must use "modules
		to do that?
git status: tells you what is going on
git add "FILE" : adds a file or file version to staging area from where
	it can be committed
git commit : commits file(s) in staging to the repository
git commit -m "COMMIT MESSAGE"
	-allows addition of simple commit message w/o using editor

