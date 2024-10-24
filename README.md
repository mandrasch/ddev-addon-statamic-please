[![tests](https://github.com/mandrasch/ddev-addon-statamic-please/actions/workflows/tests.yml/badge.svg)](https://github.com/mandrasch/ddev-addon-statamic-please/actions/workflows/tests.yml) ![project is maintained](https://img.shields.io/maintenance/yes/2022.svg)

DDEV addon for supporting statamics `please`-command.

## Installation

For DDEV v1.23.5 or above run

```sh
ddev add-on get mandrasch/ddev-addon-statamic-please
```

For earlier versions of DDEV run

```sh
ddev get mandrasch/ddev-addon-statamic-please
```

## Usage

All it does is add this custom command file to `.ddev/`:

https://github.com/mandrasch/ddev-statamic-please/blob/main/commands/web/please

You can use it afterwards with `ddev please <your-command>`

Created via https://github.com/drud/ddev-addon-template
