# alfred_workfloww

This project keeps my Alfred 3 workflows for current use. 

To install a wokflow, only to download the workflow file and then double-click on the workflow you want to install into your Alfred. I currently have the following workflows:

## Tyme2
Tyme2 is time tracking tool to help me to track my time spent. You need to get [Tyme2](https://www.tyme-app.com) from App Store.

The following are the keywords defined:

| Command           | Description |
| ----------------- | ----------- |
| t{project_name} | Start to track the time for the selected task of project |
| ts | Stop to track the time for the current tracking task |

## UMLet
UMLet is a UML tools to help draw UML diagrams quickly and export UML diagrams to pdf, jpg, svg files. This workflow is used to launch UMLet quickly.

Before using UMLet, you need to install Java SDK via homebrew. I have cask installed already, so for me it’s a simple matter of running:

```
brew cask install java
```

Then, you need to download and extract it from [UMLet](http://www.umlet.com) site. And, you need to export the installation path to your zsh profile.
```
echo 'export UMLET_HOME="/Users/kurt/Software/Umlet/"' >> ~/.zshrc
```

The following are the keywords defined:

| Command           | Description |
| ----------------- | ----------- |
| umlet | Launch UMLet via Java |

## Evernote
Alfred 3 workflow to search and create notes in Evernote.

[Original link](https://www.alfredforum.com/topic/840-evernote-9-beta-2-for-alfred-3-search-create-append-set-reminders-all-within-alfred/)


## Recent Items
Workflow to display recent Finder files and folders featuring:
* 5 default categories
* 2 custom categories
* Favorites, including a file action
* Keywords and hotkeys for Favorites and all categories apart
* Interaction with Open/Save dialogs and Finder Go To Folder
* Preview, reveal, open or use Alfred file actions

[Original link](https://www.alfredforum.com/topic/713-recent-items-42-for-alfred-3-docs-folders-apps-custom-categories-favorites-interaction-with-opensave-dialogs-and-more/)

## Top Processes
Two major features:
* List/Kill Top Processes by Memory/CPU/IO Usage
* (not working now) Get a glance of system status including internal battery, fan speed, CPU/GPU Temperature, bluetooth battery, disk capacity, etc.

[Original link](https://www.alfredforum.com/topic/1077-top-processes-based-memory-or-cpu-usage-workflow/)
