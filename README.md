This project is our work for developing the app for BYLD Innovations. We initially started with the base repo for OctoPrint. In order to edit the code, please make sure to git pull the repo and place it in your Site Packages folder, and rename to octoprint (replace the existing folder called this in Site Packages). To find where this is, you can try to delete OctoPrint with the command line command, and see what folder it is trying to delete from. 

What we have done so far is made page edits. Most of the "OctoPrint" text and their logo has been replaced with content for BYLD Innovations. The easiest way to maintain this is by running inspect element on the octoprint page (run it the same way as you normally would), and using Visual Studio Code's search function to find that line of code and making needed edits. 

This is successfully running on a Pi. In order to update the code on the pi, you need to ssh to the pi on a computer, and run git pull after any new commits have been made to the folder on GitHub. Git pull ensures all new commits have come in, and this will automatically update the code in the folder, provided it is cloned from the repo correctly. 

To push commits to GitHub, use either GitHub commands in the terminal or use Visual Studio Code's GitHub integration actions. Go to the GitHub tab, choose to stage which changes, add a commit message, and feel free to push directly to main or now. For any extensive code changes, maybe make a pull request and ask for review, but for now the changes we are making can be pushed to main directly. Just ensure it is working before doing it.