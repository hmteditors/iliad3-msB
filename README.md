# iliad3-msB

Editing book 3 of the Iliad in the Venetus B manuscript.

Image citation tool for folios [40 verso - 41 recto](http://www.homermultitext.org/ict2/?urn=urn:cite2:hmt:vbbifolio.v1:vb_40v_41r).


## Editing in this repository


1. **Always** start from a clean clone of the repository, and delete your local copy at the end of your work session.
    - In VS Code, from `View/Command Palette...` menu (or `cmd-shift-p`), find `Git: Clone`, and paste in the URL of this repository https://github.com/hmteditors/iliad3-msB/
    - Note where you cloned it (e.g., on your Desktop): you'll need to find this in your Pluto notebook
2. **Before you start editing**, open your validating notebook:
    - open Julia, and enter `using Pluto; Pluto.run()`  This will open a browser window on your Pluto notebook server. 
    -   In the box `Open from a file:`, find, inside your repository's `notebooks` folder the file named `midvalidator-VERSION.jl`.  This will take a long time to build.
3. **Edit**: work on small pieces at a time, and validate frequently, so that if you encounter problems you can isolate them more easily.  **As soon as you validate a piece of work**, use VS Code's "source control" mode to get it into your repository:
    1. select the source control icon.  Here, it shows two files have been modified. <img src="https://raw.githubusercontent.com/HCMID/tutorial2021/main/imgs/sourcecontrolmode.png" width="150">.  Click on the `+` icon next to each name.  (You may need to hover over the file name or widen the column to see the `+`.)
    2. The files now show up in the list of "Staged Changes. <img src="https://raw.githubusercontent.com/HCMID/tutorial2021/main/imgs/staged.png" width="150">
    3. Click the ✔️ icon to commit your changes. If you haven't arleady filled in a commit message, you'll be prompted to give a brief message describing your changes.  <img src="https://raw.githubusercontent.com/HCMID/tutorial2021/main/imgs/commit.png" width="150"> This records your changes in your local clone of the repository.
    4. Finally, choose "Push" from the drop-down ellipsis menu. <img src="https://raw.githubusercontent.com/HCMID/tutorial2021/main/imgs/push.png" width="150">.  Your changes are now securely back on github.  If you want to be sure, open your web browser on the repository, and look for your commit message.
4. **Cleaning up**.  Quit VS Code and Julia, close a few dozen browser tabs, and *throw away* the local clone you made of your repository.

        

## Reference

See the [MID editing handbook](https://hcmid.github.io/tutorial2021/) for more details on installing software and configuring your computer for this workflow.