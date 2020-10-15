<img src="https://mehmetcangulesci.com/ss.png" alt="Kitten" title="A cute kitten" width="300" height="80" />

![user] ![licence]  ![code_language] ![build] ![version]  ![last_commit]  ![code_size]

[user]:https://img.shields.io/badge/made%20by-mehmetcangulesci-blue.svg
[licence]:https://img.shields.io/github/license/mehmetcangulesci/hello-npm-library
[code_language]:https://img.shields.io/github/languages/top/mehmetcangulesci/hello-npm-library
[build]:https://img.shields.io/github/workflow/status/mehmetcangulesci/hello-npm-library/Node.js%20Package?event=push
[version]:https://img.shields.io/github/package-json/v/mehmetcangulesci/hello-npm-library
[last_commit]:https://img.shields.io/github/last-commit/mehmetcangulesci/hello-npm-library/main
[code_size]:https://img.shields.io/github/languages/code-size/mehmetcangulesci/hello-npm-library

## Description

This is tell us how to use private libraries in personal need or organizational level, written in Javascript, have been created with [GitHub Package Registry](https://github.com/features/packages) and [GitHub Actions](https://github.com/features/actions).
GitHub Package Registry is used for package registry and GitHub Actions are used for CI/CD process of source code.

## Setup

Before installing below rules must be followed:

1. Create Personal Access Token in GitHub User Developer settings.
2. Under the repo settings create new secret named ```NPM_TOKEN``` (you can give any name, but must ensure consistency with other codes) and give Personal Access Token value created previous step. 
3. You must have ```.npmrc``` file in current directory which has following lines.

```bash
//npm.pkg.github.com/:_authToken=${NPM_TOKEN}
registry=https://npm.pkg.github.com/mehmetcangulesci
```

### Install

```bash
# Specific Version 
npm install @mehmetcangulesci/hello-npm-library@1.0.0
```
```bash
# Latest Version 
npm install @mehmetcangulesci/hello-npm-library@latest
```

### Usage

```js
hello()
```

In Code Block

```js
const lib = require('@mehmetcangulesci/hello-npm-library');

lib.hello();
```

## Contributors

<table>
  <tr>
    <td align="center"><a href="https://mehmetcangulesci.com"><img src="https://avatars2.githubusercontent.com/u/17083968?v=3" width="50px;" alt=""/><br /><sub><b>Mehmetcan Gulesci</b></sub></a></td>
  </tr>
</table>

## Licence
[MIT](https://opensource.org/licenses/MIT) Licence 2020 Mehmetcan Güleşçi
