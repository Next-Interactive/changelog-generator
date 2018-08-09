# changelog-generator
Automate the generation of changelog and tagging.

Installation
------

*TODO: We could automate that when we commit with a CI to automatically update the `CHANGELOG.md`.*

First you need NodeJS to commit on this project. I advise you to use [nvm](https://github.com/creationix/nvm) to manage `node` version on your computer.

Then you need to install [auto-changelog](https://github.com/CookPete/auto-changelog):

`npm install -g auto-changelog`

This will update the *changelog* depending on the commit guideline.

Guideline
------

**Commit**:

They should use the pattern defined in the table under.
`EXP-1234` correspond to the define JIRA task if one is associated to the commit.

| Type  | Commit template | Description |
| ------------- | ------------- | ------------- |
| Breaking Change | `breaking change: description of commit #EXP-1234` | Deprecated usage which is going to disappear in the next version |
| New Features | `feat: description of commit #EXP-1234` | When a new feature is added |
| Changed (*Default*) | `description of commit #EXP-1234` | This is the default commit just containing change to the code that doesn't affect much |
| Deprecated | `deprecated: description of commit #EXP-1234` | Deprecated usage which is going to disappear in the next version |
| Fixed | `fix: description of commit #EXP-1234` | When a fix is done |
| Removed | `removed: description of commit #EXP-1234` | A functionality or file removed |
| Security | `security: description of commit #EXP-1234` | Security patch |

**Semver & Changelog**:

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).