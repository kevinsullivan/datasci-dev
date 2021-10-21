# Data Science Development Image for Docker

A development environment based on Python and major data analytics and machine learning libraries. Once your environment is running, open a terminal, cd
into the dev directory, and issue this command to activate a virtual environment providing all the major data science libraries: 

``` sh
source bin/activate
```

To get there, just follow the ...

## ... the Yellow Brick Road

- Update your operating system:
  - If MacOS: Be sure your OS is up-to-date.
  - If Windows:
    - If you already have Windows Pro, Education, or Enterprise, skip the remaining steps, else continue.
    - Windows 10 Home won't do: You must update to Windows 10 Professional, Enterprises, or Education
- Install git on your computer (if you know you already have it, skip this step):
  - Windows: https://git-scm.com/download/win
  - OSX/MacOs
    - Find and run the Terminal program
    - Enter the following command in the window: xcode-select --install
    - When it asks, go ahead with the standard install process. 
- Have a GitHub account. Create one if necessary. It's free: <https://github.com/>
- Install Docker Desktop: <https://www.docker.com/products/docker-desktop>. It's free. If you have it, you *must* update it to the current version.
- Install VSCode: <https://code.visualstudio.com/download>. It's free.
- Launch Docker Desktop and watch for it to complete its start-up procedures. While it starts up, continue to the remaining instructions that follow here.
- Use GitHub to fork this repository now. How? Here:
  - Be logged in to your GitHub account.
  - Visit *this* repository on GitHub (which is probably where you're reading this) while logged in to your GitHub account.
  - "Fork" this repo using the *Fork* button in the upper right corner. This will create a clone of this repository (a copy that remembers where it came from) under your GitHub account. We recommend that you should change the name of your GitHub repo (hit the pencil icon next to its name on GitHub to start editing it) to reflect the nature of your project. Doing this will avoid conflicts should you try to do this procedure again.
  - Visit your GitHub web page to confirm that you now own a clone of this repository. Click to view the repository.
  - Select the green Code button, then HTTPS, then copy the URL that is provided. This will be the GitHub URL of your newly forked copy of the respository.
- Start up your new environment
  - Start a *new* VSCode window.
  - Using the "extensions" tool (four squares with one out of place on the left of your VSCode screen), search for and install the *Remote Containers* extension. (The green icon at the lower left gets you the available Remote Containers commands direclty.)
  - Use CTRL/CMD-SHIFT-P to bring up the VSCode command palatte.
  - Search for and select *Clone Repository in Container Volume*
  - Paste in the GitHub URL of your new clone as the argument.
  - If you're asked to choose something, select *named repository* (and give a name, .e.g., datasci_dev).
- Now wait while your environment is built. It will take much longer on the initial install than on future startups. You can click in the lower right to see the build process if you want. Wait for the building activity to end and for your environment to "boot up" before taking any further actions. There is a status bar at the bottom of the screen that reflects build processes status and activities. Note that even after the OS and applications are installed and the terminal says you're done, VS code packages continue to be installed. Wait for the environment to be fully installed, as indicated by various display widgets on your screen.
- Check to see that things seem to be working (e.g., launch terminal)
- Configure git on your new containerized operating system
  - Open a new Terminal window in VSCode
  - Issue the following commands, filling in your details as appropriate
    - git config --global user.name "Your Name Here"
    - git config --global user.email "your@email.here"
- You may now work in and exit from VSCode as you wish. VSCode will let you re-open this project when you're ready to work on it again.

You now have, up and running, the potentially coolest data science environment ever. You're done!

## If you find a problem or an opportunity

If you think you've found a problem, revisit this GitHub page and report an Issue. Better yet, if you then fix the problem on your own clone of this site, commit and push it to your GitHub repo then send us a *Pull Request*. That will will send us your changes to review and possibly merge them into our main repository, whereupon they will then become available for anyone else to *Pull*, as well.  

## Legal and contact

- Acknowledgement: This work is supported in part by the National Science Foundation under grant (Award Abstract) #1909414 to Kevin Sullivan and Sebastian Elbaum.
- Copyright: © 2021 by Kevin Sullivan.
- Primary and Contact Author: Kevin Sullivan. UVa CS Dept. sullivan@virginia.edu.
