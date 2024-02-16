# Collaborative Input

<details>
<summary> 👇 Fill out Date, Username and a short Comment on this experience, and proceed with submitting the PR 👇 </summary>
<br>

| 15/02/2024       | decant09         |      Great resource, thanks so much Kasia                                                                                                                                                                                                               |
| ---------- | ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 05/10/2023 | JWalshe86        | Forking great stuff Kaisa, thanks for this.                                                                                                                                                                                |
| 04/09/2023 | GeorginaCarlisle | Really nice clear instructions and great communication for Kasia. Thank you for the chance to practice.                                                                                                                    |
| 05/09/2023 | ShaneDoyle       | Enjoyed the process, nice to finally get a chance to practice this for myself!                                                                                                                                             |
| 05/09/2023 | inc21            | Really enjoying playing around here and getting more comfortable with this. Thanks Kasia!!                                                                                                                                 |
| 13/09/2023 | SamOBrienOlinger | Thanks Kasia! A lot learnt from you today.                                                                                                                                                                                 |
| 14/09/2023 | URiem            | Thanks for this little GitHub lesson, Kasia! Still trying to wrap my head around what exactly happened in the background as I was completing all these step. I am sure it will click eventually. It's very useful to know! |
| 26/9/2023  | URiem            | Learn and Repeat the process using VSCode - always learning something new! Thanks for all the help!!                                                                                                                       |
| 02/10/2023 | NiclO1337        | Thanks for opportunity to try this and learn!                                                                                                                                                                              |
| 09/10/2023 | Zaicodes         | Thank you for helping us practice this, still not 100% confident but I'm sure the Hackathon will help a lot.                                                                                                               |
| 12/10/2023 | Kiksgold         | Thank you Kasia for your help. I look forward to the next hackathon.                                                                                                                                                       |
| 12/10/2023 | SharjAhmed       | Thanks for this lesson Kasia! Looking forward to the Hackathon!                                                                                                                                                            |
| 12/10/2023 | johnamdickson    | Not taking part in October Hackathon but appreicate the tutorial on GitHub. Thanks Kaisa!                                                                                                                                  |
| 14/10/2023 | patthoege        | First time doing a fork, clone and create a new branch by myself successfully! Thanks for the help and practice Kasia!                                                                                                     |
| 17/10/2023 | ajmmcredie       | Thank you for the pre-Hackathon practise Kasia!                                                                                                                                                                            |
| 17/10/2023 | NikolettaGr      | Thank you Kasia for this opportunity!                                                                                                                                                                                      |
| 30/10/2023 | llancruzz        | Thanks for the help and practice Kasia                                                                                                                                                                                     | Thank you
|   16 /02/2024         |                  |                                                                                                                                                                                                                            |
|            |                  |                                                                                                                                                                                                                            |
|            |                  |                                                                                                                                                                                                                            |
|            |                  |                                                                                                                                                                                                                            |
|            |                  |                                                                                                                                                                                                                            |
|            |                  |                                                                                                                                                                                                                            |
|            |                  |                                                                                                                                                                                                                            |
|            |                  |                                                                                                                                                                                                                            |

</details>

# Git Collaborative Visual Steps for VS Code

[Slides here](https://app.box.com/s/r356kxmp3yiwa96evgmpera7il9t4xyg)

# Fork, Clone, and Sync Your Fork

1. **Fork the Repository:**

   - Click the "Fork" button on the upper right corner of the repository page. This creates your own copy of this repository.

2. **Clone Your Fork**:

- **CodeAnywhere** - click on the **purple button**
- **Gitpod** - click on the **green button**
- **On VS Code** - **create folder** and then:
  - On your local machine, open a terminal.
  - Navigate to the folder where you want to clone the repository.
  - Clone your fork using the HTTPS URL:
    ```bash
    git clone https://github.com/insert-your-username-here/Git-Collaborative.git
    ```
  - Add an upstream remote to your repository to track the original repository:
    ```bash
    git remote add upstream https://github.com/bezebee/Git-Collaborative.git
    ```

# Make and Push Your Changes

3. **Create a New Branch:**

   - Create a new branch in your local repository to work on your changes:
     ```bash
     git checkout -b your-branch-name
     ```

4. **Add and Commit Changes:**

   - Make your code changes, add them, and commit them:
     ```bash
     git add .
     git commit -m "Your commit message"
     ```

5. **Push Your Changes to Your Fork:**
   - Push your local branch with the committed changes to your forked repository on GitHub:
     ```bash
     git push origin your-branch-name
     ```

# Create a Pull Request

6. **Create a Pull Request:**
   - After pushing your changes to your fork, follow link from the Terminal to create a pull request
   - Once PR created and merged, come back to the README to see what to do next

# Sync Your Fork with the Original Repository

7. **Fetch and Merge Upstream Changes:**

   - Fetch the latest changes from the original repository:
     ```bash
     git fetch upstream
     ```
   - Merge the upstream changes into your local main branch:
     ```bash
     git checkout main
     git merge upstream/main
     ```

8. **Update Your Fork on GitHub:**

- Push the merged changes to your fork on GitHub:
  ```bash
  git push origin main
  ```
