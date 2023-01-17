![bash_unit CI](https://github.com/pforret/replicate-cli/workflows/bash_unit%20CI/badge.svg)
![Shellcheck CI](https://github.com/pforret/replicate-cli/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/pforret/replicate-cli)
![GH stars](https://img.shields.io/github/stars/pforret/replicate-cli)
![GH tag](https://img.shields.io/github/v/tag/pforret/replicate-cli)
![GH License](https://img.shields.io/github/license/pforret/replicate-cli)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://www.basher.it/package/)

# replicate-cli

Bash CLI for use with Replicate.com APIBash CLI for use with Replicate.com API

## 🔥 Usage

```
Program: replicate-cli 0.0.1 by peter@forret.com
Updated: 2023-01-17
Description: Bash CLI for use with Replicate.com APIBash CLI for use with Replicate.com API
Usage: normal.sh [-h] [-q] [-v] [-f] [-l <log_dir>] [-t <tmp_dir>] <action> <input?>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] output more [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /Users/pforret/log/normal]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: .tmp]
    <action>         : [parameter] action to perform: analyze/convert
    <input>          : [parameter] input file/text (optional)
```

## ⚡️ Examples

```bash
> replicate-cli .
# start PhpStorm with current folder as project
```

## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install pforret/replicate-cli

or with `git`

	$ git clone https://github.com/pforret/replicate-cli.git
	$ cd replicate-cli

## 📝 Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2023 Peter Forret
