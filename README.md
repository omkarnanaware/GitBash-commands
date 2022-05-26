# Github-commands
Name : Omkar Rajendra Nanaware
Topic : Gitbash commands



Important Git commands:

1) echo "# CPP-Programming" >> README.md

initializing the Git repo in the local repository:
git init


Adding to the staging areas:
3) git add README.md


Commit the changes to push:
4) +git commit -m "first commit"


To change branch from master to main:
git branch -M main


5)git remote add origin https://github.com/<username>/<repositoryname>.git


To create the token :
1) goto profile (right side on main screen click on the dp)
2) Setting
3) Developer Setting
4) Generate the token 
5) use the token in generic link
	git remote set-url origin https://<githubtoken>@github.com/<username>/<repositoryname>.git

eg:
	git remote set-url origin https://ghp_0N6QEGI@github.com/omkarnanaware/C-Programming.git

Then push code to the repo:
git push -u origin main




Delete the repo:
	In Repo goto the setting of the Repo 
	open setting 
	in the bottom delete repository.
	
Delet repo from local:
	rm -fr .git
	
	
how to see hidden file:
	ls -a <path>






