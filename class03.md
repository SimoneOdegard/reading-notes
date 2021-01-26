# Read 03

## Version Control
This allows you to see recorded changes of multiple versions of a file or group of files. This makes it easy to correct mistakes or changes.
- **Local Version Control** "A Local VCS entails one database on your hard disk that stores changes to files" [(Source)](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)
- **Centralized Version Control** This makes collaborations with teams easy. You can access a single server that stores all changes to a file.
- **Distributed Version Control** This creates mirrored repos. This prevents loss of major files in case of system failure or data corruption. This is also great for when you're working in a collaboration.

## What is Git?
Git is a DVCS which stores mirrored repos in the form of snapshots. When you save each version that you make changes to, you are doing a "commit". This is your snapshot into what you've done and what you've changed to your project or file. This is also how you are able to track changes with each version you have worked on. Because you're keeping track of each step in your process when doing a commit, it makes it difficult to lose data.
- **Snapshots** This is your picture into what changes you have made
- **Local Operations** This makes it easier to retrieve data and files since it is on your local disk. You don't have to wait for a server to load what you're looking for. Plus you don't have to worry about working online since it's saved locally.
- **States** Git files have three main states:
  + **Committed** Data is securely stored in a local database
  + **Modified** Files has been changed but not committed to the database
  + **Staged** Flagged a file's changed version to be committed in the next snapshot
  + [(Source)](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

## Setting up Git
-  You will need to make sure you have it downloaded and installed. After that initial process, you will need to "log in" to your GitHub through terminal so you're able to sync your projects and files. When you want to use a different user, you will have to reconfig your settings.
- Remember to have your text editor ready and also check settings after completion

## Set up a Git Repository
- **Importing** Type the following steps into Terminal to import [(Source)](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)
  + cd test *use this to switch directories*
  + git init
  + git add -.c
  + git add LICENSE
  + git commit -m "any message here"
- **Cloning** This is how to clone the file from GitHub onto local
  + git clone https://github.com/link
  + cd ___
  + code .

## Workflow
### The local Git repository has 3 components: [(Source)](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)
1. **Working Directory** The actual files reside here
1. **Index** The area used for staging
1. **Head** Points to the most recent commit

### Saving Changes [(Source)](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)
- **Tracked** Can be modified, unmodified, staged. They are the most recent file snapshot
- **Untracked** They are not in the most recent snapshot

## Remote Repositories
Teams typically use this to push and pull information and data from. It can let you work in a read/write or read only version.

## Keywords
- **GUI** Graphical User Interface. This is what makes the computer pretty and you can click around or move files easily.
- **git status** Command that lets you see a working directory. It let's you see if there are any mistakes
- **Committing a File** This is where you create your snapshot and add your notes about what changes you made.
- **Pushing Changes** When you push your repository this is how you get what is from your local computer, onto your GitHub repo. This is the sync.
- **git stash/git stash apply** This temporarily removes changes so you have a clean working directory. The latter brings the hidden changes back


[<== Back](https://simoneodegard.github.io/reading-notes/)
