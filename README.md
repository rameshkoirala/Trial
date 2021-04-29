https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners#:~:text=%20An%20Intro%20to%20Git%20and%20GitHub%20for,environment%0AAdd%20a%20file%20to%20the%20staging...%20More%20
GitHub commands:
1. $ mkdir Trial
2. $ cd Trial
3. git init               # to initialize git on Trial directory.
4. git status             # check status of git. To see anything has been modified or not.
Create a file: emacs -nw jpt.py
5. git add jpt.py         # to set up a stage so that you can commit.
6. git commit -m "trial commit"
7. git checkout -b first_branch
8. git branch             # shows you that you are active on first_branch, not anymore in master.
9. Create <name of repo> in GitHub website. Example repo for this excersise is called Trial. 
10. git remote add origin https://github.com/rameshkoirala/Trial.git  # Connect his project to the Trial repository.
11. git branch -M first_branch
12. git push -u origin first_branch     # Finally pushed first_brach of this project to Trial repository.
		Username for 'https://github.com': rameshkoirala
		Password for 'https://rameshkoirala@github.com': 
		Enumerating objects: 3, done.
		Counting objects: 100% (3/3), done.
		Writing objects: 100% (3/3), 254 bytes | 254.00 KiB/s, done.
		Total 3 (delta 0), reused 0 (delta 0)
		To https://github.com/rameshkoirala/Trial.git
		 * [new branch]      first_branch -> first_branch
		Branch 'first_branch' set up to track remote branch 'first_branch' from 'origin'.
Just for fun create a second branch of this project.
13. git checkout -b second_branch
15. git add jpt.py       # this is required to set up a stage so that you can commit.
16. git commit -m "Info added to the script."
17. git push -u origin second_branch     # send it to the repository so that other people online can see it.
