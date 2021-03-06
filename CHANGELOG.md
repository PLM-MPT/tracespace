# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

<a name="4.0.0-next.13"></a>
# [4.0.0-next.13](https://github.com/tracespace/tracespace/compare/v4.0.0-next.12...v4.0.0-next.13) (2018-09-12)


### Bug Fixes

* Replace shortid with [@tracespace](https://github.com/tracespace)/xml-id and sanitize IDs ([#79](https://github.com/tracespace/tracespace/issues/79)) ([2cda760](https://github.com/tracespace/tracespace/commit/2cda760)), closes [#78](https://github.com/tracespace/tracespace/issues/78)


### Features

* **whats-that-gerber:** Add support for diptrace filenames ([f3d5d9a](https://github.com/tracespace/tracespace/commit/f3d5d9a))





<a name="4.0.0-next.12"></a>
# [4.0.0-next.12](https://github.com/tracespace/tracespace/compare/v4.0.0-next.11...v4.0.0-next.12) (2018-07-17)


### Bug Fixes

* **pcb-stackup:** Do not mutate layer options and keep filename ([6cbecde](https://github.com/tracespace/tracespace/commit/6cbecde))


### Code Refactoring

* **gerber-to-svg:** Remove CLI in favor of [@tracespace](https://github.com/tracespace)/cli ([50e255d](https://github.com/tracespace/tracespace/commit/50e255d))


### Features

* **cli:** Add [@tracespace](https://github.com/tracespace)/cli package ([486d6fc](https://github.com/tracespace/tracespace/commit/486d6fc)), closes [#13](https://github.com/tracespace/tracespace/issues/13)
* **whats-that-gerber:** Add support for eagle 9+ filenames ([#76](https://github.com/tracespace/tracespace/issues/76)) ([3b8f570](https://github.com/tracespace/tracespace/commit/3b8f570))


### BREAKING CHANGES

* **gerber-to-svg:** Removed gerber-to-svg (gerber2svg) CLI





<a name="4.0.0-next.11"></a>
# [4.0.0-next.11](https://github.com/tracespace/tracespace/compare/v4.0.0-next.10...v4.0.0-next.11) (2018-07-02)


### Bug Fixes

* **whats-that-gerber:** Improve Altium mech layer recognition ([#70](https://github.com/tracespace/tracespace/issues/70)) ([e48d03f](https://github.com/tracespace/tracespace/commit/e48d03f)), closes [#69](https://github.com/tracespace/tracespace/issues/69)





<a name="4.0.0-next.10"></a>
# [4.0.0-next.10](https://github.com/tracespace/tracespace/compare/v4.0.0-next.9...v4.0.0-next.10) (2018-06-27)


### Features

* **whats-that-gerber:** Match Altium internal planes as icu layer ([#68](https://github.com/tracespace/tracespace/issues/68)) ([f0155e2](https://github.com/tracespace/tracespace/commit/f0155e2)), closes [#67](https://github.com/tracespace/tracespace/issues/67)





<a name="4.0.0-next.9"></a>
# [4.0.0-next.9](https://github.com/tracespace/tracespace/compare/v4.0.0-next.8...v4.0.0-next.9) (2018-06-19)


### Bug Fixes

* **gerber-plotter:** Fix outline regression with duplicate paths([#64](https://github.com/tracespace/tracespace/issues/64)) ([23b4bcb](https://github.com/tracespace/tracespace/commit/23b4bcb))


### Features

* **fixtures:** Add usbvil and bus-pirate boards ([#65](https://github.com/tracespace/tracespace/issues/65)) ([394e130](https://github.com/tracespace/tracespace/commit/394e130))





<a name="4.0.0-next.8"></a>
# [4.0.0-next.8](https://github.com/tracespace/tracespace/compare/v4.0.0-next.7...v4.0.0-next.8) (2018-06-16)

**Note:** Version bump only for package tracespace





<a name="4.0.0-next.7"></a>
# [4.0.0-next.7](https://github.com/tracespace/tracespace/compare/v4.0.0-next.6...v4.0.0-next.7) (2018-06-16)


### Bug Fixes

* **gerber-plotter:** Fix gap fill ruining arcs (mcous/gerber-plotter[#13](https://github.com/tracespace/tracespace/issues/13)) ([6cf04b7](https://github.com/tracespace/tracespace/commit/6cf04b7))





<a name="4.0.0-next.6"></a>
# [4.0.0-next.6](https://github.com/tracespace/tracespace/compare/v4.0.0-next.5...v4.0.0-next.6) (2018-06-15)


### Bug Fixes

* **gerber-to-svg:** Fix append-ext check using old short-option ([cde8cda](https://github.com/tracespace/tracespace/commit/cde8cda))





<a name="4.0.0-next.5"></a>
# [4.0.0-next.5](https://github.com/tracespace/tracespace/compare/v4.0.0-next.4...v4.0.0-next.5) (2018-06-15)


### Features

* **gerber-to-svg:** Replace non-functional CLI options ([5633375](https://github.com/tracespace/tracespace/commit/5633375))


### BREAKING CHANGES

* **gerber-to-svg:** Short option for --append-ext was changed from -a to
-e, short option for --optimize-paths was changed to from -z to -t to
match documentation and because -z was already used by --zero





<a name="4.0.0-next.4"></a>
# [4.0.0-next.4](https://github.com/tracespace/tracespace/compare/v4.0.0-next.3...v4.0.0-next.4) (2018-04-27)


### Bug Fixes

* **pcb-stackup-core:** Fix rgba to rgb+opacity conversion ([e07b4be](https://github.com/tracespace/tracespace/commit/e07b4be))


### Features

* **tracespace:** Add pcb-stackup-core@3.0.0 to monorepo ([44a24c1](https://github.com/tracespace/tracespace/commit/44a24c1))
* **fixtures:** Move common render server into fixtures module ([523f681](https://github.com/tracespace/tracespace/commit/523f681))





<a name="4.0.0-next.3"></a>
# [4.0.0-next.3](https://github.com/tracespace/tracespace/compare/v4.0.0-next.2...v4.0.0-next.3) (2018-04-18)


### Features

* **tracespace:** Add whats-that-gerber@3.0.0 to monorepo ([5d755ed](https://github.com/tracespace/tracespace/commit/5d755ed))





<a name="4.0.0-next.2"></a>
# [4.0.0-next.2](https://github.com/tracespace/tracespace/compare/v4.0.0-next.1...v4.0.0-next.2) (2018-04-17)

### Features

* **tracespace:** Add pcb-stackup@3.0.0 to monorepo ([4b08b2d](https://github.com/tracespace/tracespace/commit/4b08b2d))





<a name="4.0.0-next.1"></a>
# [4.0.0-next.1](https://github.com/tracespace/tracespace/compare/v4.0.0-next.0...v4.0.0-next.1) (2018-04-17)


### Features

* **fixtures:** Add [@tracespace](https://github.com/tracespace)/fixtures module ([526a330](https://github.com/tracespace/tracespace/commit/526a330))
