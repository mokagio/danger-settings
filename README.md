This is a for of [Automattic/peril-settings](https://github.com/Automattic/peril-settings) where the `Dangerfile`s don't use `export default async`, as that [seems to result in issues when fed to `yarn run danger`](https://github.com/mokagio/WordPress-iOS/pull/9).

---

# Peril Settings

These are the settings for running [Peril](https://github.com/danger/peril) on repositories in `Automattic`, `simplenote` and `wordpress-mobile`.

### Installing

After cloning the repo, run `yarn install`.

### Running the tests

Tests can be run with `yarn test`.
