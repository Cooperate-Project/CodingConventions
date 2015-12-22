# CodingConventions

This project contains the coding convetions for the source code related to the cooperate project. The conventions are stored as checkstyle rules to be easily usable in coding projects.

## Setup Eclipse
* Install Checkstyle from Eclipse Marketplace
* Checkout this project into your workspace
* Configure Java code formatting via _Window - Preferences - Java - Code Style_
  * Under _Formatter_ import the `cooperate-code-formatter.xml` configuration
  * Under _Cleanup_ import the `cooperate-cleanup-rules.xml` configuration
* Checkstyle will be configured for each project individually
  
## Setup Projects
If you create a new project, activate checkstyle checks for it by applying the following steps
* Activate checkstyle for the project via context menu
* Copy the `.checkstyle` file from this repository into the root folder of the project

## Credits
The coding conventions are based on the coding convetions of the [SPLevo tool chain](https://github.com/kopl/SPLevo/tree/master/Releng/org.splevo.releng.codeconventions) licensed under EPL 1.0 and initially created by Benjamin Klatt.
