
# Contribution Guidelines 

Welcome to our project! We appreciate your interest and contributions. Please read the following guidelines carefully to ensure a smooth collaboration.

## General Rules:

- **No Build Steps:** Avoid adding build steps like `npm install` to maintain simplicity as a static site.
- **Preserve Existing Content:** Do not remove existing content.
- **Issues:** Feel free to add a new issue and solve it yourself.
- **Code Style:** Your code can be neat, messy, simple, or complex. As long as it works, it's welcome.
- **Keep it Small:** Aim for small pull requests to minimize merge conflicts and streamline reviews.

## Getting Started 

1. **Fork the Repository:**
   - Use the fork button at the top right of the repository page.

2. **Clone Your Fork:**
   - Clone the forked repository to your local machine.

   ```bash
   git clone https://github.com/aitr-hacktoberfest2024.git
   ```

3. **Navigate to the Project Directory:**

   ```bash
   cd hacktoberfest2024
   ```

4. **Create a New Branch:**

   ```bash
   git checkout -b my-new-branch
   ```

5. **Make Your Changes:**

   ```bash
   git add .
   ```

6. **Commit Your Changes:**

   ```bash
   git commit -m "Message"
   ```

7. **Push to Your Branch:**

   ```bash
   git push origin my-new-branch
   ```

8. **Create a Pull Request:**
   - Go to your forked repository on GitHub and create a pull request to the main repository.

## Avoiding Conflicts {Syncing Your Fork}

To keep your fork up-to-date with the main repository and avoid conflicts:

1. **Add Upstream Remote:**

   ```bash
   git remote add upstream https://github.com/aitr-hacktoberfest2024.git
   ```

2. **Verify the New Remote:**

   ```bash
   git remote -v
   ```

3. **Sync Your Fork with Upstream:**

   ```bash
   git fetch upstream
   git merge upstream/master
   ```

   This will pull in changes from the parent repository and help you resolve any conflicts.

4. **Keep Updated:**
   - Regularly pull changes from the upstream repository to keep your fork updated.

We look forward to your contributions and thank you for being a part of our community!
