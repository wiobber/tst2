# rumbas-codespaces-template
This template can be used to easily run rumbas in Github Codespaces or VSCode with Dev Containers Extension.

## Github Codespaces

This setup allows you to run rumbas without needing to install anything.

- Create a repository from this template by clicking on the green 'Use this template' button and choosing the 'Create a new repository' option.
  - Place it under your personal account, choose a name and whether it should by a private or public repo.
- Github will show your new repo
- Click on the green 'Code' button, use the codespaces tab and click on the plus icon or the green 'Create codespace on main' button.

## Visual Studio Code

This setup allows you to run rumbas on your own computer in VSCode with the Dev Containers Extension.

- Install Docker
- Install VSCode
- Install the Dev Containers Extension
- Place this repo on your computer:
  - Either Create a repository from this template by clicking on the green 'Use this template' button and choosing the 'Create a new repository' option and pull your fork (so you can also push your changes)
  - Or pull / download this repo (and you can't push your changes without setting up git or the remote)


## How does this repo work?

- The `.devcontainer` folder contains the configuration for the dev container
- The `.vscode` folder contains the configuration for VSCode
  - This includes tasks to execute rumbas commands.
  - These commands can be executed by pressing `Ctrl+Shift+P` and typing `Tasks: Run Task` and then selecting the task you want to run.
  - Alternatively, you can run the tasks by clicking on the buttons in the status bar.


The following extensions are used:
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) to host the rumbas output files
- [Task Buttons](https://marketplace.visualstudio.com/items?itemName=spencerwmiles.vscode-task-buttons) to put buttons in the status bar to run the tasks