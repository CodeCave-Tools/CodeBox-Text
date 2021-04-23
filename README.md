#CodeBox Edit 2021

CodeBox Edit 2021 is an edited version of the open source Visual Studio Code project.

New features, UI Changes, and more will be coming to CodeBox Edit.

#Build:

These instructions are for mac and have not been tested for other platforms.

1) Clone the repository to your device
2) Open up a text editor of your choice and make a file called .yarnrc
3) Save the file in the repository clone
4) Enter the following inside .yarnrc

disturl "https://electronjs.org/headers"
target "12.0.4"
runtime "electron"

5) Install Node Version Manager (https://github.com/nvm-sh/nvm)
6) Use "nvm install 10.24.0" to install node 10.24.0
8) Use "nvm use 10.24.0" to use node 10.24.0
9) Install yarn using "npm install yarn --global"
10) CD to where you cloned the repository
11) Enter "yarn" in terminal
12) When done, run "yarn watch"
13) Do "./scripts/code.sh" (You may need to hit CMD + SHIFT + (.) before)
14) Close the editor and go back to terminal
15) run "npm run gulp vscode-darwin-x64-min"


#Extensions:
To use VS Code Extensions, you may need to get the extensions from github or a VS Code Installation and move it into the "Extensions" folder.

#Coming Soon

- New UI Changes
- Transition from Electron to a custom engine


#License

Copyright (c) Microsoft Corporation. All rights reserved.

Licensed under the [MIT](LICENSE.txt) license.
