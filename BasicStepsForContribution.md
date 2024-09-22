Here are the steps to make your contribution smoothly in open source repositories:

## Steps to Contribute

1. **Fork the Repository**
   - Go to the original repository and click the **Fork** button.

2. **Clone Your Fork**
   - Clone the forked repository to your local machine:
     ```bash
     git clone https://github.com/YOUR-USERNAME/REPO-NAME.git
     cd REPO-NAME
     ```

3. **Add the Upstream Repository**
   - Set the upstream remote to keep track of changes in the original repository:
     ```bash
     git remote add upstream https://github.com/ORIGINAL-OWNER/REPO-NAME.git
     ```

4. **Create a New Branch**
   - Create a new branch for your feature or bug fix:
     ```bash
     git checkout -b feature-branch
     ```

5. **Make Your Changes**
   - Make the necessary changes or add new code.

6. **Commit Your Changes**
   - Stage and commit your changes with a clear message:
     ```bash
     git add .
     git commit -m "Describe the change"
     ```

7. **Sync With the Original Repository**
   - If the original repository has new changes, pull the latest updates:
     ```bash
     git fetch upstream
     git merge upstream/main
     ```

8. **Push to Your Fork**
   - Push your changes to your fork on GitHub:
     ```bash
     git push origin feature-branch
     ```

9. **Create a Pull Request**
   - Go to your fork on GitHub and click **Compare & pull request**.
   - Describe your changes and link any related issues (e.g., `Closes #issue_number`).

10. **Respond to Feedback**
    - If any feedback is given, make the necessary changes, commit, and push to the same branch. Your pull request will update automatically.

11. **Tag or Mention Issues**
    - If applicable, reference any issue(s) in your pull request using `#issue_number` to close or link the issue.

12. **Keep Your Fork Updated** _(optional)_
    - Periodically sync your fork to stay up to date with the original repo:
      ```bash
      git fetch upstream
      git merge upstream/main
      git push origin main
      ```

---

Happy coding! 😊
