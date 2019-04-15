# changelog-generator
Automate the generation of changelog and tagging.

Installation
------

*TODO: We could automate with a CI to automatically update the `CHANGELOG.md` on a push | PR*

First you need NodeJS to commit on this project. I advise you to use [nvm](https://github.com/creationix/nvm) to manage `node` version on your computer.

Then you need to install [auto-changelog](https://github.com/CookPete/auto-changelog):

`npm install -g auto-changelog`

This will update the *changelog* depending on the commit guideline.

Usage
------

`npm version [<newversion> | major | minor | patch | premajor | preminor | prepatch | prerelease | from-git]`

For example if the version in `package.json` is `1.0.1` and you want to update to a new minor version use:
`npm version minor`

You can also specify specific version, it is useful for `beta` or `alpha` versions:
`npm version 1.0.1-beta.0`

To update the Changelog when nothing is released yet:
`npm run unreleased`

Guideline
------

- [Default template guideline](docs/default_template.md) | [Example](docs/default_example.md)

Tweak
------

You can tweak the package.json to your guise to use something else than jira as issue provider. If you want to go deeper and create your own template I advise you to check the readme on [auto-changelog](https://github.com/CookPete/auto-changelog).
