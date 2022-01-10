# Fix `colors` version

- Yarn: use `resolutions` field
  - Example: [yarn](./yarn)
  - Docs:
    - yarn v1: [Selective dependency resolutions | Yarn](https://classic.yarnpkg.com/lang/en/docs/selective-version-resolutions/)
    - yarn v2+: [`yarn set resolution` | Yarn - Package Manager](https://yarnpkg.com/cli/set/resolution)
- npm 8.3+: use `overrides` field
  - Example: [npm-8](npm-8)
  - Docs:
    -
- npm < 8.3: No official way
  - Modify package-lock.json
  - Use [npm-force-resolutions - npm](https://www.npmjs.com/package/npm-force-resolutions)
  - Related
    - [node.js - How do I override nested NPM dependency versions? - Stack Overflow](https://stackoverflow.com/questions/15806152/how-do-i-override-nested-npm-dependency-versions)