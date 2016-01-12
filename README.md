# vcsh-zsh-server
ZSH configuration files for servers, specifically Ubuntu, for use with [vcsh](https://github.com/RichiH/vcsh)

vcsh basically provides namespaced git repos in the same directory. For instance, this namespace is `vcsh-zsh-server`.

## Installation
1. `sudo apt-get install vcsh`
1. `vcsh clone git@github.com:watbe/vcsh-zsh-server.git` - clones as `vcsh-zsh-server`

## Updating
1. `vcsh <namespace> add/commit <name-of-file>`
2. `vcsh <namespace> push`
