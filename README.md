# A02

### Git
Git is a version control system that tracks changes in code, lets multiple people collaborate, and helps manage different versions of a project.

How to use:
1. Download Git from https://git-scm.com/downloads.
2. Navigate to your project folder in the terminal.
3. Run `git init` to start version control.
4. Use `git add .` to stage changes and `git commit -m "<message>"` to save them.
5. Use `git status` to check changes and `git log` to view history.

### GitHub
GitHub is a cloud-based platform for hosting Git repositories. It's used to collaborate on code, share projects, and track issues.

How to use:
1. Create a GitHub account at https://github.com/.
2. Make a new repository on GitHub.
3. Connect your local Git project with `git remote add origin <repo_url>`.
4. Push code to GitHub using `git push origin main` (or `master`).
5. You can use GitHub's web interface to review code, open issues, and collaborate with others.

### WebStorm
WebStorm is an integrated development environment (IDE) by JetBrains designed for JavaScript, TypeScript, and web development. It offers code completion, debugging, version control integration, and project management tools.

How to use:
1. If you are a studen, WebStorm can be installed from https://www.jetbrains.com/student/.
2. Open the IDE and create a new project or open an existing one.
3. You can write code in the editor with features like auto-complete and error checking.
4. You can execute and debug code directly within the IDE.
5. Integrate with Git/GitHub inside WebStorm for source control.

How to integrate with Git:
1. Display the Webstorm settings (press `Ctrl+Alt+S`)
2. Choose `Version Control` -> `Git` from the left side.
3. Choose the location of your Git install. The path will look like: `C:\Program Files\Git\bin\git.exe`
4. Click `Test` to make sure that Webstorm is connected to Git.
5. If Git is installed correctly, you should get the message "Git Executed Successfully."

### References
- "Introduction to Github and Webstorm" by Arthur H. Hendela, Ph.D
- "Additional Instructions on Creating a Git and Github repository." Revised (2/15/2020) by Arthur H. Hendela, Ph.D
