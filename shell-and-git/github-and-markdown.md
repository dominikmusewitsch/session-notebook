Hints and collection of commands I find helpful

| command                    |            functionality             |
| -------------------------- | :----------------------------------: |
| git switch -c _branchname_ | create a new branch and switch to it |
| git switch _branchname_    |           switch branches            |
| git branch                 |          list your branches          |
| git branch -a              | list all branches (local and remote) |
| git branch -d _branchname_ |           delete a branch            |

Basic Workflow for a pull request (PR)

1. Create a new branch with git switch -c _branchname_.
2. Make changes to the code / write your code fpr the feature.
3. Push the changes and the new branch with git push -u origin _branchname_ (after you have done this once you can use git push for this branch)
4. Create a pull request on GitHub from the new branch into main
5. Share the pull request with your team
6. Review the pull request, implement changes if needed, push again to update the pull request until it gets approved
7. Merge the pull request into main
8. Don't forget to git pull inside the main branch on your local machine
9. Delete the new branch on GitHub and locally
