# Statistical Computing course at UPF
 
This repository contains resources for the Statistical Computing course at UPF (taught by David Rossell)

- lectures: source files (.qmd) and compiled lectures (.html). Make sure to download both the .html and the _files directory (e.g. 01_Basics.html and 01_Basics_files) for proper visualization in your browser
- data: datasets
- code: auxiliary R code


INSTRUCTIONS FOR DOWNLOADING AND UPDATING THE COURSE MATERIALS

If you're new to GitHub, the easiest option is to click on "Code" and download a zip file with all materials. However, I do not recomment this as you would need to repeat the process every time that I upload the materials! Instead, I suggest that you install GitHub desktop and use that to keep the materials up to date. Please follow the steps below.

1. Install GitHub Desktop from https://desktop.github.com
2. After installing it, open GitHub Desktop on your computer
3. Click on "Clone repository". Go to tab "URL" and at "Repository URL" type "https://github.com/davidrusi/statcomp" (you can also change the default directory in your computer where the repository will be saved). Click on "Clone".
4. You now have a copy of the statcomp repository in your computer. You can open and view the files normally.
5. To update the repository to the latest contents I posted there, within GitHub Desktop click on "Fetch origin". If there are any updates you will see an option "Pull origin", click on it and you're done!

Important: if you edit the downloaded files in your computer, for example to add your own annotations,
there will be conflicts when you next try to update the notes with my latest changes at GitHub.
GitHub provides a simple way to manage different versions of files, where you can keep your annotations and still update with my latest changes.

Step 1: In GitHub Desktop, click the Current Branch button and select New Branch. Name it my-notes.

Step 2: Select Current branch -> my-notes. Edit the files adding your desired comments, this will only affect your local my-notes branch.

Step 3: To download my updates:

  - Switch back to the main branch. You'll get a message "You have changes on this branch". Select "Leave my changes on my-notes", and click "Switch branch"

  - Click Fetch origin and Pull origin.

  - Switch back to the my-notes branch.

  - Go to Branch -> Merge into current branch and select main (or Branch -> Update from main)
  
  - Resolve any conflicts that may arise (GitHub Desktop will guide you through this process)