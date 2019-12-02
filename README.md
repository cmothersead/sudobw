# sudobw
bash script to integrate bitwarden-cli with sudo

## Installation
Make the 'sudobw' file executable
  chmod +x sudobw

Assign path to 'sudobw' executable to environment variable $SUDO_ASKPASS
  export SUDO_ASKPASS=/path/to/executable
(In order for export to persist between sessions, place that line in ~/.bash_profile)

## Usage
In order to utilize this script the -A, --askpass parameter must be passed to sudo. This can be accomplished with an alias, or manually.

## License
[MIT]
(https://choosealicense.com/licenses/mit/)
