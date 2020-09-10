(DEVELOP) C# Compiler Settings For Unity
===

**NOTE: This branch is for development purposes only.**  
**To use a released package, see [Releases page](https://github.com/mob-sakai/CSharpCompilerSettingsForUnity/releases) or [default branch](https://github.com/mob-sakai/CSharpCompilerSettingsForUnity).**


## How to develop this package

1. Fork the repository and create your branch from `develop`.
3. Open the project and click `Open Sesame > Develop Mode`
4. Develop the package
5. Click `Window > Generals > Test Runner` to test
6. Commit with [Angular Commit Message Conventions](https://gist.github.com/stephenparish/9941e89d80e2bc58a153)
7. Create pull request

For details, see [CONTRIBUTING](https://github.com/mob-sakai/CSharpCompilerSettingsForUnity/blob/upm/CONTRIBUTING.md) and [CODE_OF_CONDUCT](https://github.com/mob-sakai/CSharpCompilerSettingsForUnity/blob/upm/CODE_OF_CONDUCT.md).


## How to release this package

When you push to `preview`, `master` or `v1.x` branch, this package is automatically released by GitHub Action.

* Update version in `package.json` 
* Update CHANGELOG.md
* Commit documents and push
* Update and tag upm branch
* Release on GitHub
* ~~Publish npm registory~~

Alternatively, you can release it manually with the following command:

```bash
$ node run release -- --no-ci
```