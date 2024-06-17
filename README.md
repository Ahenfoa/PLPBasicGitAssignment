# Git and GitHub Basics: Assignment Documentation

This document outlines the basic steps to set up a GitHub repository, connect it to a local folder using `git clone`, make changes, commit, and push to GitHub.

## Task 1: Repository Setup

1. **GitHub Repository Creation:**
   - Log in to GitHub.
   - Create a new repository named "powerlearnproject".
   - Initialize it with a README file.

## Task 2: Cloning the Repository

2. **Clone Repository:**
   - Open a terminal or command prompt.
   - Navigate to the directory where you want to clone the repository.
   - Use `git clone` followed by the URL of the repository.
     ```bash
     git clone https://github.com/Ahenfoa/powerlearnproject.git
     ```

## Task 3: Making Changes

3. **Create a File:**
   - Inside your local folder (e.g., `powerlearnproject`), create a new text file (e.g., `hello.txt`).
   - Add a simple text message (e.g., "Hello, Git!").

4. **Committing Changes:**
   - Stage the changes.
     ```bash
     git add powerlearnproject.txt
     ```
   - Commit the changes.
     ```bash
     git commit -m "appreciation"
     ```

## Task 4: Pushing to GitHub

5. **Pushing to GitHub:**
   - Push the committed changes to your GitHub repository.
     ```bash
     git push origin main
     ```

