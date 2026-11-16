# Instant Cloud docs

Source of [docs.instant.rw](https://docs.instant.rw), built with [Mintlify](https://mintlify.com). Pages are MDX files; navigation and site settings live in `docs.json`.

## Preview locally

```sh
npm i -g mint
mint dev
```

The site runs at http://localhost:3000. Run `mint broken-links` before pushing.

## Publishing

Pushes to `main` deploy to docs.instant.rw. Pages can also be edited in the Mintlify editor, which commits to this repository.
