## {{ UNRELEASED_VERSION }} - [{{ UNRELEASED_DATE }}]({{ UNRELEASED_LINK }})

## v3.0.0 - [November 19, 2024](https://github.com/lando/code-sign-action/releases/tag/v3.0.0)

### **BREAKING CHANGES**

* Added `inputs.certificate-id` for use when using non-Apple signing certs
* Added `inputs.signtool` to explicitly use a particular tool but not usage is not recommended
* Dropped support for `linux`, it never really worked and wasn't ever needed, it now errors on Linux
* Improved `inputs.file` to correctly handle `relative` and `absolute` paths
* Refactored code to be more pluggable in the event we want to support additional future signing methods

## v2.2.0 - [May 3, 2024](https://github.com/lando/code-sign-action/releases/tag/v2.2.0)

* Added support for using DigiCert KeyLocker to sign Windows and Linux packages. [#7](https://github.com/lando/code-sign-action/pull/7)

## v2.1.1 - [June 17, 2023](https://github.com/lando/code-sign-action/releases/tag/v2.1.1)

* Switched release flow over to [@lando/prepare-release-action](https://github.com/lando/prepare-release-action)

## v2.1.0 - [April 27, 2023](https://github.com/lando/code-sign-action/releases/tag/v2.1.0)

* Added support for either `altool` or `notarytool` for notarizations
* Switched `set-output` and `save-state` to new `$GITHUB_OUTPUT` and `$GITHUB_STATE`. See [this](https://github.blog/changelog/2022-10-11-github-actions-deprecating-save-state-and-set-output-commands/)
* Updated to use new [`@lando/notarize-action@v2`](https://github.com/lando/notarize-action)

## v2.0.1 - [April 13, 2022](https://github.com/lando/code-sign-action/releases/tag/v2.0.1)

* Added `color` and `icon` to GitHub Marketplace listing

## v2.0.0 - [April 13, 2022](https://github.com/lando/code-sign-action/releases/tag/v2.0.0)

* First release

