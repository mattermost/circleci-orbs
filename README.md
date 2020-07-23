# Mattermost circleci orbs

Orbs to help with building Mattermost repositories in circleci

* [**plugin-ci**](https://circleci.com/orbs/registry/orb/mattermost/plugin-ci): shared jobs to add a plugin to the standard CI

## Releasing new orb for plugin-ci
```bash
$ git tag patch-release-vX.Y.Z
$ git push origin patch-release-vX.Y.Z
```
Manually approve in circleci
