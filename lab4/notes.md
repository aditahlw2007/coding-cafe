# Lab 4 — Git & GitHub Answers

### Question 1
`--global` means the Git setting applies to my whole computer/user account, so it will be used for all my Git repositories. If I leave out `--global`, the setting only applies to the current repository.

### Question 2
The `.git` folder appeared when I ran `git init`. It contains Git's internal information, including the repository history, configuration, and information Git needs to track changes. I should not manually change or delete anything inside it.

### Question 3
Git showed the files and folders in my `coding-cafe` directory that were not yet being tracked. The exact number depends on the files already present in my folder, and some of the entries may be code or other files that I created earlier.

### Question 4
After creating `.gitignore`, the files inside `.venv/`, along with `__pycache__/`, `.pyc` files, and `.DS_Store`, disappeared from the `git status` list. Git now ignores these files instead of treating them as untracked files.

### Question 5
`.gitignore` should be committed because it is an important part of the project and tells Git which files should not be tracked. It should not be ignored because other people who clone the repository also need these rules.

### Question 6
`README.md` moved from the "Untracked files" section to the "Changes to be committed" section. In the three-place model, the file moved from the working directory to the staging area after I ran `git add README.md`.

### Question 7
After the commit, Git printed information showing that a new commit was created and that files were changed. The exact number of files changed depends on the contents of my `coding-cafe` folder, so I should copy the number shown by my own `git commit` output.

### Question 8
The first seven characters are the short version of the commit's hash, also called the commit ID. They provide a short way to identify that specific commit and can be used to refer to it.

### Question 9
The four steps are: make a change, check the status or changes, stage the change with `git add`, and save it with `git commit`. This cycle is repeated whenever I make another set of changes.

### Question 10
`README.md` has a special name because GitHub automatically displays it on the main page of a repository. It is normally used to explain the project, its contents, and how to use it.

### Question 11
`gh auth login` authenticates my GitHub account in the terminal. It stores the authentication information so GitHub can recognize me when I push, meaning I do not need to enter my GitHub password every time.

### Question 12
The `README.md` file is shown on the front page of the GitHub repository. It is shown there because GitHub automatically renders a repository's README as the main introduction to the project.

### Question 13
No, pushing did not change my local Git history. `git push` copied my existing commits from my computer to GitHub; it did not create a new local commit.

### Question 14
A private repository exists on GitHub but only people who have permission can access it. If a repository does not exist on GitHub at all, there is no online repository for collaborators or TAs to access.


