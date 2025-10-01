# A02

### Git
**Git** is a distributed version control system that tracks changes in source code and allows multiple developers to collaborate efficiently.

**How to use:**
1. Download **Git** from https://git-scm.com/downloads.
2. Navigate to your project folder in the terminal.
3. Run `git init` to initialize a local **repository**.
4. Create a new **branch** for your work using `git branch <branch-name>` and switch with `git checkout <branch-name>`.
5. Use `git add .` to stage changes and `git commit -m "<message>"` to save them.
6. Use `git fetch` to check for updates from the **remote** **repository** without merging them.
7. Merge your **branch** back into the main one using `git merge <branch-name>`. If two people edited the same lines, you may get a **merge conflict**, which you'll need to fix manually.
8. Use `git status` to check changes and `git log` to view history.

### GitHub
**GitHub** is a cloud-based platform that hosts **Git** **repositories** and provides collaboration features like **pull** requests, issue tracking, and project management.

**How to use:**
1. Create a **GitHub** account at https://github.com/.
2. Make a new **repository** on **GitHub**.
3. Connect your local **Git** project with `git remote add origin <repo_url>`.
4. **Push** commits from your computer to the **remote** **repository** on **GitHub** using `git push origin main` (or `master`).
5. Collaborators can **clone** the **repository**, make changes, and **push** updates.
6. When merging changes, **GitHub** may flag a **merge conflict** if different **branches** altered the same code. You can manually fix the conflict from within **Github's** web interface.

### WebStorm
WebStorm is an integrated development environment (IDE) by JetBrains designed for JavaScript, TypeScript, and web development. It offers code completion, debugging, version control integration, and project management tools.

**How to use:**
1. If you are a student, WebStorm can be installed from https://www.jetbrains.com/student/.
2. Open the IDE and display the Webstorm settings (press `Ctrl+Alt+S`)
3. Choose `Version Control` -> `Git` from the left side.
4. Choose the location of your Git install. The path will look like: `C:\Program Files\Git\bin\git.exe`
5. Click `Test` to make sure that Webstorm is connected to Git.
6. If Git is installed correctly, you should get the message "Git Executed Successfully."
7. Create a new project or open an existing one. You can clone a **remote** **repository** from **GitHub** into WebStorm with the built-in **clone** option.
8. Use the interface to make a **commit** whenever you finish a task.
9. Push your **commits** to **GitHub** with the "**Push**" option, or **pull** new changes from teammates with "**Pull**."
10. When working on a feature, create a **branch** in WebStorm, and **merge** it back once complete.

### References
- "Introduction to Github and Webstorm" by Arthur H. Hendela, Ph.D
- "Additional Instructions on Creating a Git and Github repository." Revised (2/15/2020) by Arthur H. Hendela, Ph.D

### Glossary
- **Branch** - A separate line of development within a Git repository.
- **Clone** - A local copy of a remote Git repository.
- **Commit** - A saved snapshot of your code at a particular point in time, along with a message describing the changes.
- **Fetch** - A Git command that downloads changes from a remote repository but does not merge them into your local code automatically.
- **Git** - A distributed version control system that tracks changes in source code and allows multiple developers to collaborate efficiently.
- **Github** - A cloud-based platform that hosts Git repositories and provides collaboration features like pull requests, issue tracking, and project management.
- **Merge** - The process of combining changes from one branch into another.
- **Merge Conflict** - A situation where Git cannot automatically merge code because changes in different branches affect the same part of a file in incompatible ways.
- **Push** - Uploading your local commits to a remote repository (e.g., GitHub) so others can see and use them.
- **Pull** - A command that fetches changes from a remote repository and merges them into your local branch.
- **Remote** - A reference to a version of your repository that's hosted on another server, like GitHub.
- **Repository** - A storage space for your project that contains all the code, history, and configuration for version control.
