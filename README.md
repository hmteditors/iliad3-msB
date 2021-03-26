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
3. **Edit**: work on small pieces at a time, and validate frequently, so that if you encounter problems you can isolate them more easily.  **As soon as you validate a piece of work**, git it into your repository:
    - 

        

## Reference

See the [MID editing handbook](https://hcmid.github.io/tutorial2021/)