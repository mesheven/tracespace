# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [4.1.1](https://github.com/tracespace/tracespace/compare/v4.1.0...v4.1.1) (2019-06-05)


### Bug Fixes

* **deps:** update dependency readable-stream to ^3.4.0 ([#264](https://github.com/tracespace/tracespace/issues/264)) ([1936088](https://github.com/tracespace/tracespace/commit/1936088))
* **deps:** update type definitions ([#245](https://github.com/tracespace/tracespace/issues/245)) ([d227db3](https://github.com/tracespace/tracespace/commit/d227db3))





# [4.1.0](https://github.com/tracespace/tracespace/compare/v4.0.3...v4.1.0) (2019-05-01)


### Bug Fixes

* **deps:** update type definitions ([#238](https://github.com/tracespace/tracespace/issues/238)) ([899777e](https://github.com/tracespace/tracespace/commit/899777e))





## [4.0.3](https://github.com/tracespace/tracespace/compare/v4.0.2...v4.0.3) (2019-04-10)


### Bug Fixes

* **deps:** update dependency @types/node to ^11.13.0 ([#193](https://github.com/tracespace/tracespace/issues/193)) ([44f2d60](https://github.com/tracespace/tracespace/commit/44f2d60))
* **deps:** update dependency @types/node to ^11.13.2 ([#217](https://github.com/tracespace/tracespace/issues/217)) ([e981a4e](https://github.com/tracespace/tracespace/commit/e981a4e))
* **deps:** update dependency readable-stream to ^3.3.0 ([#199](https://github.com/tracespace/tracespace/issues/199)) ([594e947](https://github.com/tracespace/tracespace/commit/594e947))





## [4.0.2](https://github.com/tracespace/tracespace/compare/v4.0.1...v4.0.2) (2019-03-24)


### Bug Fixes

* **deps:** update dependency @types/node to ^11.11.6 ([#184](https://github.com/tracespace/tracespace/issues/184)) ([c3bb301](https://github.com/tracespace/tracespace/commit/c3bb301))
* **gerber-plotter:** Emit correct 'repeat' object on steprepeat disable ([#188](https://github.com/tracespace/tracespace/issues/188)) ([930d133](https://github.com/tracespace/tracespace/commit/930d133)), closes [#81](https://github.com/tracespace/tracespace/issues/81)
* **gerber-to-svg:** Allow options parameter to be skipped ([#181](https://github.com/tracespace/tracespace/issues/181)) ([bbe5c07](https://github.com/tracespace/tracespace/commit/bbe5c07))





# [4.0.0](https://github.com/tracespace/tracespace/compare/v4.0.0-next.19...v4.0.0) (2019-03-09)

**Note:** Version bump only for package gerber-plotter





# [4.0.0-next.19](https://github.com/tracespace/tracespace/compare/v4.0.0-next.18...v4.0.0-next.19) (2019-03-09)


### Features

* Add typescript definitions to all consumable modules ([#103](https://github.com/tracespace/tracespace/issues/103)) ([bb6e8f9](https://github.com/tracespace/tracespace/commit/bb6e8f9))
* Update dependencies and enable Greenkeeper ([9db54cc](https://github.com/tracespace/tracespace/commit/9db54cc))


### Performance Improvements

* Align and simplify parameters, defaults, and return values ([#102](https://github.com/tracespace/tracespace/issues/102)) ([c4e3a84](https://github.com/tracespace/tracespace/commit/c4e3a84)), closes [#99](https://github.com/tracespace/tracespace/issues/99)


### BREAKING CHANGES

* Parameters, defaults, and return types have changed in pcb-stackup,
pcb-stackup-core, and gerber-to-svg





# [4.0.0-next.15](https://github.com/tracespace/tracespace/compare/v4.0.0-next.14...v4.0.0-next.15) (2018-11-13)


### Features

* **whats-that-gerber:** Use collection of filenames to determine type ([#77](https://github.com/tracespace/tracespace/issues/77)) ([6919549](https://github.com/tracespace/tracespace/commit/6919549))


### BREAKING CHANGES

* **whats-that-gerber:** Output of whats-that-gerber changed from a single string to an
object keyed by the filenames passed in as an array





<a name="4.0.0-next.13"></a>
# [4.0.0-next.13](https://github.com/tracespace/tracespace/compare/v4.0.0-next.12...v4.0.0-next.13) (2018-09-12)

**Note:** Version bump only for package gerber-plotter





<a name="4.0.0-next.9"></a>
# [4.0.0-next.9](https://github.com/tracespace/tracespace/compare/v4.0.0-next.8...v4.0.0-next.9) (2018-06-19)


### Bug Fixes

* **gerber-plotter:** Fix outline regression with duplicate paths([#64](https://github.com/tracespace/tracespace/issues/64)) ([23b4bcb](https://github.com/tracespace/tracespace/commit/23b4bcb))





<a name="4.0.0-next.8"></a>
# [4.0.0-next.8](https://github.com/tracespace/tracespace/compare/v4.0.0-next.7...v4.0.0-next.8) (2018-06-16)

**Note:** Version bump only for package gerber-plotter





<a name="4.0.0-next.7"></a>
# [4.0.0-next.7](https://github.com/tracespace/tracespace/compare/v4.0.0-next.6...v4.0.0-next.7) (2018-06-16)


### Bug Fixes

* **gerber-plotter:** Fix gap fill ruining arcs (mcous/gerber-plotter[#13](https://github.com/tracespace/tracespace/issues/13)) ([6cf04b7](https://github.com/tracespace/tracespace/commit/6cf04b7))
