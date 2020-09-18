# Readme for X13-Backplane

Whenever you make a new part, download the datasheet and save it here _**and**_ with the part in the parts library

Always pull other people's changes before beginning to work
`git pull`

Be sure to push your changes after  working on them. Run:
1. `git add .` to add any files in this directory or a subdirectory
or `git add -u` to add any modified files
2. (Optional) `git clean -nX` to see what ignored files can be removed
	`git clean -fX` removes ignored files (Eagle backups)
3. `git commit -m "helpful commit message"` with a description of the work that you did
4. `git push` to push your work to github

Other helpful commands
* `git status` says information about modified and staged files
* `git log` shows the recent commits of the repository
* `git log filename.extension` show the recent commits for just that file
* `git checkout first-couple-letter-of-commit-id` lets you go back to a previous version
* `git checkout master` brings you back to the latest commit
* `git tag` lists the tags
* `git tag -a orderX -m "the version of the board placed for the X'th order"` tag a specific commit
* `git push --tags` needed to push tags to remote
* `git show orderX` show the commit log for the given tag
* `git checkout orderX` go back and interact with the files at the tagged commit
