# Lab 4 Notes

## Question 1
The `--global` option makes the Git configuration apply to the current user across all repositories on the computer. Without `--global`, the configuration applies only to the current repository.

## Question 2
Running `ls -a` shows hidden files and directories, including the `.git` directory. The `.git` directory contains Git's internal information, such as commits, branches, and configuration.

## Question 3
The untracked files are files that exist in the working directory but are not currently tracked by Git. The untracked code files are the files containing source code that have not yet been added to the staging area.

## Question 4
After creating `.gitignore`, files and directories matching its patterns no longer appear as untracked files in `git status`. The `.gitignore` file itself still appears as an untracked file until it is added to Git.

## Question 5
`.gitignore` should be committed because it is part of the project's configuration and tells Git which files should be ignored. Committing it ensures that other people working on the repository use the same ignore rules.

## Question 6
A file can move between three places in Git: the working directory, the staging area, and the repository. Editing changes the working directory, `git add` moves changes to the staging area, and `git commit` moves staged changes into the repository.

## Question 7
`git commit` creates a new commit from the changes currently in the staging area and records them in the repository history. The output reports the commit and summarizes how many files were changed and how many insertions or deletions occurred.

## Question 8
The first seven characters of the commit hash are `429b6ed`. They are a shortened form of the full commit hash and can be used to identify that commit.

## Question 9
The four steps of the repetitive Git loop are edit, stage, commit, and push. You edit files, use `git add` to stage them, use `git commit` to save a snapshot locally, and use `git push` to send the commits to GitHub.

## Question 10
`README.md` is the main introductory documentation file for a repository. It is normally placed in the root directory so that GitHub can automatically display it on the repository's front page.

## Question 11
`gh auth login` authenticates the GitHub CLI and stores authentication credentials securely. After authentication, GitHub CLI can use those credentials for future GitHub operations without repeatedly asking for a password.

## Question 12
GitHub renders the repository's `README.md` file on the repository's front page. This happens because README files provide an introduction and documentation for the project.

## Question 13
`git push` sends local commits to the remote repository on GitHub. It does not create or change commits in the local history; the commits already exist locally before they are pushed.

## Question 14
A private repository exists on GitHub but its contents are restricted to the owner and people who have been given access. Having no repository on GitHub means the project has not been created or uploaded there at all.
