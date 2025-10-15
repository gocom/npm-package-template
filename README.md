npm Package Template
=====

[![MIT](https://img.shields.io/badge/license-MIT-green)](./LICENSE) ![TypeScript](https://img.shields.io/badge/types-TypeScript-blue)

> [!NOTE]
> This is a personal skeleton Node library template, supporting TypeScript. The template publishes the library as a
> package to npm registry  via GitHub actions, when a tag is added to the repository. GitHub Actions also use TypeDoc
> to generate API documentation from the code comments, which is published to a git branch named **docs**.

<!-- Add description here -->

🎺 Getting started
-----

To set up a repository using the template:

* [ ] Update [package.json](./package.json) with your package name, URLs and other details.
* [ ] If you can not use [trusted publishing](https://docs.npmjs.com/trusted-publishers), you can optionally add your `NPM_TOKEN` as a secret to the repository's or the organization's secrets.
* [ ] Add your package's typescript code to under the **src** directory. Default entrypoint is [src/index.ts](./src/index.ts), which exports will become part of the publicly exported API. The [src/internal.ts](./src/internal.ts) can be used to export internal code paths to the generated API documentation.
* [ ] Run tests using the instructions found in [CONTRIBUTING.md](./CONTRIBUTING.md).
* [ ] Add your license and copyrights to [LICENSE](./LICENSE).
* [ ] Update [CHANGELOG.md](./CHANGELOG.md).
* [ ] Update [CONTRIBUTING.md](./CONTRIBUTING.md).
* [ ] Update [SECURITY.md](./SECURITY.md).
* [ ] Update [sonar-project.properties](./sonar-project.properties) and add your `SONAR_TOKEN` to repository secrets, if you wish to use SonarQube Cloud integration.
* [ ] Update title, links, package name, usage instructions to [README.md](./README.md), and remove these **Getting started** instructions.
* [ ] Commit and push changes. Feel free to amend the first commit and overwrite the history, if you initialized the repository directly from the template. 🎉

⚡ Install
-----

Using npm:

```shell
$ npm install @gocom/npm-package-template
```

📖 Documentation
-----

See [API Docs](https://github.com/gocom/npm-package-template/blob/docs/main/Public/API.md).

🛠️ Development
-----

See [CONTRIBUTING.md](https://github.com/gocom/npm-package-template/blob/main/CONTRIBUTING.md).
