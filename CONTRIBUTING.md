Contributing Guidelines
Thank you for considering contributing! 🎉
Follow these steps to make the process smooth for everyone.

1. Fork the Repository

Go to the repository page.
Click the Fork button (top-right corner).
This creates your own copy of the project under your GitHub account.


2. Create a Branch

Clone your fork to your local machine:Bashgit clone https://github.com/<your-username>/<repo-name>.git


Navigate into the project folder:Bashcd <repo-name>


Create a new branch for your changes:Bashgit checkout -b feature/your-feature-name

Use feature/ for new features, fix/ for bug fixes.


3. Commit Message Style


Keep messages short and descriptive.


Use the present tense (e.g., "Add new login button" not "Added").


Format:
<type>: <short description>

Types:

feat: New feature
fix: Bug fix
docs: Documentation changes
style: Code style changes (no logic changes)
refactor: Code restructuring
test: Adding or updating tests

Example:
feat: add dark mode toggle




4. Open a Pull Request (PR)

Push your branch to your fork:Bashgit push origin feature/your-feature-name


Go to the original repository on GitHub.
Click Compare & pull request.
Fill in:

Title: Short summary of your change.
Description: Explain what you did and why.


Submit the PR and wait for review.


💡 Tip: Keep your fork updated with the main repo to avoid merge conflicts:
Bashgit remote add upstream https://github.com/<original-owner>/<repo-name>.git
git pull upstream main


