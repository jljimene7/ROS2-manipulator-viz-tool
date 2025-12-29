# Git Practices

This repo strives to use professional git practices to ensure compliance with leading industry practice. Therefore, familiarity with git tools are crucial for contributing to this codebase. Key terminology is bolded. Ensure familiarity with these terms to make the best use of this document.

## Rebase Feature Branch
In order to rebase a feature branch, a couple pre-merge checks must be made. For sake of brevity and clarity, assume the branch to be merged into is `main` branch.  The branch we are merging is the `feature` branch. Check this [video](https://www.jetbrains.com/guide/tips/rebase-feature-branch/) for a clear example.

1. Has `main` branch changed since you create a branch from it?
    - Yes: you need to rebase the feature branch to the latest commit on the `main` branch. Go to step 2. 
    - No: you can merge the branch in. Push to origin/main (i.e. github). Done!
2. Resolve any conflicts that occur from the rebase and make sure the code looks neat. Merge into main branch. Finally, push to origin/main (i.e. github). Done!

## Git Merge Branch
> Merging is one of the most **important** parts of using git!

In order to properly understand how to use git to contribute to this repo, understanding merging branches is necessary. 

Check out this [article](https://www.geeksforgeeks.org/git/git-merge/) for a clear breakdown with the differences and use cases explained for `git merge` and `git rebase`.