# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

<!-- insertion marker -->
## Unreleased

<small>[Compare with latest](https://github.com/mrsimonemms/gotify/compare/e19609915ca123a4694ae39a5ef347ce59cc7576...HEAD)</small>

### Features

- allow additional envvars and make default user optional ([2a7cee0](https://github.com/mrsimonemms/gotify/commit/2a7cee0d0749e111884f1d3f31dfcf7ec09ab019) by Simon Emms).
- update image to v 2.6.1 ([046bde5](https://github.com/mrsimonemms/gotify/commit/046bde5600cfed31d81f222ff232ad817face3bb) by Peter Motzko).
- update image to v 2.6.0 ([97c7887](https://github.com/mrsimonemms/gotify/commit/97c78879070f9fa36e1a6cd75058781e32b8ee0c) by Peter Motzko).
- add send notification step, when update available ([3289407](https://github.com/mrsimonemms/gotify/commit/3289407e1df9723da09466226810223d45e5098f) by Peter Motzko).
- add Helm chart update check ([c2b848c](https://github.com/mrsimonemms/gotify/commit/c2b848c602854af983921f7e78bc9059dfbfd1e7) by Peter Motzko).
- add trivy as security scanner ([6151ad7](https://github.com/mrsimonemms/gotify/commit/6151ad7990c23c55f4b3b3b9727c4331639c9cb1) by Peter Motzko).
- bump version to 0.2.1 ([9754629](https://github.com/mrsimonemms/gotify/commit/97546290f18b3ccb1d54e07fb29655833c85cf7d) by Peter Motzko).
- bump app version to 2.3.0 ([7f2fdef](https://github.com/mrsimonemms/gotify/commit/7f2fdefc3c4f378fab8780d8b88ad44dc5f51014) by Peter Motzko).
- Add CONTRIBUTING.md file ([89d0a53](https://github.com/mrsimonemms/gotify/commit/89d0a53031fd8574f5b3f12cd1c77299609714fb) by Peter Motzko).
- Add contributing section to README.md.gotmpl ([385bcde](https://github.com/mrsimonemms/gotify/commit/385bcdebf826897e42376ad469a67f64595309e0) by Peter Motzko).
- update Taskfile to latest content ([745a145](https://github.com/mrsimonemms/gotify/commit/745a145585fdbd79378293e183023eac67552eea) by Peter Motzko).
- update readme badge ([4e37850](https://github.com/mrsimonemms/gotify/commit/4e378504d5f44422f5f4b179f8e9a4cd16605c65) by Peter Motzko).
- update test ([5c4b10c](https://github.com/mrsimonemms/gotify/commit/5c4b10cd845fe21e5ce54c2899b57a520bfb497c) by Peter Motzko).
- bump app version to 2.2.5 ([bd8fbe8](https://github.com/mrsimonemms/gotify/commit/bd8fbe8be76672bbc15bd924a3f41833a3911d80) by Peter Motzko).
- remove api-key from checkov GH Action ([7707b31](https://github.com/mrsimonemms/gotify/commit/7707b318d4d3a10efd69064c8b037f782b8d5482) by Peter Motzko).
- add checkov security scan ([041708a](https://github.com/mrsimonemms/gotify/commit/041708af1b27546ff48345b40985975053ca469c) by Peter Motzko).
- make it possible to use ingress and service-type "LoadBalancer" at the same time ([a494fdf](https://github.com/mrsimonemms/gotify/commit/a494fdf84babed1ea7ceece0aa7e06022401a0fc) by Peter Motzko).
- add taskfile ([1b800e6](https://github.com/mrsimonemms/gotify/commit/1b800e66e28293f1ae2d10b98716ba71465b542f) by Peter Motzko).
- add unittests ([c13d804](https://github.com/mrsimonemms/gotify/commit/c13d8042092a5db3146e72c129addc075d946232) by Peter Motzko).
- adjust .git-/.helmignore ([14d43f1](https://github.com/mrsimonemms/gotify/commit/14d43f1cccc416c23679d31581c94f2260dd70e3) by Peter Motzko).
- add .env template ([b406a2d](https://github.com/mrsimonemms/gotify/commit/b406a2dbe9b6700bfd337bda241daceadc3109fa) by Peter Motzko).
- add precommit hooks ([2016a42](https://github.com/mrsimonemms/gotify/commit/2016a42346071124c4b223ad9eda45367942c2d6) by Peter Motzko).
- add CODE_OF_CONDUCT.md ([86f8b51](https://github.com/mrsimonemms/gotify/commit/86f8b517e65670e18f49d023259c0bfca00ed073) by Peter Motzko).
- Add Artifacthub annotation ([d98a67f](https://github.com/mrsimonemms/gotify/commit/d98a67fed1abf5ce38fa1549117c4e8863ed2a3c) by Peter Motzko).
- Add registration flag and update Readme ([1149cd4](https://github.com/mrsimonemms/gotify/commit/1149cd47733eab28bb57de75307925968c508bf0) by Peter Motzko).
- Add repositoryID ([9b3ec39](https://github.com/mrsimonemms/gotify/commit/9b3ec39b49c163290e80d3dd810ead8778048854) by Peter Motzko).
- Add maintainer email ([e63b465](https://github.com/mrsimonemms/gotify/commit/e63b465fc3605327e4ab106ff045e949c2ec22cd) by Peter Motzko).
- Initial commit ([9e48168](https://github.com/mrsimonemms/gotify/commit/9e48168ccd18a8bfcbd872cff7cefc23f02816cc) by Peter Motzko).

### Bug Fixes

- update tests to current changes ([5e749b8](https://github.com/mrsimonemms/gotify/commit/5e749b882dbfe8308e5b9249ef5057acad674222) by Peter Motzko).
- set allowPrivilegeEscalation to false ([805db22](https://github.com/mrsimonemms/gotify/commit/805db222d6fc6e036e226d66142f9e3453697943) by Peter Motzko).
- set root FS read-only ([8405806](https://github.com/mrsimonemms/gotify/commit/8405806caf736e076d63e0880441abd3d3212ac4) by Peter Motzko).
- use port > 1024 ([55cd7e2](https://github.com/mrsimonemms/gotify/commit/55cd7e27f8d812ea99816e01e6f291c06b0eae11) by Peter Motzko).
- right way of using secrets / vars ([e97f9da](https://github.com/mrsimonemms/gotify/commit/e97f9da93445dd22495f1375f4d6ef899615ca5a) by Peter Motzko).
- add more files to .helmignore ([de2a448](https://github.com/mrsimonemms/gotify/commit/de2a448206a000538272e8b1074177ec5fbd056f) by Peter Motzko).
- unittest ([cb5df00](https://github.com/mrsimonemms/gotify/commit/cb5df00a98a9319af82f58c5b790a2dd4201ed28) by Peter Motzko).
- remove fix values image.tag value ([ae80d1d](https://github.com/mrsimonemms/gotify/commit/ae80d1d8cf5ae0d62b434092a6a55351fb60f714) by Peter Motzko).
- missing "-headless" suffix in ingress ([26ab24e](https://github.com/mrsimonemms/gotify/commit/26ab24ed3e320385d5152cc65da9011fb7d3bede) by Peter Motzko).
- typo in CONTRIBUTING.md ([145cca2](https://github.com/mrsimonemms/gotify/commit/145cca2481dd1a12d940eed211c39f8aa0f820e2) by Peter Motzko).

<!-- insertion marker -->
