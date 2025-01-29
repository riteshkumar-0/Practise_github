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


git remote set-url origin https://github.com/riteshkumar-0/Practise_github.git