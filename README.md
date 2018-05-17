GitLab code tree view
=====================

This is browser extension for Chrome / Firefox / Opera (and maybe IE as well :) ) that provides tree view for code in GitLab (must have for code reviews!). 

![Image of plugin](https://github.com/tomasbonco/gitlabtree/blob/master/screenshot.png)

## Installation

[Chrome](https://chrome.google.com/webstore/detail/gitlab-tree-view/pijacafkghdlolapcjpmiodgbnpinicn)
● [Firefox](https://addons.mozilla.org/firefox/addon/gitlab-tree-view/)
● [Opera](https://addons.opera.com/extensions/details/gitlab-tree-view)


## Contribution

Star, if you like :) Open an issue, if you find a bug or you miss something. Send a Pull Request when you decided to extend/fix (thank you for that!).


## How to build

First you need [NodeJS](https://nodejs.org/en/) installed. Then you need to install Typescript via:
```
npm install typescript -g
```
Now in Visual Studio Code you can run build task. If you prefer terminal:
```
tsc -p tsconfig.json
```

## Develop 

1. Clone repository to local directory. 

2. In chrome, open the Extension Management page by navigating to chrome://extensions.

- The Extension Management page can also be opened by clicking on the Chrome menu, hovering over More Tools then selecting Extensions.

3. Enable Developer Mode by clicking the toggle switch next to Developer mode.

4. Click the LOAD UNPACKED button and select this folder.

## License

MIT 
