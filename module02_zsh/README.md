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
| python3    | Launches the python3 interpretor                              |
## AI Use Statement
I did not use AI for this lab.

## Week 3: Virtual Environments and .zshrc
## Commands Practiced
| Command                               | What it does                                                                                      |
|---------------------------------------|---------------------------------------------------------------------------------------------------|
| python3 -m venv .venv                 | Creates an isolated python virtual environment called .venv in the current directory              |
| source .venv/bin/activate             | Activates the virtual environment, switching the shell to use specific Python interpreters and packages |
| which python3                         | Displays the precise file path of the active Python executable being used in the terminal         |
| pip install pytest ruff               | Downloads/installs the pytest and ruff packages into the active environment                       |
| pip list                              | Displays a list of all Python packages installed                                                  |
| pip freeze > requirements.txt         | Saves a list of all currently installed Python packages and their versions into a file            |
| source ~/.zshrc                       | Reloads the zsh configuration to apply any recent edits/aliases                                   |
| pytest --collect-only                 | Lists all discovered test cases without executing                                                 |
| deactivate                            | Exits the virtual environment and restores the terminal to the global Python                      |
| alias ll='ls -la'                     | Alias shortcut to list all files and directories, including hidden ones                           |
| alias c='clear'                       | Alias shortcut to clear the current terminal output                                               |
| alias py='python3'                    | Alias shortcut to launch the python3 interpretor                                                  |
| alias gs='git status'                 | Alias shortcut to display the working tree status of the Git repository                           |
| alias ga='git add .'                  | Alias shortcut to stage all current changes and untracked files for the next commit               |
| alias gcmsg='git commit -m'           | Alias shortcut to commit staged changes with a commit message                                     |
| alias gp='git push'                   | Alias shortcut to upload local repository commits to the tracking branch                          |
| alias gl='git log --oneline'          | Alias shortcut to display the commit history in a single line format                              |
| alias tree2='tree -L 2'               | Alias shortcut to display a directory tree visualization                                          |
| mkcd () { mkdir -p "$1" && cd "$1" }  | Creates a new directory path if nonexistant and immediately enters it                             |
## AI Use Statement
I did not use AI for this lab.