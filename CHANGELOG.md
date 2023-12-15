# Changelog

## [1.5.1](https://github.com/remarkablemark/release-please-extra-files-demo/compare/v1.5.0...v1.5.1) (2023-12-15)


### Features

* **github:** upgrade release-please-action to v4 ([0d6d9bf](https://github.com/remarkablemark/release-please-extra-files-demo/commit/0d6d9bf2e2e3bd17f2844bdd4fd049938f671e0b))


### Bug Fixes

* add packages to release-please-config.json ([2e8e00a](https://github.com/remarkablemark/release-please-extra-files-demo/commit/2e8e00a57281742ec139c5876e2c28dcd3dbe3bc))
* add version to .release-please-manifest.json ([c7ca387](https://github.com/remarkablemark/release-please-extra-files-demo/commit/c7ca3873ae397b1ef3b4864d295356a28aee7f25))
* create .release-please-manifest.json ([9ced392](https://github.com/remarkablemark/release-please-extra-files-demo/commit/9ced3924ca7fed7027da6cfd707f119c8d2e139b))


### Miscellaneous Chores

* release 1.5.1 ([9dd99be](https://github.com/remarkablemark/release-please-extra-files-demo/commit/9dd99be1e4a769ffe77b1e92b75538a9d9c02f76))

## [1.5.0](https://github.com/remarkablemark/release-please-extra-files-demo/compare/v1.4.0...v1.5.0) (2022-09-23)

### Features

- **github:** update pull-request-title-pattern ([5413aec](https://github.com/remarkablemark/release-please-extra-files-demo/commit/5413aecaf20fa84e375a56e8dab108835f6de4d9))

### Bug Fixes

- **github:** fix extra-files path in release-please.yml ([60e9204](https://github.com/remarkablemark/release-please-extra-files-demo/commit/60e9204d9db3b64f322d053e128aba27d4da8459))

## [1.4.0](https://github.com/remarkablemark/release-please-extra-files-demo/compare/v1.3.8...v1.4.0) (2022-09-23)

### Features

- **github:** enable manual workflow trigger for release-please.yml ([70e9df5](https://github.com/remarkablemark/release-please-extra-files-demo/commit/70e9df572122673880e5a820dd233c0c1a892e24))

## [1.3.8](https://github.com/remarkablemark/release-please-extra-files-demo/compare/v1.3.7...v1.3.8) (2022-09-23)

### Bug Fixes

- **github:** parse JSON string of pr object during checkout ([cc4a4a1](https://github.com/remarkablemark/release-please-extra-files-demo/commit/cc4a4a16ecf62b87efdc6de217addc6b8ebdccd0))

## [1.3.7](https://github.com/remarkablemark/release-please-extra-files-demo/compare/v1.3.6...v1.3.7) (2022-09-23)

### Bug Fixes

- **github:** continue job on error ([61cc7dd](https://github.com/remarkablemark/release-please-extra-files-demo/commit/61cc7dd83622bb4f77392644f9a74eebc7478f04))

## [1.3.6](https://github.com/remarkablemark/release-please-extra-files-demo/compare/v1.3.5...v1.3.6) (2022-09-23)

### Bug Fixes

- **github:** add missing release id so jobs don't get skipped ([6bde6ef](https://github.com/remarkablemark/release-please-extra-files-demo/commit/6bde6ef93f08d20edb6c2b18a0e446b5e7afd563))

## [1.3.5](https://github.com/remarkablemark/release-please-extra-files-demo/compare/v1.3.4...v1.3.5) (2022-09-23)

### Miscellaneous Chores

- trigger a patch release ([58e72ae](https://github.com/remarkablemark/release-please-extra-files-demo/commit/58e72aef76cb1e3e2e221b9bc5b541ac1264425e))

## [1.3.4](https://github.com/remarkablemark/release-please-extra-files-demo/compare/v1.3.3...v1.3.4) (2022-09-23)

### Bug Fixes

- **github:** check release pr and if previous jobs were skipped ([6e4f76c](https://github.com/remarkablemark/release-please-extra-files-demo/commit/6e4f76caa92d0d88db798b9e382516c296dbe787))
- **github:** fix expression check in release-please.yml ([a97c3be](https://github.com/remarkablemark/release-please-extra-files-demo/commit/a97c3bed06691e855b1de8f5a19737ba6a13b26d))
- **github:** replace invalid 'skipped' with release outputs pr ([fb45738](https://github.com/remarkablemark/release-please-extra-files-demo/commit/fb4573846e0b372d834496c35e2e30cf137830db))

## [1.3.3](https://github.com/remarkablemark/release-please-extra-files-demo/compare/v1.3.2...v1.3.3) (2022-09-23)

### Bug Fixes

- **github:** don't edit release PR if merged ([5cbd040](https://github.com/remarkablemark/release-please-extra-files-demo/commit/5cbd040af6a39bb83c25523beebde7780634a3e1))

## [1.3.2](https://github.com/remarkablemark/release-please-extra-files-demo/compare/v1.3.1...v1.3.2) (2022-09-23)

### Bug Fixes

- **github:** amend instead of creating a new commit ([e41de84](https://github.com/remarkablemark/release-please-extra-files-demo/commit/e41de84b39e628dba3fdd98f107ca7a4b84e4dfc))
- **github:** revert amend changes since it broke Release Please ([9de8d22](https://github.com/remarkablemark/release-please-extra-files-demo/commit/9de8d22634abd5e961c26dc820d9ce59f77b3d21))

## [1.3.1](https://github.com/remarkablemark/release-please-extra-files-demo/compare/v1.3.0...v1.3.1) (2022-09-23)

### Bug Fixes

- **github:** configure git user in workflow release-please.yml ([f60d024](https://github.com/remarkablemark/release-please-extra-files-demo/commit/f60d024829475dab3b5398b500f1f917cbc05aad))
- **github:** edit release in workflow release-please.yml ([738f5c6](https://github.com/remarkablemark/release-please-extra-files-demo/commit/738f5c65dbe1f93b9ffc07be34098e3e2c6bc532))
- **github:** supply commit message instead of amend ([632c323](https://github.com/remarkablemark/release-please-extra-files-demo/commit/632c323d46a4dbb156546e39b98c77d435de5e45))

## [1.3.0](https://github.com/remarkablemark/release-please-extra-files-demo/compare/v1.2.0...v1.3.0) (2022-09-23)

### Features

- **github:** add workflow edit-release.yml ([c117b75](https://github.com/remarkablemark/release-please-extra-files-demo/commit/c117b753349176c2712d91cf695e4892ba33b98a))

## [1.2.0](https://github.com/remarkablemark/release-please-extra-files-demo/compare/v1.1.0...v1.2.0) (2022-09-22)

### Features

- add badge and table for version ([171fc37](https://github.com/remarkablemark/release-please-extra-files-demo/commit/171fc3787698973292eeb517f6a81f2af8cefb27))

## [1.1.0](https://github.com/remarkablemark/release-please-extra-files-demo/compare/v1.0.0...v1.1.0) (2022-09-22)

### Features

- add files with major, minor, and patch versions ([63bb480](https://github.com/remarkablemark/release-please-extra-files-demo/commit/63bb4807c0ec53a9cc9064563396693ea50a6595))

## 1.0.0 (2022-09-22)

### Features

- add package.json and set version in README.md ([971b88d](https://github.com/remarkablemark/release-please-extra-files-demo/commit/971b88d63d6bad39a94bafd202fd5e71022e83c6))

### Bug Fixes

- annotate lines to update arbitrary files ([410d101](https://github.com/remarkablemark/release-please-extra-files-demo/commit/410d101cf32c902cef40008279c6024c78b7b9a1))
