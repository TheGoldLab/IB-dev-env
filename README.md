# Docker-based development environment for information bottleneck analyses

## What this repo is used for
This repository contains the specification files required to construct a docker image that can run information bottleneck analyses on (hopefully) any computer. When starting a new project repository that will require information bottleneck analyses, simply copy all of the files here (except this README.md) into the top level folder. Alternatively, begin your new project repository by forking this repository. Using VS Code, you will then be able to work on your project using the development environment contained within the docker image.

## Requirements
- VS Code installed on your computer
    - VS Code Dev Containers extension
- Docker Desktop installed on your computer
- Git installed  and set up on your computer

## Workflow
1. Open your project folder (containing the files within this repo) in VS Code
2. Open the command window by pressing Ctrl/Cmd + Shift + P or by clicking on the top search bar and going to "Show and Run Comands >".
3. Type in the command "Dev Containers: Reopen Folder in Container" and press enter (when you begin typing any part of this command, the window should suggest it)
4. VS Code will begin the process of opening the folder in the container specified by the files in this repository. If it is the first time you are doing this, it may take a while for the container to be built. After the first time, it should open quickly.
5. You can now edit and run code as you would normally.
6. You can also use git via VS Code while inside the dev container.

Note: Once you are in the container, you will need to "reinstall" any VS Code extensions you normally use. This is because you are now using a different instance of VS Code that is within your container. Making sure you have the extensions you need "reinstalled" should fix any difficulties you may encounter.