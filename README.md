# labmid.github
Open git bash on your PC:

For initialization:
command: git init

After initialzation:
commands:touch ReadMe.md
	 git add README.md
	 git commit -m"Initial commit"

Once committed, then create branches
For creating branches in git:
command: git branch <branch name>
For creating two branches:
git branch feature-1
git branch feature-2

For switching branches:
git checkout feature-1
or
git checkout feature-2

For verifying if the branches are created:
command: git branch

Now create and modify files into each feature by normall checking out into specific brnch and addding the files

For merging the branches 
1. Switch to the Main Branch:
Get on the branch you want to merge into:
git checkout feature-1
2. Merge the Feature Branch:
o Merge the feature-2 branch into the feature-1 branch:
git merge feature-2

