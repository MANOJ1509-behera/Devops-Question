## Day - 1

```
1. Can you explain the Git branching model and how you would choose a branching strategy for a large project?

2. What happens when you merge two branches that have conflicting changes? How would you handle merge conflicts in a real project?

3. How do you use git rebase to ensure that your feature branch is up-to-date with the latest changes from the main branch?

4. Explain the difference between git pull and git fetch. When would you use one over the other in a multi-developer environment?

5. Imagine a scenario where you accidentally commit sensitive information, such as passwords or API keys, into a public repository. How would you fix that issue, and what steps would you take to prevent this in the future?

6. How do you manage large repositories with multiple teams working on different parts of the codebase, and how do you prevent conflicts between them?

7. What are Git submodules, and how would you use them to manage dependencies between multiple repositories in a large project?

8. If you need to squash multiple commits into one before merging a pull request, how would you do that? And why might you want to do this in a DevOps workflow?

9. What is the difference between git stash and git commit --amend? When would you use one over the other?

10. How would you set up Git to automatically trigger a build in a CI/CD pipeline every time a new commit is pushed to the repository?

```

## Day - 2

```

1. How do you revert a commit that has already been pushed to a shared repository without affecting the commit history?

2. What is the difference between a fast-forward merge and a no-fast-forward merge? In what scenario would you use each?

3. How would you handle a situation where a feature branch has diverged too much from the main branch, and you want to integrate the changes without losing any work?

4. If two developers are working on the same file and they both make changes to the same lines, how would you resolve this using Git?

5. How do you view the differences between two commits in Git? How would you compare a local branch with the remote branch?

6. What are Git tags, and how would you use them to mark important points in your project’s history (e.g., releases)?

7. Can you explain how to set up a Git hook that runs a linter on every commit?

8. In a situation where a pull request is rejected due to failing tests, how would you fix the issue and update the pull request with the corrected commits?

9. How can you undo the most recent commit, but keep the changes made in the working directory?

10. If you want to work on a feature branch and you notice that the main branch has received important updates, how would you get those updates without disrupting your work?

```

## Day -  3

```

1. How do you revert a commit that has already been pushed to the remote repository, and what steps do you follow to ensure the change is propagated to all team members?

2. What is a fast-forward merge in Git, and how does it differ from a non-fast-forward merge? When would you use one over the other?

3. How can you handle a situation where you have a large number of commits to squash before merging a feature branch into the main branch?

4. If you need to clean up your local Git repository by removing branches that have already been merged into the main branch, how would you go about doing that?

5. What is the purpose of the `.gitignore` file, and how can you ensure that sensitive files or folders are not accidentally committed to the repository?

6. How would you use `git bisect` to identify the commit that introduced a bug in a large repository, and what are some potential challenges you might encounter during the process?

7. Can you explain how Git handles file renaming and how you would go about detecting a file rename in a Git repository?

8. How can you configure Git to automatically sign your commits with GPG, and why is this important in an enterprise setting?

9. How would you use `git log` to view the commit history in a specific branch or for a specific author, and what are some useful flags you can add to refine the output?

10. Explain the difference between `git fetch` and `git pull` and how each command impacts the local repository’s state when working with remote repositories.

```
## Day - 4
```
1. How would you handle a situation where you need to push changes to a remote repository but the push is rejected due to non-fast-forward updates? What steps would you take to resolve this?

2. In a scenario where you need to pull changes from a remote repository but want to avoid any merge conflicts, what is the best strategy to follow?

3. How do you handle a situation where you accidentally commit files that should have been ignored (e.g., large log files or sensitive data), and how can you remove them from both your local and remote repositories?

4. Explain how you can configure Git to automatically rebase your local commits before pushing them to a remote repository. Why is this useful in a collaborative environment?

5. How would you address a situation where a colleague pushes directly to the `main` branch without following the proper pull request process? What actions would you take to enforce better Git practices in your team?

6. Can you explain the difference between `git reset`, `git revert`, and `git checkout`? In what scenarios would you use each command, and how do they impact the commit history?

7. How can you use Git hooks to enforce code style checks or run unit tests before commits are made? Can you describe a scenario where this automation could prevent issues?

8. What is a Git merge conflict, and how would you resolve one when working in a team with multiple branches? What tools can you use to make conflict resolution easier?

9. If you needed to delete a remote Git branch, what steps would you take to ensure that the branch is safely removed and does not disrupt the team’s workflow?

10. How do you handle large binary files (e.g., images, videos) in a Git repository, and what strategies or tools can you use to prevent bloating your Git history with large files?

```




