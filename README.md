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
Program : replicate-cli  by peter@forret.com
Version : v0.0.2 (2023-01-17 16:23)
Purpose : Bash CLI for use with Replicate.com API
Usage   : replicate-cli [-h] [-q] [-v] [-f] [-l <log_dir>] [-t <tmp_dir>] [-C <COUNT>] [-G <GUIDANCE>] [-H <HEIGHT>] [-M <MODEL>] [-N <STEPS>] [-R <STRENGTH>] [-S <SCHEDULE>] [-T <REPLICATE_API_TOKEN>] [-V <VERSION>] [-W <WIDTH>
] [-X <SEED>] <action> <prompt?> <negative?>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] also show debug messages [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /home/pforret/log/replicate-cli]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: .tmp]
    -C|--COUNT <?>   : [option] Number of outputs  [default: 1]
    -G|--GUIDANCE <?>: [option] Classifier-free guidance  [default: 7.5]
    -H|--HEIGHT <?>  : [option] Image height  [default: 512]
    -M|--MODEL <?>   : [option] Prediction model to use  [default: stability-ai/stable-diffusion]
    -N|--STEPS <?>   : [option] Number of steps  [default: 50]
    -R|--STRENGTH <?>: [option] Prompt strength (0-1)  [default: 0.8]
    -S|--SCHEDULE <?>: [option] Scheduler  [default: DPMSolverMultistep]
    -T|--REPLICATE_API_TOKEN <?>: [option] Replicate.com API token
    -V|--VERSION <?> : [option] Prediction model version
    -W|--WIDTH <?>   : [option] Image width  [default: 512]
    -X|--SEED <?>    : [option] Force start seeding
    <action>         : [choice] action to perform  [options: collections,models,predict,check,env,update]
    <prompt>         : [parameter] prompt (optional)
    <negative>       : [parameter] negative prompt (optional)

### TIPS & EXAMPLES
* use replicate-cli predict to ...
  replicate-cli predict
* use replicate-cli collections to list all collections
  replicate-cli collections
* use replicate-cli models to list all models for a collection
  replicate-cli models
  replicate-cli models image-to-text
  replicate-cli models super-resolution
* use replicate-cli check to check if this script is ready to execute and what values the options/flags are
  replicate-cli check
* use replicate-cli env to generate an example .env file
  replicate-cli env > .env
* use replicate-cli update to update to the latest version
  replicate-cli update
* >>> bash script created with pforret/bashew
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

* Replicate API on [replicate.com/docs/reference/http](https://replicate.com/docs/reference/http)
* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2023 Peter Forret
