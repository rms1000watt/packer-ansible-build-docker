# Packer Ansible Build Docker

## Introduction

Build Docker using Packer + Ansible (wtf?)

Influenced from [here](https://blog.james-carr.org/build-docker-images-with-packer-and-ansible-3f40b734ef4f)

## Contents

- [Installation](#installation)
- [Usage](#usage)

## Installation

```bash
brew install packer ansible
```

## Usage

Build stuff from james-carr example

```bash
cd demo
packer build packer-shell.json
packer build packer-ansible.json
cd ..
```

## TODO

- [ ] Golang version from scratch (is this even doable?)
