# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

### [Unreleased](https://github.com/Jno21/changelog-generator/compare/v2.2.0...HEAD)

#### PR Merged

#### :wrench:  Changed

- Add typo for PR Merged [`1e2b952`](https://github.com/Jno21/changelog-generator/commit/1e2b9525a3acec453cf9ffab1e91d50aa40e0de8)

#### :bug:  Fixed

- Fix PR link [`3a87b0a`](https://github.com/Jno21/changelog-generator/commit/3a87b0a5b40b2947537955d25ba9c5a7397dacbb)

### [v2.2.0](https://github.com/Jno21/changelog-generator/compare/v2.1.1...v2.2.0)
> 15 April 2019

#### PR Merged
- Update changelog generator  [`1`](https://github.com/Jno21/changelog-generator/pull/1)

#### :sparkles:  New Features

- Add npm command to update the unreleased content of the CHANGELOG.md [`65c3ed4`](https://github.com/Jno21/changelog-generator/commit/65c3ed4631b7d5a832d4f5cf33f21ca95433f289)
- Update and fix version of auto-changelog to 1.12.1 [`e491209`](https://github.com/Jno21/changelog-generator/commit/e4912091f628fe7c00cbd6cad6c459d34173b81f)
- Use option breakingPattern to know when breaking changes occurs [`00c8649`](https://github.com/Jno21/changelog-generator/commit/00c8649d797eb235cdf85d46916d026a4d6aaaff)

#### :wrench:  Changed

- Change order of options in package.json to be more readable [`3fbaff9`](https://github.com/Jno21/changelog-generator/commit/3fbaff96401650764d7bd875df56292f043b8525)
- 2.2.0 [`d7a717d`](https://github.com/Jno21/changelog-generator/commit/d7a717d07d9798c65940502ffb997e8222cb88f7)
- Add .gitignore for node files [`7e6202d`](https://github.com/Jno21/changelog-generator/commit/7e6202dcef6db031f5822aeac6407e2f33329627)
- Update documentation to explain unreleased option [`598f267`](https://github.com/Jno21/changelog-generator/commit/598f26775e99581765725022510409c58d896f96)

#### :bug:  Fixed

- Fix typos in comment for default-templates.hbs [`d22c994`](https://github.com/Jno21/changelog-generator/commit/d22c994555c9b34f3860857088ca106b83a92297)

####  :no_entry_sign:  Removed

- removed: Remove issueUrl and issuePattern using Jira [`880f0b7`](https://github.com/Jno21/changelog-generator/commit/880f0b79fde27537a1f4bd446fe7626aa308d3ba)

### [v2.1.1](https://github.com/Jno21/changelog-generator/compare/v2.1.0...v2.1.1)
> 28 August 2018

#### PR Merged

#### :wrench:  Changed

- 2.1.1 [`a155dba`](https://github.com/Jno21/changelog-generator/commit/a155dba4f6f43c213e7dfa4abc97f780bbb7d9ba)

#### :bug:  Fixed

- Fix docs for default_temaplate which contained invalid informations [`7032395`](https://github.com/Jno21/changelog-generator/commit/7032395b8880b12481a39919507eab03afe38e2b)

### [v2.1.0](https://github.com/Jno21/changelog-generator/compare/v2.0.2...v2.1.0)
> 9 August 2018

#### PR Merged

#### :sparkles:  New Features

- Add emoji to changelog [`dd51cb7`](https://github.com/Jno21/changelog-generator/commit/dd51cb74fbfcb9d67bf98e6d9ba55c1ac6c114a2)

#### :wrench:  Changed

- 2.1.0 [`38d58b4`](https://github.com/Jno21/changelog-generator/commit/38d58b4e7f1e2c2c1ef22ba86ad41c5ba02d2b3d)

### [v2.0.2](https://github.com/Jno21/changelog-generator/compare/v2.0.1...v2.0.2)
> 9 August 2018

#### PR Merged

#### :wrench:  Changed

- 2.0.2 [`ce6a3b3`](https://github.com/Jno21/changelog-generator/commit/ce6a3b380c74e08b7da7f51773636d30c0795bb0)

#### :bug:  Fixed

- Rename default-template.md to default_template.md [`092016a`](https://github.com/Jno21/changelog-generator/commit/092016ad6526a190a473ff2da5c1309568f30f08)

### [v2.0.1](https://github.com/Jno21/changelog-generator/compare/v2.0.0...v2.0.1)
> 9 August 2018

#### PR Merged

#### :wrench:  Changed

- regenerate changelogs default_example.md [`8adb4c5`](https://github.com/Jno21/changelog-generator/commit/8adb4c502a455c0e76e9d887ba909970207f1794)
- 2.0.1 [`da48c64`](https://github.com/Jno21/changelog-generator/commit/da48c64d3597c29d9b697e3c7580d31a0ffb98b2)

## [v2.0.0](https://github.com/Jno21/changelog-generator/compare/v1.0.0...v2.0.0)
> 9 August 2018

#### PR Merged

#### :rotating_light:  Breaking Changes  :rotating_light:

- Moved and rename the template to templates/default.hbs [`0da6034`](https://github.com/Jno21/changelog-generator/commit/0da603458b189cc17c7e74a16eebc5557ca86999)

#### :sparkles:  New Features

- Add &#x60;security&#x60; and &#x60;removed&#x60; to new type of commit [`b65abcf`](https://github.com/Jno21/changelog-generator/commit/b65abcf0dc90c7347379520569163d530bfffa37)
- Add example to default_template [`ded6f68`](https://github.com/Jno21/changelog-generator/commit/ded6f6873e396c7b18d71e52ad7e298071d7ff7e)

#### :wrench:  Changed

- Refactor documentation to be more complete and easy to understand [`2901f29`](https://github.com/Jno21/changelog-generator/commit/2901f2940bb79e2b6040ccf7b18802e710457043)
- 2.0.0 [`47d3fe3`](https://github.com/Jno21/changelog-generator/commit/47d3fe39aee97e35d788bb370d57271017707531)

#### :bug:  Fixed

- Fix breaking changes in package.json, incorrect syntax [`7d809cc`](https://github.com/Jno21/changelog-generator/commit/7d809cc74140446a5972fe1e0cd7991de11f104d)

### v1.0.0
> 7 August 2018

#### PR Merged

#### :sparkles:  New Features

- Add changelog template [`e9797ff`](https://github.com/Jno21/changelog-generator/commit/e9797ff5e8a914a03f7f38dbc138353195023ff7)

#### :wrench:  Changed

- Initial commit [`0d98ba0`](https://github.com/Jno21/changelog-generator/commit/0d98ba00b39ca87c873dc30f459bdbd20bfa287a)
- Update README.md [`6e18ed0`](https://github.com/Jno21/changelog-generator/commit/6e18ed0f6306b02b7d665113ff1bdd7325a39570)
- Add package.json [`e08fd45`](https://github.com/Jno21/changelog-generator/commit/e08fd45ba9695927dcf3088b89c9c884a74da589)
- 1.0.0 [`d38657b`](https://github.com/Jno21/changelog-generator/commit/d38657b5c66791ec95b1217eda4c2e889d2d9a96)
