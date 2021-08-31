# Git & GitHub Extension Pack

<!-- [![Visual Studio Marketplace](https://img.shields.io/visual-studio-marketplace/v/vscode-gitandgithub-pack?color=success&label=Visual%20Studio%20Marketplace)](https://marketplace.visualstudio.com/items?itemName=vscode-gitandgithub-pack)  -->

A collection of essential extensions to increase your productivity while working with Git and GitHub, created by [vinirossa](https://github.com/vinirossa)

## Included extensions
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
- [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
- [GitHub Codespaces](https://marketplace.visualstudio.com/items?itemName=github.codespaces)
- [Git Tags](https://marketplace.visualstudio.com/items?itemName=howardzuo.vscode-git-tags)
- [GitHub Pull Requests and Issues](https://marketplace.visualstudio.com/items?itemName=github.vscode-pull-request-github)
- [Open in GitHub, Bitbucket, Gitlab, VisualStudio.com !](https://marketplace.visualstudio.com/items?itemName=ziyasal.vscode-open-in-github)
- [Remote Repositories](https://marketplace.visualstudio.com/items?itemName=github.remotehub)

## Want to install only some extensions?
To install only some of the fonts, just edit the package.json file removing the unwanted extensionPack consequences and then follow the procedures below to install locally.

## How to develop and install locally
- Clone the repository
```bash
$ git clone https://github.com/vinirossa/vscode-gitandgithub-pack
```
- Install vsce
```bash
$npm install -g vsce
```
- Create the extension package
```bash
$vsce package
```
- Install the extension via the .vsix file
1. Open VS Code
2. Select Extensions from the menu
3. Click More > Install from VSIX...
4. Select the reloaded-extension-pack-x.x.x.vsix file
5. Click Reload Now to reload the VS Code

## For more information

* [See my Github](https://github.com/vinirossa)
