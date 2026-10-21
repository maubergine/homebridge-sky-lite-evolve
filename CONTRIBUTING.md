# Contributing

A Homebridge plugin for the BlissLights Sky Lite Evolve star projector (a fork of kevbo/homebridge-sky-lite-evolve).

Bug reports and feature requests are welcome as [issues](https://github.com/maubergine/homebridge-sky-lite-evolve/issues). Pull requests are
welcome too; CI on a pull request from a fork may wait for the maintainer to approve it.

## Commits

Use [Conventional Commits](https://www.conventionalcommits.org/): `fix:`, `feat:`, `chore:`, `docs:` and so on. This fork doesn't use semantic-release, so commits don't cut releases. CI checks
every commit (`commitlint.yml`). To check them locally before you push:

```sh
npm install   # installs commitlint and turns on .githooks/commit-msg
```

Commits to `latest` must be signed.

## Tests

Run `npm ci`, then `npm run lint` and `npm run build`. There are no unit tests.
