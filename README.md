# changelog-db

Last updated: 2023-05-04T17:13:27+0900

A manual best-effort attempt at creating a third-party npm package name → changelog URL mapping.

`false` represents "I've checked and it doesn't have a changelog".

Scope:

- other software registries
  - [pypi](https://pypi.org/): already records it

Monorepo GitHub releases: If I can find a search term to narrow it down to the package, I'll try to do so. If not, the release page is recorded as the changelog URL instead. Example of the latter would be Astro.

GitHub path links: [use `-` to refer to *the default branch*](https://stackoverflow.com/questions/64726262/is-there-a-stable-url-to-always-get-the-default-branch-in-github).

We track the latest changelog, as the main use is for people looking for what's changed between their current version and a newly released version. For example, [node-config](https://github.com/node-config/node-config) uses GitHub Releases for new releases but has a History.md for releases before a certain point; only the former is tracked.

## License

CC-0.
