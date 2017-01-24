# CodingConventions

This project contains the coding convetions for the source code related to the cooperate project. The conventions are stored as checkstyle rules to be easily usable in coding projects.

## Setup Sonar Lint
* Install Sonar Lint from the Eclipse Marketplace.
* Restart Eclipse.
* Show the view `SonarQube Servers`.
* Click `Connect to a SonarQube server...`.
* Enter the URL `https://mammutbaum36.fzi.de/sonar/`.
* Enter your SonarQube username and password.
* Click `Finish`.
  
## Setup New Project
### Setup Formatter and Clean Up
If you create a new project, set the Formatter and Clean Up rules by applying the following steps.
* Checkout this project.
* If not already done, import the Formatter and Clean Up rules under `Window` -> `Preferences` -> `Java` -> `Coding Style` -> `Formatter` and -> `Clean Up` by pressing `Import...` and selecting the file from this repository.
* From the context menu of the new project, open its preferences.
* Under `Java Code Style` -> `Formatter` and -> `Clean Up` select `Enable project specific settings` and select the profiles imported in the previous steps.
* Under `Java Editor` -> `Save Actions` select `Enable project project specific settings` and `Perform the selected actions on save`. Activate `Format source code`, `Organize imports` and `Additional actions`.
### Setup SonarLint
* Run a first SonarQube analysis on the project by pushing to the server.
* From the context menu of the new project select `SonarLint` -> `Bind to a SonarQube project`.
* Make sure the new project is selected.
* Click `Auto bind selected projects`.
* Click `Finish`.

## Credits
The coding conventions are based on the coding convetions of the [SPLevo tool chain](https://github.com/kopl/SPLevo/tree/master/Releng/org.splevo.releng.codeconventions) licensed under EPL 1.0 and initially created by Benjamin Klatt.
