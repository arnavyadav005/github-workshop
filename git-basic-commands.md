# --- GIT BASICS COMMANDS ---

# 1. Check your files (See what is modified)
    git status

# 2. Prepare your changes (Stage all files for saving)
    git add .

# 3. Save your changes (Take a permanent snapshot)
    git commit -m "your explanation here"

# 4. Upload your code (Send saved commits to GitHub/remote)
    git push

# 5. Download updates (Get latest changes from GitHub/remote)
    git pull

# Git Remote Commands:

* **`git remote`** — Lists the short names of all currently configured remote repositories.

* **`git remote -v`** — Lists all remotes along with their exact fetch and push URLs.

* **`git remote add <name> <url>`** — Connects your local repository to a new remote server (usually named `origin`).

* **`git remote remove <name>`** — Deletes the connection to a specific remote repository.

* **`git remote rename <old_name> <new_name>`** — Changes the local short name of an existing remote.

* **`git remote set-url <name> <new_url>`** — Updates the URL for an existing remote connection.

* **`git remote show <name>`** — Displays detailed sync and branch information about a specific remote.