Step 1: Install Git and Verify
If you haven't installed Git yet, download and install it from git-scm.com. Once installed, open your terminal (Command Prompt, PowerShell, or the integrated terminal in VS Code) and verify the installation:

Bash
git --version
Step 2: Open the Terminal in Your Project Folder
Navigate to your project directory. If you are using Visual Studio Code, you can simply open your project folder and open the terminal (Ctrl + ~ or via the top menu: Terminal > New Terminal).

Step 3: Initialize the Repository
Run the initialization command to create a hidden .git folder in your project directory:

Bash
git init
Step 4: Configure Your Git Username and Email
Set up your global identity so your commits are properly attributed to you:

Bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Step 5: Create an HTML File
Create a new file named index.html in your project folder and add some basic HTML boilerplate code (e.g., a simple heading and paragraph).

Steps 6 & 7: Make at Least 3 Meaningful Commits
To fulfill the requirement of making three distinct, meaningful commits, you will make incremental changes to your HTML file, checking the status and committing each change separately.

Commit 1: Add initial HTML structure
Check the status to see your untracked file:

Bash
git status
Stage the file:

Bash
git add index.html
Commit with a meaningful message:

Bash
git commit -m "feat: add initial HTML boilerplate structure"
Commit 2: Add page content and headings
Open index.html, add a main heading (<h1>) and a description paragraph about your project, then save the file.

Check status and stage the changes:

Bash
git add index.html
Commit the second change:

Bash
git commit -m "content: add main heading and project description"
Commit 3: Add footer or structural sections
Open index.html again, add a footer section or a navigation link, and save the file.

Stage and commit the final change:

Bash
git add index.html
git commit -m "style: add footer section with copyright details"
Capturing Your Submission Screenshots
For your submission, you will need to capture two things:

Screenshot of the Repository Folder:

Make sure hidden items are visible in your file explorer so the .git folder is visible alongside your index.html file.

Screenshot of the Commit History:

Run the following command in your terminal to display your commit history nicely, and take a screenshot of the output:

Bash
git log --oneline