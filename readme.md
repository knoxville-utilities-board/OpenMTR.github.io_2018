---
layout: default
title: ReadMe
permalink: /readme/
---

# OpenMTR.Github.io
This is the documentation site for the OpenMTR software. This site will be used to record the process of its development and operation.

## Running Site Locally

### Docker

#### Required Software
* [Docker](https://store.docker.com/editions/community/docker-ce-desktop-windows)
* [Git](https://git-scm.com/)

#### Getting Started
1. Ensure that docker can access the volume where your repository will be stored from its "Shared Drives" menu in settings
2. Use `git clone git@github.com:OpenMTR/OpenMTR.github.io.git %userprofile%\git\OpenMTR.github.io` replacing `%userprofile%\git\OpenMTR.github.io` with a different directory if you don't want to put the repository there.
3. Navigate to the repository in the command line and run `docker-compose up`
4. You're done! You can open a web browser and navigate to <http://localhost:4000> to test the site.
   * To stop the server press `Ctrl^C` into the command prompt and/or close the command prompt window.
   * To start the server again repeat step 3.

### Ruby

#### Required Software
* [Ruby](https://github.com/oneclick/rubyinstaller2/releases/download/rubyinstaller-2.4.3-1/rubyinstaller-2.4.3-1-x64.exe)
* [Git](https://git-scm.com/)

#### Getting Started
1. After installing ruby you will need to add an entry to your system path.
    1. Search for "environment variables" in the start menu search bar, or alternatively navigate to the control panel, select **_System_**, then **_Advanced System Settings_**, and navigate to the **_Advanced_** tab.
    2. In **_Environment Variables_** there are two lists of variables: the top list is for only the active user, and the bottom is for every user on the machine. Find the **_Path_** variable in whichever is more appropriate and select **_Edit_**
    3. Select **_New_** and enter ruby's bin folder, by default `C:\Ruby24-x64\bin`
    4. Reboot
2. Open the command prompt
3. If you didn't already run `ridk install` through the ruby installer you will need to do so yourself and install all three options presented. When that is done use `Ctrl^C` to get back out to the command prompt.
4. Run `gem install jekyll bundler`
5. Using `cd` navigate to the repository where you cloned the site
6. Run `bundle install`
7. Run `bundle exec jekyll serve`
    * That's it! To stop the server use `Ctrl^C`
    * To start the server again repeat steps **5** and **7**
