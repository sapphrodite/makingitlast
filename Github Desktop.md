## GitHub Desktop Workflow

First of all you, need to create a GitHub account to use with GitHub Desktop. Once you have Github Desktop installed, you can try completing the tasks in **"Create a Tutorial Repository"** or you can create your own repository from scratch in GitHub Desktop to get yourself familiarized with the main workflow of using the app. We know that this can be overwhelming for a beginner, so feel free to ask any of us for help!

Before you get started, set your default text editor in the GitHub Desktop app. (Note: Obsidian works using markdown formats and is not a plain text editor, so it will not be compatible. Some examples of text editors are Notepad, Notepad++ or Sublime.)
 
1. Click on **File > New Repository (Ctrl+N)** and create a new repository. This will be the folder in which your files exist.
2. You will be initially in the main (or master) branch of your repository. Whenever you work on a project you will be creating another branch so that your edits will not reflect on the main version of the project until you ready to publish those changes.
   These files are saved in the local version of the repository on your computer. In order to save this to the online repository stored on GitHub (origin), you need to hit the **Publish Repository** button. This will also create an instance of the repository on your GitHub account if you haven't already made one.
3. When you need to work on something, you can create a new branch by clicking **Current Branch (main) > New Branch** and naming it after whatever you are working on.  %% This is purposefully after the Publish step since otherwise it will create the GitHub repo with the new branch as default if they don't publish main first. %%
4. Once you have created a new branch, you can **start working on files** in the repository. (Eg: Create a random file, make a .txt and type in the lyrics to your favorite song, whatever!)
   Once you have made changes to your files, it should show up in the **Changes** tab in the left sidebar, and the particular changes will show up in the main window of the app. Make sure to hit the **Fetch origin** button to check the latest version of the remote GitHub repository stored online for any new changes.
5. When you are satisfied with your changes you can commit them to the branch. In the sidebar, you can select which files you want to add to the commit, name the commit, and then hit **Commit to 'branch-name'**, with or without a description of the changes. You can view your commit history in the **History** tab of the left sidebar.
6. All of these changes are still stored in the local version of the repository stored on your computer. In order to upload these changes to GitHub, click on **Publish Repository**.
7. When you are done working on this branch, you can merge these changes with the main branch by clicking **Preview/Create a Pull Request (Ctrl+Alt+P)**. Once the pull request is approved by the moderator, your changes will be reflected in the main branch of the project. Your branch can now be safely deleted.

**Reminder:** Make sure to Fetch Origin before committing/pushing commits.

**GitHub Desktop Keyboard Shortcuts:** Maybe add this too?

! Split GHD into GIt and GH sections