

# Collaborative Input
- Fill out Date, Username and a short Comment on this experience, and proceed with submitting the PR

| Date       | Username         |  Comment                                                                                                 |
| ---------- | ---------------- |  ------------------------------------------------------------------------------------------------------- |
| 04/09/2023 | GeorginaCarlisle |  Really nice clear instructions and great communication for Kasia. Thank you for the chance to practice. |
| 05/09/2023 | ShaneDoyle       |  Enjoyed the process, nice to finally get a chance to practice this for myself!                          |
| 05/09/2023 | inc21            |  Really enjoying playing around here and getting more comfortable with this. Thanks Kasia!!              |
| 13/09/2023 | SamOBrienOlinger |  Thanks Kasia! A lot learnt from you today.                                                              |


# Git Collaborative Steps

[Slides here](https://app.box.com/s/r356kxmp3yiwa96evgmpera7il9t4xyg)

## Fork, Clone, and Sync Your Fork

1. **Fork the Repository:**

   - Click the "Fork" button on the upper right corner of the repository page. This creates your own copy of this repository.

2. **Clone Your Fork**:

- Create folder with VS Code,
- Or just click the Green/Purple button with Cloud IDEs

3. **On VS Code**:

   - On your local machine, open a terminal.
   - Navigate to the folder where you want to clone the repository.
   - Clone your fork using the HTTPS URL:
     ```bash
     git clone https://github.com/insert-your-username-here/Git-Collaborative.git
     ```
   - Navigate to Your Repository:
     ```bash
     cd projectName
     ```

4. **Set Upstream Remote:**
   - Add an upstream remote to your repository to track the original repository:
     ```bash
     git remote add upstream https://github.com/bezebee/Git-Collaborative.git
     ```

## Make and Push Your Changes

5. **Create a New Branch:**

   - Create a new branch in your local repository to work on your changes:
     ```bash
     git checkout -b your-branch-name
     ```

6. **Add and Commit Changes:**

   - Make your code changes, add them, and commit them:
     ```bash
     git add .
     git commit -m "Your commit message"
     ```

7. **Push Your Changes to Your Fork:**
   - Push your local branch with the committed changes to your forked repository on GitHub:
     ```bash
     git push origin your-branch-name
     ```

## Create a Pull Request

8. **Create a Pull Request:**
   - After pushing your changes to your fork, follow link from the Terminal to create a pull request

## Sync Your Fork with the Original Repository

9. **Fetch and Merge Upstream Changes:**

   - Fetch the latest changes from the original repository:
     ```bash
     git fetch upstream
     ```
   - Merge the upstream changes into your local main branch:
     ```bash
     git checkout main
     git merge upstream/main
     ```

10. **Update Your Fork on GitHub:**

- Push the merged changes to your fork on GitHub:
  ```bash
  git push origin main
  ```

