![Icon](https://github.com/geeklearningio/gl-vsts-tasks-yarn/blob/master/Extension/extension-icon.png)

# Yarn Build and Release Tasks

![cistatus](https://geeklearning.visualstudio.com/_apis/public/build/definitions/f841b266-7595-4d01-9ee1-4864cf65aa73/77/badge)

[Yarn](https://yarnpkg.com/) is Facebook's npm alternative. It is the fast, reliable and secure dependency management.
This extension brings the power of Yarn to Visual Studio Team Services Build and Release Management. It enables using yarn with the official npm registry or any registry you like such as Myget or [Visual Studio Team Services Package Management](https://marketplace.visualstudio.com/items?itemName=ms.feed#).

[Learn more](https://github.com/quixit/gl-vsts-tasks-yarn/wiki) about this extension on the wiki!

## Tasks included

- **[Yarn installer](https://github.com/quixit/gl-vsts-tasks-yarn/wiki/Yarn-Installer)**: Installs Yarn
- **[Yarn](https://github.com/quixit/gl-vsts-tasks-yarn/wiki/Yarn)**: Execute Yarn

## To contribute

1. Globally install typescript and tfx-cli (to package VSTS extensions): `npm install -g typescript tfx-cli`
2. From the root of the repo run `npm install`. This will pull down the necessary modules for the different tasks and for the build tools.
3. Run `npm run build` to compile the build tasks.
4. Run `npm run package -- --version <version>` to create the .vsix extension packages (supports multiple environments) that includes the build tasks.

## Known Issues

Please refer to our [wiki page](https://github.com/quixit/gl-vsts-tasks-yarn/wiki/Known-Issues)

## Release Notes

Please refer to our [release page](https://github.com/quixit/gl-vsts-tasks-yarn/releases)

## Contributors

This extension was created by Geek Learning, with help from the community.
It also uses some foundation code from [Azure pipelines Tasks](https://github.com/Microsoft/azure-pipelines-tasks).
It has been updated by [Jonathan Bruce](http://github.com/Quixit) as the original repository has been unmaintained for many years.

## Attributions

- [Yarn by Yarn Contributors](https://yarnpkg.com/)
