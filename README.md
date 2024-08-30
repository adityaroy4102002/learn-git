# learn-git

Learning git and github through practice

## Table of content

- [learn-git](#learn-git)
  - [Table of Content](#table-of-content)
  - [Initialization a repository](#initialize-a-repository)
  - [Stage changes](#stage-changes)
  - [Commit changes](#commit-changes)
  - [Adding Remote Repository](#adding-remote-repository)

## Initialize a repository

Use `git init` command in the root of the project to initialize a git repository.

```bash
git init
```

## Stage changes

Stage your changes using `git add` command. You can add whole directory as well using directory name.

```bash
# To stage a file
git add <filepath-to-add>

# To stage a directory
git add <directory-to-add>

# To stage the whole project, use the following in project root
git add .
```

## Commit changes

Commit your changes using `git commit` command.

```bash
git commit -m "Write a message for your commit"

# It is a good practice to write the message in the following format
git commit -m "Short message

Commit description"
```

## Add remote repository

Add a remote repository(e.g. github repo) using `git remote` command.

```bash
git remote add origin <remote-url(ssh)>
```

## Pull changes from remote

You can pull changes from remote repository using `git pull` command.

```bash
git pull origin
```

## Push changes to remote

You can push your changes to remote repository using `git push` command.

```bash
git push origin
```
