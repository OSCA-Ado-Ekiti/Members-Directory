# Contributing to Members-Directory Repository
We would love for you to contribute to Members-Directory to help curate a list of all members within the chapter. As a contributor, here are the guidelines we would like you to follow:

## Code of Conduct
Please read and follow our [code of conduct](CODE_OF_CONDUCT.md)

## Question or Problem?
Do not open issues for general support questions as we want to keep GitHub issues for bug reports and feature requests. You've got much better chances of getting your question answered on [Discord Channel](https://discord.gg/M5g9TC9n) or google.

## Found a bug?
If you find a bug in the source code, you can help us by submitting an issue to our GitHub Repository. Even better, you can submit a Pull Request with a fix.

## SUBMISSION GUIDELINES
### Submitting an Issue:
Before you submit an issue, please search the issue tracker, maybe an issue for your problem already exists and the discussion might inform you of workarounds readily available.

### Submitting a Pull Request (PR):
Before you submit your Pull Request (PR) consider the following guidelines:

1. Search the repository for an open or closed PR that relates to your submission. You don't want to duplicate effort.

2. Be sure that an issue describes the problem you're fixing, or documents the design for the feature you'd like to add. 

3. Make sure you sign with the primary email address of the Github identity that has been granted access to the team repository.

4. Fork repo.

5. On your command line, clone repository
    ```
    git clone <repo-url>
    ```
6. Add remote upstream
    ```
    git remote add upstream <repo-url>
    ```
    You can check this by typing `git remote`, you should have `origin` and `upstream`

7. Run the following commands;
    `git checkout main`
    `git fetch upstream`
    `git merge upstream/main`
    `git push`

8. Create a new branch to work on
    `git checkout -b <BRANCHNAME>`

9. Make the changes you want from this branch.

10. Add and commit your changes
    `git add <filename>` or `git add .` to add multiple files.
    `git commit -m "explicit commit message"`

11. Run the first three commands in #7 above.

12. `git checkout <YOUR-BRANCHNAME>`

13. `git rebase main`

14. Push your code
    `git push --set-upstream origin <YOUR-BRANCHNAME>`

That's it! Go ahead and click on the `Create Pull Request` button on the web.

Thank you for your contribution!
