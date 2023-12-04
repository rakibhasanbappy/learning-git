To learn Git and Github, you can follow this book by Zonayed Ahmed: https://with.zonayed.me/book/git-n-github-at-glance/

This book is written in Bengali.

When we initialize(init) a git repo in our local machine, the default branch is set to `master`. But in Github, the default branch is set to `main`.  You can change the default branch to `master` in github from the settings. However many platforms and communities have transitioned to using main as the default branch name to promote more inclusive language. So, to change the default branch in your local machine, you can first rename the "master" to `main` by the following command:

```git branch -m master main```

After renaming the branch, you should be able to use `git push origin main` without any issues.

To make `main` as your default branch in local repository, run the following command: 

```git config --global init.defaultBranch main```


If you already push the `master` branch to github, you can delete the `master` branch by following command: 

```git push origin --delete master```
