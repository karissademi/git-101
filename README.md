# Git + GitHub for Beginners

### Steps we'll be taking

1. Clone this repository

```
$ git clone https://github.com/karissademi/git-101.git
```

2. Add a .txt file in the `/users` directory. In the file, include 
 - your name
 - job title
 - most recent project
 -  favorite programming language

3. Name the file `your-name.txt`

4. Enter the directory on your computer

```
$ cd git-101
```

5. Checkout a new branch e.g. `task/your-name`

```
$ git checkout -b task/karissa-demi
```

6. Check the status of the working directory
```
$ git status
```

7. Add the file in git
```
$ git add karissa-demi.txt
```

8. Check the status again
```
$ git status
```

9. Create a commit message
```
$ git commit -m "Add my file"
```

10. Create the remote branch and push your changes to the origin
```
$ git push --set-upstream origin task/sample-user
```

11. Open a pull request for your branch in the GitHub interface

12. Check the pull request that appears under your own. 

13. Provide feedback. 

14. Check your original pull request to see if you need to make a change. 

15. Make the change and commit. 
```
$ git add <file-name>
$ git commit -m "A commit message that explains the change you made" 
```
16. Push the changes
```
$ git push
```
17. Merge the orginal pull request. 

18. Switch back to the master branch
```
$ git checkout master
```
19. Get all the changes we've been making on your local copy
```
$ git pull 
```
20. See all the changes
```
$ git log
```
21. Delete your branch
```
$ git branch -D <branch-name>
```
Forgot your branch name? 
```
$ git branch
```




