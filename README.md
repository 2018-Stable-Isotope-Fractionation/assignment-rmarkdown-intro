# Introduction to RMarkdown / RStudio Server

This is the `README` for the intro to RMarkdown and use of the R Server with Git exercise.

## Setup

1. Login: log into the [R Server](http://moab.colorado.edu:8787) with your username and password
2. Setup Git:
  - find the Terminal tab at the bottom of the IDE (interactive development environment). This is a simple linux command prompt.
  - execute the following commands (with the proper replacements) to set up your github credentials:
  - `git config --global credential.helper store`
  - `git config --global credential.https://github.com.username YOURGITHUBUSERNAME`
  - `git config --global user.email "YOUREMAIL"`
  - `git config --global user.name "YOURNAME"`
  - double check that the configuration is all correct by executing `git config --list`
3. Check-out this repository:
  - if you have an open project in your RStudio Server, close it by choosing **Close Project** from the Project dropdown button in the upper right corner (it should say `Project: (None)` afterwards)
  - switch back to the terminal tab and make sure you are at the top level of your folder structure by checking that the command prompt shows `[YOURUSERNAME@rstudiogeo ~]$` with the `~` indicating that you are at the top level of your home directory - if you are in a subdirectory, execute `cd ..` until you reach the above prompt
  - at the top of this repository's GitHub page, click on the green **Clone or download** button and copy the shown link to the clipboard
  - in your R Server terminal, type `git clone ` and paste the copied link right after (so it says something to the effect `git clone https://github.com/......git`), then execute the commmand (this creates a local copy of your GitHub repository and you should see the new folder in your directory tree in the **Files** tab on the right)
4. Load project:
 - click the blue Project dropdown button in the upper right corner (underneath your user name and the red power button) and chose **Open Project**
 - navigate to the new project folder and selec the `project.Rproj` file inside it
 - this will load a new RSession rooted in the new project folder (you will see this project now selected in the Project dropdown)

## Assignment

1. Markdown continued: open the `markdown.Rmd` file in your R Server session and complete the exercises
2. RMarkdown: complete the exercises in `markdown.Rmd` (don't forget to commit your changes)
3. Isotopia: complete the exercises in `isotopia.Rmd` (don't forget to commit your changes)
4. Submit: push all your changes to GitHub and submit your exercise by the usual way: file a pull request on GitHub to merge the `master` into the `submit` branch (i.e. base: `submit`)

## Additional Notes

If you want to synchronize a repository also with your local desktop, you can do so easily using [GitHubDesktop](github.md).


## Resources

 - [RStudio cheat sheet](https://github.com/rstudio/cheatsheets/raw/master/rstudio-ide.pdf)
 - [RMarkdown cheat sheet](https://github.com/rstudio/cheatsheets/raw/master/rmarkdown-2.0.pdf)
 - [Latex math cheat sheet](https://users.dickinson.edu/~richesod/latex/latexcheatsheet.pdf)
