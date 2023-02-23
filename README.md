# Git & GitHub

Exploring git and github in the workshop

## Table of Contents

- [Git Commands](#git-commands)

### Git Commands

1. Download and install git from [git-scm](https://git-scm.com/)
2. Check git version

```bash
git --version
```

3. Let Git know who you are

```bash
git config --global user.name "your name"
git config --global user.email "your@email.here"
```

4. Check the status of files/project

```bash
git status

# the short way
git status --short

    #  ?? - Untracked files
    # A - Files added to stage
    # M - Modified files
    # D - Deleted files
```

5. Add a file to the staging environent

```
git add <filename">
# or
git add .
```

6. Committing our project files

```
git commit -m "our message"
```
