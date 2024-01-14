Note_to self.md

**My modifications** 
Since I have done some modifications, I want to keep them, such as this mere file and some additional snipes to further broaden my examples on what can langchain do"
I do first commit to my own branch: I should commit before mergin the upstream fetched from origin
``` git add . ```
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

To update your forked GitHub repository with changes from the original repository (often called the "upstream" repository), while also keeping your own modifications, you can follow these steps:

I have already add original repo as remote source to my local git. So I check this is the case: 
```` `git remote -v``
