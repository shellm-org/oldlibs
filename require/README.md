# require
External requirements for shell scripts.

- Authors: https://gitlab.com/shellm/require/AUTHORS.md
- Changelog: https://gitlab.com/shellm/require/CHANGELOG.md
- Contributing: https://gitlab.com/shellm/require/CONTRIBUTING.md
- Documentation: https://gitlab.com/shellm/require/wiki
- License: ISC - https://gitlab.com/shellm/require/LICENSE

## Installation
Installation with [basher](https://github.com/basherpm/basher):
```bash
basher install shellm/require
```

Installation from source:
```bash
git clone https://gitlab.com/shellm/require
cd require
sudo ./install.sh
```

## Usage
Command-line:
```
require -h
```

As a library:
```bash
# with basher's include
include shellm/require lib/require.sh
# with shellm's include
shellm-source shellm/require lib/require.sh
```
