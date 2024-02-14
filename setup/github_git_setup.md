
# Git Setup Instructions for Flexbox 4.0 Project

**Reminder**: Begin by creating a blank GitHub repository, ensuring no README, license, or .gitignore files are automatically generated. Remember to save the initial setup instructions provided by GitHub.

## Identity Configuration

This setup uses the 'school' identity from the SSH and Git configuration.

### 1. Initialize the Git Repository

- Navigate to your project directory:
  ```bash
  cd path/to/flexbox_4.0
  ```

- Initialize the directory as a Git repository:
  ```bash
  git init
  ```

### 2. Set and Verify Local Git Identity

- Set the local Git user name and email, and verify the configuration in one line:
  ```bash
  git config user.name "dirwebdev" && git config user.email "dirwebdev@gmail.com" && git config user.name && git config user.email
  ```

### 3. Add Remote Repository

- Add the GitHub repository as a remote using the SSH URL:
  ```bash
  git remote add origin git@github.com-school:dirwebdev/flexbox_4.0.git
  ```

### 4. Stage and Commit the README.md

- Add the `README.md` file to the staging area:
  ```bash
  git add README.md
  ```

- Commit the addition of the `README.md` file:
  ```bash
  git commit -m "Add initial README.md"
  ```

### 5. Rename the Local Branch to Main

- Rename your local branch to `main`:
  ```bash
  git branch -M main
  ```

### 6. Push to GitHub

- Push your local `main` branch to the GitHub repository:
  ```bash
  git push -u origin main
  ```

### 7. Status Check

- Confirm the status of your local Git repository:
  ```bash
  git status
  ```

- List all branches, including remote tracking branches:
  ```bash
  git branch -a
  ```

By following these detailed steps, you have initialized your Git repository, set the local Git identity using the 'school' profile, staged, committed, and pushed your initial README.md to GitHub.

