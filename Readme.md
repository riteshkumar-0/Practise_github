	•git branch will show you the current branches available locally.
	•git status will show you the current state of the working directory and staging area.

# If the main branch doesn't exist
git checkout -b main

# Or if it exists but you're not on it
git checkout main


# Add files to staging area
git add .

# Commit the files
git commit -m "Initial commit"

git push -u origin main

-u sets the upstream for your branch, which means in future pushes you can simply use git push.

Additional Check: Verify Remote URL
git remote -v
This command will display the remote repositories connected to your local repository.

to set the correct url
git remote set-url origin https://github.com/riteshkumar-0/Practise_github.git

 Basic Local Changes
 	•git status
    •git add [file Name]
    •git commit -m "[commit message]"

Branching

	•git branch:- Lists all local branches in the repository(show all branch).
    •git branch [branch-name]:- Creates a new branch.
     git checkout [branch-name]:- Switches to the specified branch and updates the working directory.
     git checkout -b [branch-name]:- Create a new branch and switch to newly created
    •git merge [branch]:-Merges the specified branch’s history into the current branch.
 
 After mergin we can Delete the branch 

 git branch -d branch-name(locally delete the branch i.e where you currently working )


git push origin --delete branch name(to delete the branch from remote i.e from github)