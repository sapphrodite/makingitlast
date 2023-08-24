g# How to get started contributing
here is the part where we'd put some grandiose intro sentence, and talk about how in a few short steps, you too can be a part of something greater! All you have to do is install a couple things, then it's your path to greatness! 

## What Is Markdown?
We work exclusively using markdown files, the same format that Discord, GitHub, and many other applications use. Markdown's greatest strength is its ability to provide support for pretty formatting such as tables and subheadings while remaining a free and easily understandable plaintext format. Using a plaintext format rather than proprietary software such as Google Docs or Microsoft Word has numerous advantages, the most important of which is freedom - we are able to use any tool we like to do our work!. 

## What Is Git?
Instead of traditional cloud service such as dropbox (explain reasons here)
todo - explain what a version control system *is*

The most common Git service is Microsoft's cloud-based platform called Github. While Git only comes with a minimal command-line interface that looks like it belongs in the MS-DOS days, GitHub provides GitHub Desktop as a more user-friendly graphical alternative. We use this to help people contribute to this project even if they're not familiar with using command line interfaces

Here are the most important concepts you need to understand to get started with Git:
- A Git repository, in the simplest sense, is similar to a shared folder. However, unlike auto-synchronizing services such as Google Docs, a Git repository must be manually synchronized with the central repository. While this might seem like a disadvantage at first, it's actually one of Git's greatest strengths when utilized properly, as it gives you full control over revision history. 
- The abstract concept underlying Git is that of delta, the mathematical representation of change over time. By tracking only the differences between subsequent revisions, the entire recorded history of a file can be stored with a minimum amount of disk space. TODO: fix that god awful first sentence
- A commit is like a snapshot of our repository at a given time. TODO: talk about how this factors into people's workflows
- Branches are one of Git's most powerful features, as they allow for a large amount of people to simultaneously perform work on the same repository.  TODO: talk about master branch, diversions in history, merges, etc

!-- Important Distinction: Git is the protocol, GitHub is the company! They are not interchangeable. --!

## Github Desktop
If you're already familiar with Git or Github Desktop, skip to the next section. Otherwise [download Github Desktop here](https://desktop.github.com/) and read up on how to [get started with Github Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/overview/getting-started-with-github-desktop). This part can be rather confusing for beginners, so If you have any questions, please ask us - we're always happy to help!

1. Create a GitHub account, and connect it to GitHub Desktop
2. Complete the tasks in the "Create a Tutorial Repository" section.
3. **WARNING:** ALWAYS sure to Fetch Origin before committing/pushing commits.

## Obsidian
We use Obsidian as our primary markdown text editor, although you're free to use any editor you like.
Your next step is to  [download Obsidian](https://obsidian.md/download). If you're familiar with Obsidian or the markdown format in general, feel free to skip ahead. If you want to learn more about the markdown format, the [Obsidian Markdown Guide](https://help.obsidian.md/Editing+and+formatting/Editing+and+previewing+Markdown) is a great reference. if you have any other questions, please ask us or check out the [Obsidian Help Page](https://help.obsidian.md/Home).

## Putting it all together!
To start contributing, just follow these steps once you're familiar with both Obsidian and Git:
1. **Send your GitHub username to @sapphrodite** and ask her to add you to the repository. Once you are approved, you should receive an email from GitHub asking you to accept the invite.
2. If you have used Git or GitHub Desktop before, amazing! Otherwise, check the **GitHub Desktop Workflow section** to learn how to use Git and GitHub Desktop before heading on to the next steps. 
3. Clone our repository. If you're using GitHub Desktop, go to **File > Clone repository (Ctrl+Shift+O)**. Under the URL tab, type in `sapphrodite/makingitlast` for the **Repository URL**, and the desired folder on your computer for the **Local Path**. Hit Clone. Git will now automatically copy all the files you need onto your computer.
4. In Obsidian, go to **File > Open vault...** and click on **Open folder as vault**. Now navigate to the folder containing your Git repository and hit Select Folder. Your files are now ready for you to edit in Obsidian!