# Readme
This is the documentation site for the OpenMTR software. This site will be used to record the process of its development and operation.

## Required Software
* [Docker](https://store.docker.com/editions/community/docker-ce-desktop-windows)
* [Git](https://git-scm.com/)

## Getting Started
1. Ensure that docker can access the volume where your repository will be stored from its "Shared Drives" menu in settings
2. Use `git clone git@github.com:OpenMTR/OpenMTR.github.io.git %userprofile%\git\OpenMTR.github.io` replacing `%userprofile%\git\OpenMTR.github.io` with a different directory if you don't want to put the repository there.
3. Navigate to the repository in the command line and run `docker-compose up`
4. You're done! You can open a web browser and navigate to <http://localhost:4000> to test the site.
   * To stop the server press `Ctrl^C` into the command prompt and/or close the command prompt window.
   * To start the server again repeat step 3.
