1.) Basics:
git.initit
git add .
git status
git commit -m "message"
git restore

2.) how to push it
2.) how to push it:
step 1.) create repositories
step 2.) git remote add origin https://github.com/anishshete21-beep/github_for_devops.git , you will get this paste it on terminal
step 3.) use git remote -v
step 4.)create a classic token, and allow rep
step 5.)use git remote set-url origin https://
step 6.) copy paste the tokken :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
step 7.) and add at the end @github.com/anishshete21-beep/github_for_devops.git
step 8.)use git remote -v
step 9.) git push origin master

3.) FORK:
A Fork is a copy of someone else's GitHub repository into your own GitHub account.

It lets you make changes without affecting the original project.

Why do we use Fork?
🍴 Copy an open-source project to your account.
✏️ Make changes safely.
🤝 Contribute to the original project by creating a Pull Request.
Example
Original Repository (Owner)
          │
        Fork
          ▼
Your GitHub Repository
          │
   Make Changes
          │
   Create Pull Request
          ▼
Original Repository
Simple Analogy

Imagine your teacher shares a document.

Fork = Make your own copy.
Edit your copy.
If your work is good, ask the teacher to merge it into the original document.
One-line Interview Answer

A fork is a copy of another user's GitHub repository in your own GitHub account, allowing you to make changes without affecting the original project.

4.)Branches (Git) – Short & Simple

A branch is a separate line of development in Git.

git branch                   # Show branches
git branch feature           # Create a new branch
git checkout -B feature      # Create a new branch and Switch to It
git switch feature           # Switch to the branch
git merge feature            # Merge into current branch

Think of a tree:

Trunk = main branch
Branches = Different features or tasks

4.)Branches (Git) – Short & Simple

A branch is a separate line of development in Git.

git branch                 # Show branches

git checkout -b feature    # Create & switch branch

git switch -c feature      # Modern way

git status                 # Check changes

git add .                  # Stage changes

git commit -m "message"    # Save changes

git push origin feature    # Push branch

git pull origin main       # Get latest changes

git checkout main          # Switch branch

git merge feature          # Merge feature into current branch

git branch -d feature      # Delete local branch
Think of a tree:

Trunk = main branch
Branches = Different features or tasks