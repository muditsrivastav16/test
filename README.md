# test
test repo
This is the first assignment.

Step 1. Create new Repository
Step 2. Clone Repository
	  Copy repository link from github
	  Run command on GIT Bash : git clone [paste copied link]
Step 3. Add new file in local system in same directory.
	  Run Command : git add <file name>
	  (Staging Area)
Step 4. Commit
	  git commit -m 'message'
	  (local machine)
Step 5. Push
	  git push

some more command : git log, git status

git difftool HEAD : to compare file in staging area with the file on the github.

To undoing the file before adding on git (i.e git add <file name> not executed) :-
	$ git checkout -- <file name>
	$ git checkout -- . [undo all files]

To undoing the file after add and commit on git :-
	$ git revert <commit id or HEAD>

To undoing the changes :-
	$ git reset --hard <commit id>