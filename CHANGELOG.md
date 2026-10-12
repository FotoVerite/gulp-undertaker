# Changelog

## 1.0.0 (2026-10-12)


### ⚠ BREAKING CHANGES

* Stop inspecting UNDERTAKER_TIME_RESOLUTION environment variable ([#98](https://github.com/FotoVerite/gulp-undertaker/issues/98))
* Normalize repository, dropping node <10.13 support ([#97](https://github.com/FotoVerite/gulp-undertaker/issues/97))

### Features

* Attach properties to missing task error ([#102](https://github.com/FotoVerite/gulp-undertaker/issues/102)) ([989d9e9](https://github.com/FotoVerite/gulp-undertaker/commit/989d9e90bd65f50b54c89ab2e62a628db6af1c47))


### Bug Fixes

* Avoid setting displayName on series/parallel functions (ref gulpjs/gulp[#2270](https://github.com/FotoVerite/gulp-undertaker/issues/2270)) ([#91](https://github.com/FotoVerite/gulp-undertaker/issues/91)) ([1ee58b1](https://github.com/FotoVerite/gulp-undertaker/commit/1ee58b1a374af428607fd67362895ac30927073c))
* Capture start time only on successful completion ([1a17780](https://github.com/FotoVerite/gulp-undertaker/commit/1a17780354a35d6a67cc90d1938862ba977997e2))
* Consistent naming for functions created by series/parallel ([9e9ca31](https://github.com/FotoVerite/gulp-undertaker/commit/9e9ca31da4d68e1342dfd869f0422c30c291425a))
* Emit an error even if settling & only emit the first error in an array of errors ([206c088](https://github.com/FotoVerite/gulp-undertaker/commit/206c08898681d2dddacd14f0d97b94d0be3d89ea))
* Ensure some task tests are actually running ([f94fd87](https://github.com/FotoVerite/gulp-undertaker/commit/f94fd87143b9ff81e92e193ab3c9484b787770a6))
* Ignore leaked global from `sparkles` ([818450b](https://github.com/FotoVerite/gulp-undertaker/commit/818450bd6bb834a351624d5a505225bd1a578993))
* Improve integration tests, especially on Windows ([a2a2f73](https://github.com/FotoVerite/gulp-undertaker/commit/a2a2f73ba281b85ba83fa14c1601958e11f9605b))
* Inline anonymous functions to get tests passing on newer nodes ([#70](https://github.com/FotoVerite/gulp-undertaker/issues/70)) ([ffcb044](https://github.com/FotoVerite/gulp-undertaker/commit/ffcb04412b824a50adecca4831395c32b1685ce1))
* Keep task name precedence consistent ([ec61638](https://github.com/FotoVerite/gulp-undertaker/commit/ec61638d5555af423e29d193a15e7269283b3591))
* Make linting pass & add pretest hook ([52c3cad](https://github.com/FotoVerite/gulp-undertaker/commit/52c3cad218dbea789464dfde7b48e2105f317fcc))
* Remove conditional use of es6-weak-map ([7f076bd](https://github.com/FotoVerite/gulp-undertaker/commit/7f076bd1b43cc53b172c353cf24ee274ea7b5db3))
* Support modified functions in custom registries ([edd3487](https://github.com/FotoVerite/gulp-undertaker/commit/edd34876e52cd55ff2b286d0a2619bb8fd4a18d5))
* Support task aliases ([25c2a90](https://github.com/FotoVerite/gulp-undertaker/commit/25c2a906037fccce58afae3017e7e9ba0591c117))
* Validate series/parallel arguments aren't empty or invalid (fixes [#72](https://github.com/FotoVerite/gulp-undertaker/issues/72)) ([#75](https://github.com/FotoVerite/gulp-undertaker/issues/75)) ([5464736](https://github.com/FotoVerite/gulp-undertaker/commit/546473622f41daa1ac45144506b51e66140444b8))


### Miscellaneous Chores

* Normalize repository, dropping node &lt;10.13 support ([#97](https://github.com/FotoVerite/gulp-undertaker/issues/97)) ([b270c28](https://github.com/FotoVerite/gulp-undertaker/commit/b270c2852c8398c26f1ac5b1fb80cd6e2aebdf89))
* Stop inspecting UNDERTAKER_TIME_RESOLUTION environment variable ([#98](https://github.com/FotoVerite/gulp-undertaker/issues/98)) ([e255fc7](https://github.com/FotoVerite/gulp-undertaker/commit/e255fc7c9be27d11dc8a711a3f15e058040e712c))

## [2.0.0](https://www.github.com/gulpjs/undertaker/compare/v1.3.0...v2.0.0) (2024-03-22)


### ⚠ BREAKING CHANGES

* Stop inspecting UNDERTAKER_TIME_RESOLUTION environment variable (#98)
* Normalize repository, dropping node <10.13 support (#97)

### Features

* Attach properties to missing task error ([#102](https://www.github.com/gulpjs/undertaker/issues/102)) ([989d9e9](https://www.github.com/gulpjs/undertaker/commit/989d9e90bd65f50b54c89ab2e62a628db6af1c47))


### Miscellaneous Chores

* Normalize repository, dropping node <10.13 support ([#97](https://www.github.com/gulpjs/undertaker/issues/97)) ([b270c28](https://www.github.com/gulpjs/undertaker/commit/b270c2852c8398c26f1ac5b1fb80cd6e2aebdf89))
* Stop inspecting UNDERTAKER_TIME_RESOLUTION environment variable ([#98](https://www.github.com/gulpjs/undertaker/issues/98)) ([e255fc7](https://www.github.com/gulpjs/undertaker/commit/e255fc7c9be27d11dc8a711a3f15e058040e712c))
