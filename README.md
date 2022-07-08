# Vodyani semantic-release

*⚙ With a little preparation, the semantic release rules for vodyani may be readily integrated into projects.*

[![Npm](https://img.shields.io/npm/v/@vodyani/semantic-release)](https://www.npmjs.com/package/@vodyani/semantic-release)
[![Npm](https://img.shields.io/npm/dm/@vodyani/semantic-release)](https://www.npmjs.com/package/@vodyani/semantic-release)
[![License](https://img.shields.io/github/license/vodyani/semantic-release)](LICENSE)
![Workflow](https://github.com/vodyani/semantic-release/actions/workflows/release.yml/badge.svg)

## Installation

```sh
npm install --save-dev @vodyani/semantic-release
```

## Usage

**Add the `release` configuration to `package.json`, then the inheritance relationship like this:**

```json
{
  "release": {
    "extends": "@vodyani/semantic-release"
  }
}
```

## Dependencies

- semantic-release `v19`
- @semantic-release/git `v10`
- @semantic-release/changelog `v6`

## Team

|[![ChoGathK](https://github.com/chogathK.png?size=100)](https://github.com/chogathK)|
|:-:|
|[ChoGathK](https://github.com/chogathK)|

## License

Vodyani semantic-release is [MIT licensed](LICENSE).
