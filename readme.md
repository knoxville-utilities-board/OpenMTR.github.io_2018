# Readme
This is the documentation site for the OpenMTR software. This site will be used to record the process of its development and operation.

## Installation
It may be necessary to install and run a local version of this website for the purposes of development and testing, to do so follow these steps.
1. Set up [Docker](https://store.docker.com/editions/community/docker-ce-desktop-windows)
   1. Download and install from the link above.
   2. Be prepared to restart the computer multiple times before docker is ready to go.
   3. Once docker is installed and running, open the settings menu from the icon in the notification area.
   4. In the "Shared Drives" section make sure that the volume where your repository is located is checked.
2. Clone the git repository
   1. If you haven't already, install some method of git management such as git bash, WSL, github desktop, etc.
   2. Use `git clone git@github.com:OpenMTR/OpenMTR.github.io.git %userprofile%\git\OpenMTR.github.io` replacing `%userprofile%\git\OpenMTR.github.io` with a different directory if you don't want to put the repository there.
3. Navigate to the repository in the command line and run `docker-compose.exe up`
4. You're done! You can open a web browser and navigate to <http://localhost:4000> to test the site.
   * To stop the server press `Ctrl^C` into the command prompt and/or close the command prompt window.
   * To start the server again repeat step 3.