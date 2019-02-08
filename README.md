# Assembling necessary information etc to teach git at RUsers group

## Workshop layout:


1. Introduction to Git
    * [Repository first method](https://happygitwithr.com/new-github-first.html)
    * Create a new repository on Gitlab.cscscience.ca
    * Add an SSH key to that repository
      * Check if you have an SSH key on rstudio
        * Git pane
        * More > Shell
        * ```ls ~/.ssh```
      * If so, yay! If not:
        * Open a bash terminal: locally or go to jupyter.cscscience.ca 
        * Connect to the RStudio server: ```ssh rstudio```
        * Create a ssh key: ```ssh-keygen -t rsa -C "YOUR-EMAIL@canada.ca"```
        * Verify it: ```ls ~/.ssh```
        * Print your public key and copy it: ```cat ~/.ssh/id_rsa.pub``` (ctrl+insert or shift+right click in jupyter)
      * User icon > Settings > SSH Keys - Paste and save
    * Sign in at rstudio.cscscience.ca
    * Create new project (include git repository) in RStudio
    * Make a new R Markdown file and save it as README.md
    * First commit
    * Make changes
    * Second commit
    * Add remote origin via git shell:
      * Git pane
      * More > Shell
      * git remote add origin git@gitlab.cscscience.ca:**USERNAME**/git-example.git

2. 



