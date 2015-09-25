Learing how to use git
======================

Ref
https://www.youtube.com/watch?v=mMsWq3rS6Po
https://www.youtube.com/watch?v=Y9XZQO1n_7c


Working from local to remote
============================
- Make sure you are using the most current version
get pull
get pull origin

- Edit files
vim test.bash

- See the status of the git repository
git status

- Add the modified files
git add .

- See the status of the git repository
git status

- commit the changed files to the local git repository
git commit

- See the status of the git repository
git status

- upload to remote git repository
git push origin


Working from remote then pulling to local
=========================================
- Edit files on github

- When within local folder for repository sync with
git pull origin

- Check urls
git remote -v
	john@debian:~/git-test/wills-test-blah$ git remote -v
	origin	https://github.com/wballum/wills-test-blah.git (fetch)
	origin	https://github.com/wballum/wills-test-blah.git (push)

