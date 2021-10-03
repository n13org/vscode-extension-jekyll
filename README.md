# Jekyll Snippets for Visual Studio Code

[Jekyll](https://jekyllrb.com) (a ruby based static page generator) snippets for [Visual Studio Code](https://code.visualstudio.com) which is published on [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=kargware.vscode-extension-jekyll-kw) with the name `vscode-extension-jekyll-kw`.

![Image vscode-extension-jekyll-kw](images/vsce-jekyll-kw-128x128.png)

The code of the extension is hosted on [GitHub n13org/vscode-extension-jekyll](https://github.com/n13org/vscode-extension-jekyll)

See all extensions from Kargware on the [Marketplace](https://marketplace.visualstudio.com/manage/publishers/kargware)

## Create a Release / Publish to Marketplace

Create a tag which starts with a `v`, e.g. `v0.0.1`. Then the [CI pipeline](.github/workflows/ci.yml) will execute the `publish` job.

```sh
git tag v0.0.0 HEAD
git push --tags
```

The tag will also be created when a "new release" is created on the [GitHub Release Website](https://github.com/n13org/vscode-extension-jekyll/releases) -> "draft a new release" -> Create a tag on publish.
