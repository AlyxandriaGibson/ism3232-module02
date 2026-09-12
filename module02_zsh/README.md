# ISM3232 - Module 2: zsh Navigation and File Operations
## Commands Practiced
| Command    | What it does                                                  |
|------------|---------------------------------------------------------------|
| pwd        | Prints the current working directory                          |
| ls         | Lists the visible files and folders                           |
| ls -la     | Lists all files including hidden ones                         |
| cd ..      | Moves you up one level in the directory                       |
| code .     | Opens the current working directory as a workspace in VS Code |
| rm         | Permanently deletes files or directories                      |
| touch      | Creates a new, empty file                                     |
| mkdir      | Make directory, creates a new, empty directory                |
| cd         | Navigates or moves you between folders                        |
| tree       | Displays files and folders as a branching tree diagram        |
| mv         | To move                                                       |
| cp         | To copy                                                       |
| python 3   | Launches the python3 interpretor                              |
## AI Use Statement
I did not use AI for this lab.

## Week 3: Virtual Environments and .zshrc
## Commands Practiced
| Command    | What it does                                                  |
| python3 -m venv .venv
| source .venv/bin/activate
| which python3
| pip install pytest ruff
| pip list
| pip freeze > requirements.txt
| source ~/.zshrc
| pytest --collect-only
| deactivate
| alias ll='ls -la'
| alias c='clear'
| alias py='python3'
| alias gs='git status'
| alias ga='git add .'
| alias gcmsg='git commit -m'
| alias gp='git push'
| alias gl='git log --oneline'
| alias tree2='tree -L 2'
| mkcd () { mkdir -p "$1" && cd "$1" }