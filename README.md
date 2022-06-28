<!-- NOTES:
  Once repo is created and pulled to dev environment, run `deno run -A init.ts` to initialize the repo.
  Be sure to resolve the "TODO:"s in the repo.
  Before you commit, make sure run `deno task pre-commit` to run the pre-commit task.
-->

<p align="center">
  <!-- Update log -->
  <img alt="partic11e logo" height="70" src="https://raw.githubusercontent.com/i11n/.github/main/profile/img/p11/logotype.svg" />
  <strong>{{packageName}}</strong>
</p>

<p align="center">
  partic11e is a collection of easy-to-use utility and feature libraries for creating anything you want with the [Deno][deno] runtime.
</p>

<h1 align="center">partic11e - {{packageName}}</h1>

<p align="center">
  <!-- TODO: Package description -->
</p>

<p align="center">
  <!-- TODO: Link to documentation and other resources -->
</p>

<p align="center">
  <sub>Built with ❤ by integer11 and <a href="https://github.com/i11n/{{packageName}}/graphs/contributors">contributors</a></sub>
</p>

<p align="center">
  <a href="https://github.com/i11n/{{packageName}}/blob/main/CODE_OF_CONDUCT.md">
    <img alt="Contributor Covenant" src="https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg?style=flat-square" />
  </a>
  <a href="https://github.com/i11n/{{packageName}}/commits">
    <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/i11n/partic11e?style=flat-square">
  </a>
  <a href="https://github.com/i11n/{{packageName}}/releases">
    <img alt="GitHub release (latest SemVer)" src="https://img.shields.io/github/v/release/i11n/{{packageName}}?style=flat-square" />
  </a>
  <a href="https://github.com/i11n/{{packageName}}/issues">
    <img alt="GitHub issues" src="https://img.shields.io/github/issues-raw/i11n/partic11e?style=flat-square">
  </a>
</p>

## Table of contents

- [Features](#features)
- [Installation](#installation)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Features

[(to top)](#table-of-contents)

<!-- TODO: Enumerate key features -->

## Installation

[(to top)](#table-of-contents)

To install, you simply need to re-export the library features with your `./deps.ts` file.

```ts
// ./deps.ts
export * from "https://denopkg.com/i11n/{{packageName}}/mod.ts";
//  or specific features
```

and then import them from your `./deps.ts` file into the files they are needed.

```ts
// ./src/app.ts
import { VERSION } from "../deps.ts";
//  or other features
```

You can specify a specific branch or release to re-export:

**Export from a specific branch**

```ts
export * from "https://denopkg.com/i11n/{{packageName}}@dev-fix-06145/mod.ts";
```

**Export from a specific release**

```ts
export * from "https://denopkg.com/i11n/{{packageName}}@v0.1.0-alpha/mod.ts";
```

**Export the latest release**

```ts
export * from "https://denopkg.com/i11n/{{packageName}}@latest/mod.ts";
```

> **Note:** If no branch or tag is specified in the re-export, then it will pull from the main branch, which we only merge into when preparing a release.\
> Check out the [branches][branches] and [releases][releases] see what's available.

## Examples

[(to top)](#table-of-contents)

<!-- TODO: Add an example, or add links to examples -->

```ts
```

## Contributing

[(to top)](#table-of-contents)

Contributions are welcome! Take a look at our [contributing guidelines][contributing] to get started.

## License

[(to top)](#table-of-contents)

The MIT License (MIT) 2022 integer11. Refer to [LICENSE][license] for details.

[deno]: https://deno.land "Deno homepage"
[branches]: https://github.com/i11n/{{packageName}}/branches "{{packageName}} branches on GitHub"
[releases]: https://github.com/i11n/{{packageName}}/releases "{{packageName}} releases on GitHub"
[contributing]: https://github.com/i11n/{{packageName}}/blob/main/.github/CONTRIBUTING.md "{{packageName}} contributing guidelines"
[license]: https://github.com/i11n/{{packageName}}/blob/main/LICENSE "{{packageName}} license"
