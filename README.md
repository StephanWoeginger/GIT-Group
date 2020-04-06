# GIT-Group 
Group Exercise GIT 
For this exercise you do not have to provide screenshots as the result will be pushed on github and therefore can be reviewed directly. Each of you will execute the tasks on your local computer and push it to github when mentioned. Some tasks such as merging pull requests will be done on the github web site. 
This exercise will show you how to collaborate working on the same files using a version control system. For each commit please provide a reasonable commit message. 
What you will do: 
•	Create your repository on github 
•	Invite the others to join the repository 
•	Create some branches and commit files 
•	Publish these changes on the repository on github and merge them back to master. 
How to 
1.	Create a public git repository on github as shown in the LVA. 
a.	Init this repository with a README.md 
b.	Also include the MIT License file. 
c.	Include a default .gitignore file for Java 
d.	See https://github.com/renes/fh-test-repo for reference 
e.	Grant all team members full access to the repository. Go to e.g. https://github.com/renes/fh-test-repo/settings/access. Please adapt the URL with the username who created the repo and your repository name. 
f.	Also grant me, (User: renes – schakmann.rene@gmail.com) full access. 
2.	Each team member, clone this git repository to your computer 
a. Check point: 
  
3.	Each team member creates a branch name {your first name – some random number} e.g. 
rene-3434 
a.	Each team member push this branch to github 
b.	Use e.g. git push --set-upstream origin rene-3434 to push as its your first time, later git push origin is enough 
c.	Check point:
  
4.	Each team member creates a readme-{your first name}.md file and include some content a. Commit this file 
b.	Push the change to github 
c.	Check point:
  
5.	Three of your team:  
a.	Create a Pull Request for your branch to master 
b.	Checkpoint:
  
c.	Someone else of your team should accept and merge two of the pull request to master 
d.	Reject the other 6. One of the other two: 
a.	Edit the README.md on your branch. Add 10 lines. 
b.	Push your change to github 7. The remaining one: 
a.	Edit the README.md on the master. Add 5 lines that are different from the lines above. 
b.	Push your change to github 
8.	Merge the branch from 6 to master with a pull request. Resolve the merge conflict if there is one. 
9.	Checkpoint, at this point you should have: 
a.	Six branches (five you created plus master), you can check it at https://github.com/{name}/{your-repo}/branches 
b.	Three merged to master, therefore your files should be visible in the master branch 
10.	One of your team 
a.	Switch to master 
b.	Adapt the .gitignore to exclude all future *.txt files 
c.	Push your change to github 
11.	Each team member, switch to master branch 
a.	Edit README.md, add some text 
b.	Pull the latest changes from master (git pull) 
c.	Do whatever necessary to commit your changes 
d.	Push your changes to github 
12.	Congratulation, you are done. 
