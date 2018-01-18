# RMarkdown exercise

This is the `README` for the intro to RMarkdown (and use of the R Server with Git) exercise.

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
3. Check-out this repository (still all in the terminal):
  - make sure you are at the top level of your folder structure by checking that the command prompt shows `[YOURUSERNAME@rstudiogeo ~]$` with the `~` indicating that you are at the top level of your home directory - if you are in a subdirectory, execute `cd ..` until you reach the above prompt
  - at the top of this repository click on the green **Clone or download** button and copy the shown link to the clipboard
  - in your R Server terminal, type `git clone ` and paste the copied link right after (so it says something to the effect `git clone https://github.com/......git`), then execute the commmand (this creates a local copy of your GitHub repository)
  - 

## Exercise

Fill out the questions in the [`assignment.md`](assignment.md) (the [video tutorial](https://youtu.be/bRkpm1LTpkY) will be a useful starting point but note that the assignment questions are slightly different than those covered in the tutorial).
