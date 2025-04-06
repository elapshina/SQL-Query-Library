# 30 Essential Git Commands


1. **Set user name and email**
   - `git config --global user.name "Your Name"` — Set the username for commits.
   - `git config --global user.email "your.email@example.com"` — Set the email for commits.

2. **Cache credentials**
   - `git config --global credential.helper cache` — Enable credential caching to avoid entering the password with each commit.

3. **Initialize a repository**
   - `git init` — Create a new empty Git repository in the current directory.

4. **Clone a repository**
   - `git clone <repository_url>` — Clone an existing remote repository to your local machine.

5. **Add files to the staging area**
   - `git add <filename>` — Add a specific file to the staging area.
   - `git add .` — Add all changes in the current directory to the staging area.

6. **Check repository status**
   - `git status` — Show the current status of the repository, including modified, added, or deleted files.

7. **Create a commit with a message**
   - `git commit -m "Commit message"` — Create a commit with the specified message.

8. **View commit history**
   - `git log` — View the full commit history.
   - `git log --oneline` — View a brief commit history in one line.

9. **View changes before committing**
   - `git diff` — Show the differences between the current changes and the last commit.

10. **Remove tracked files from the working directory**
   - `git rm <filename>` — Remove a file from the working directory and the index.

11. **Rename files**
    - `git mv <old_name> <new_name>` — Rename a file in the repository.

12. **Discard changes in files**
    - `git checkout -- <filename>` — Discard changes in a file, reverting it to the state of the last commit.

13. **Amend the last commit**
    - `git commit --amend` — Modify the last commit (e.g., for fixing the commit message).

14. **Undo the last commit**
    - `git reset --hard HEAD~1` — Remove the last commit and all associated changes.

15. **Reset to a specific commit**
    - `git reset --hard <commit_hash>` — Reset the repository to a specific commit.

16. **Create a new branch and switch to it**
    - `git checkout -b <branch_name>` — Create a new branch and switch to it.

17. **View a list of branches**
    - `git branch` — Show a list of all local branches.

18. **Delete a branch**
    - `git branch -d <branch_name>` — Delete a specified local branch.

19. **Merge branches**
    - `git merge <branch_name>` — Merge the specified branch into the current branch.

20. **View commit history in a graph**
    - `git log --graph --oneline --all` — View the commit history in a graphical format.

21. **Abort a merge in case of conflicts**
    - `git merge --abort` — Abort the merge process in case of conflicts.

22. **Add a remote repository**
    - `git remote add origin <url>` — Add a remote repository with the given URL.

23. **View remote repositories**
    - `git remote -v` — Show the list of remote repositories.

24. **View detailed information about a remote repository**
    - `git remote show origin` — Display detailed information about the remote repository.

25. **Push changes to a remote repository**
    - `git push origin <branch_name>` — Push changes from the current branch to the remote repository.

26. **Pull changes from a remote repository**
    - `git pull origin <branch_name>` — Fetch and merge changes from the remote repository.

27. **Fetch changes from a remote repository**
    - `git fetch origin` — Fetch changes from a remote repository without merging.

28. **Push a new branch to a remote repository**
    - `git push origin <branch_name>` — Push a new branch to a remote repository.

29. **Delete a remote branch**
    - `git push origin --delete <branch_name>` — Delete a branch from the remote repository.

30. **Rebase a branch**
    - `git rebase <branch_name>` — Rebase the current branch onto the specified branch.
