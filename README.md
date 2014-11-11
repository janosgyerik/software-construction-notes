Software construction notes
===========================

General notes about software development, checklists, document templates

Checklists
----------

The content of the checklists directory comes from [Steve McConnell's Code Complete 2][1].
These checklists are publicly available on the author’s website.
You have to create an account to access the content but it’s FREE.

In every new project,
I recommend to grab a copy of these checklists,
commit to the project,
review and make edits in-place as you complete your requirements analysis and begin construction.

    # add a remote called "checklists", pointing to this repo
    git remote add checklists https://github.com/janosgyerik/software-construction-notes
    
    # fetch the repo contents
    git fetch checklists
    
    # get the "checklists" folder from the "master" branch
    git checkout checklists/master checklists
    
    # commit the files in your project
    #git commit -m 'added checklists files from code complete'
    # ^^^ Commented out, as you might want to move the directory first

[1]: http://www.cc2e.com/Default.aspx
