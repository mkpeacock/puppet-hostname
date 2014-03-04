Puppet hostname module
===============
A simple module for setting and managing a servers hostname. Useful for projects which just use `puppet apply`

## Requirements

Only tested on Ubuntu. No provisions have been made for this to work on other systems.

## Installation

git submodule add https://github.com/mkpeacock/puppet-hostname modules/hostname

## Usage

```
class {
    'hostname':
        hostname => 'my.server.test.com'
}
```
