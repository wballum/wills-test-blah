Learning how to use git and github
==================================

Reference
=========
- How to create your first repository and upload it to Github
	https://www.youtube.com/watch?v=mMsWq3rS6Po
- Learn Git in 20 Minutes
	https://www.youtube.com/watch?v=Y9XZQO1n_7c
- configure the default text editor 
	https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup
	git config --global core.editor vim.tiny

- git clone url ()
	git clone https://github.com/wballum/dynamic-calendar.git
	
- Why is Git always asking for my password?
	https://help.github.com/articles/why-is-git-always-asking-for-my-password/
	
	Caching your GitHub password in Git
	https://help.github.com/articles/caching-your-github-password-in-git/#platform-linux
	git config --global credential.helper cache
	git config --global credential.helper 'cache --timeout=3600'

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
