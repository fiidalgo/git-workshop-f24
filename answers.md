**Name:** Nico Fidalgo

1. What is the difference between git and GitHub?

git is something that you need to download and it contains all of the git commands that you can run in your terminal. This is the "version control" part where you can stage your changes and push them and collaborate. GitHub is a cloud host of the remote repo so that it can be viewed and shared.

1. Why is version control important?

Version control is important as it ensures that all collaborators on a project are working with the same code as they make changes and that everything is up to date that way no work needs to be unnecessarily repeated.

1. What is the command to view a branch's commit history?

```bash
git log
```

1. What command lists all the branches in your local repository? Which one lists those in the remote?

```bash
git branch
```

This command lists all the branches in your local repository.

```bash
git branch -r
```

This command lists all the branches in the remote repository.

1. To prevent specific files and folders from being commited to a repository, what should you do?

You should put them in the `.gitignore` file. Common files would be `.venv` files, `.env`, and any secrets.
