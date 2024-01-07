Note_to self.md

**how to update the forked mine** with the original of the author repo; 
to check the state of your current forked repo with the original repo
      ``` git remote -v ```

*** Fetching Changes from the Original Repository:***
To fetch changes from the original repository, use: 
        ```git fetch upstream```

This command retrieves updates from the original repository, but it doesn't merge them into your local branches.

'''***Merging Updates into Your Local Branch***''':
Now, merge the updates from the original repository's main branch (or another branch if specified) into your local branch:

        ```git merge upstream/main main```


Replace 'main' with the default branch name if different

''***Pushing Updates to Your Fork on GitHub:***''
Finally, push the updates to your forked repository on GitHub:
        ```git push origin main```

