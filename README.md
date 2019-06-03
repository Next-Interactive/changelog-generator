# changelog-generator
Automate the generation of changelog and tagging following the [Semantic Versionning](https://semver.org/).

What's a changelog: keepachangelog.com

Installation
------

*TODO: We could automate with a CI to automatically update the `CHANGELOG.md` on a push | PR*

First you need NodeJS to commit on this project. I advise you to use [nvm](https://github.com/creationix/nvm) to manage `node` version on your computer.

Then you need to install [auto-changelog](https://github.com/CookPete/auto-changelog):

`npm install -g auto-changelog`


Installation in a repo
------

Copy the `package.json` from this repo to the repo you want to use changelog-generator. 
Edit the file to change:
- the `name` to your repository name
- the `version` to the current version of your repository (tag) or set it to 0.0.1 to begin with.

Run `npm install` to install locally `auto-changelog`

You are ready to use it !

Usage
------

To release a new version:

`npm version [<newversion> | major | minor | patch | premajor | preminor | prepatch | prerelease | from-git]`

For example if the version in `package.json` is `1.0.1` and you want to update to a new minor version use:
`npm version minor`

You can also specify specific version, it is useful for `beta` or `alpha` versions:
`npm version 1.0.1-beta.0`

After this you just have to `git push` and your version is released.

To update the Changelog when nothing is released yet:
`npm run unreleased`

Guideline
------

- [Default template guideline](docs/default_template.md) | [Example](docs/default_example.md)

Tweak
------

You can tweak the package.json to your guise to use something else than jira as issue provider. If you want to go deeper and create your own template I advise you to check the readme on [auto-changelog](https://github.com/CookPete/auto-changelog).
