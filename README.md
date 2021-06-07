[![Build Status](https://travis-ci.org/w-sanches/asdf-rabbitmq.svg?branch=master)](https://travis-ci.org/w-sanches/asdf-rabbitmq)

# asdf-rabbitmq

Rabbitmq plugin for [asdf](https://github.com/asdf-vm/asdf) version manager. 

## Pre-requesites 

Rabbitmq requires Erlang to be installed. You can use the [asdf-erlang](https://github.com/asdf-vm/asdf-erlang) plugin to install Erlang versions.

## Install

```
asdf plugin add rabbitmq https://github.com/w-sanches/asdf-rabbitmq.git
```

### Support

This plugin currently supports both Linux and macOS.
However, this is an early version and bug may be found. Please report them in the issue tracker.

### .tool-versions file

You can specify the version to install with a line like so in your `.tool-versions` file:

```
rabbitmq <version>
```

## Usage

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install & manage versions of Rabbitmq.
