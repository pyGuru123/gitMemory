	git config remote.origin.url https://{USERNAME}:{PASSWORD}@github.com/{USERNAME}/{REPONAME}.git
	git config --global credential.helper wincred


# Basic commands

## Create a new repo
	git init
	git remote add origin repo_url
	git clone repo_url

## Check git files status
	git status

## Tracking files
	git add .
	git commit -m "comment"

## Push to github
	git push
	git push -u origin master

...

# Contribute to other people repo

## cloning repo
	fork the repo
	git clone repo_url
	git remote -v
	git remote add upstream url
	git pull upstream main

	git add.
	git commit -m "added new file"
	git push

	make a pull request