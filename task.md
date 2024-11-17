#### Task 1: Create a Local Git Repository

1. Create a new folder with mkdir

    mkdir MyProject

2. To navigate into this folder use cd

   cd MyProject

3. Initialize git into this folder

    git init 

4. When we enter git status output is "No commit yet"

    git status


#### Task 2: Clone a Remote Repository

1. To clone a remote repository

    git clone https://github.com/kiranchaudhary18/audi-india-Luxury-Cars-.git

2. To verify that the remote repository

    cd MyProject
    ls


#### Task 3: Commit Changes Locally

1. Create a new file and add some text into this file

    echo "Welcome to Git" > test.md

2. Add file to the stagging area 

    git add test.md

3. Add commit the staged file:  

    git commit -m "Initial commit"


#### Task 4: Write Effective Commit Messages

1. Create a commit message

    git commit "Add the detailed commit message

2. To commit multiple files with one message

    echo "" >> file1.txt 
    echo "" >> file2.txt

    git add .

    git commit -m "Two new file added"



#### Task 5: View Detailed Commit History

1. To view full commit history we use git log  

   git log

2. To view commit history in a compact format:  

   git log --oneline


#### Task 6: Customize Log Outputs

1. View logs with a graphical representation:  

   git log --oneline --graph --decorate

2. Filter logs for a specific file:  

   git log README.md
 

### Task 7: Understanding Branching 

1. To list all branches

    git branch

2. To create a new branch

    git branch new_branch

3. To switch to this branch

    git checkout new_branch

#### Task 8: Make Changes in a Branch

1. Add new file in the new branch

    echo "New file" >> new_file.txt

2. Add to stagging area and commit 

    git add new_file
    git commit -m "File added"


#### Task 9: Merging Branches

1. To merge branch first we switch into main branch

    git checkout main

2. Merge the new branch into main

    git merge new_branch


#### Task 10: Simulate a Merge Conflict

1. First make a new file in both the existing branches

