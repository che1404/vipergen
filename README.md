# Vipergen 🐍

A VIPER module generator written in Swift. It's heavily based on [Pedro Piñera](https://twitter.com/pepibumur)'s vipergen [tool](https://github.com/pepibumur/viper-module-generator/), now sadly deprecated.

## Installation
```shell
$ git clone https://github.com/che1404/Vipergen.git vipergen
$ cd vipergen
$ make install
```

## Usage
Usage:

```shell
$ vipergen --help
Usage:

    $ vipergen <module name>

Arguments:

    module name - The name of the module

Options:
    --template [default: default] - The template (Should exist in the Templates directory)
    --creator [default: John Doe] - The name of the creator
    --output [default: .] - The output directory
```

## Uninstallation
```shell
$ make uninstall
```

## Building
Regenerate the xcodeproj 
```shell
$ swift package generate-xcodeproj
```

