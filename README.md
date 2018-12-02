# `toshimaru/bundle-install` 

[![CircleCI](https://circleci.com/gh/toshimaru/bundle-install.svg?style=svg)](https://circleci.com/gh/toshimaru/bundle-install)

CircleCI Orbs which runs Ruby `bundle install` command with cache.

## Usage

```yml

version: 2.1
 orbs:
  toshimaru: toshimaru/bundle-install@0.0.2

jobs:
  build:
    docker:
      - image: circleci/ruby
    steps:
      - checkout
      - toshimaru/bundle-install
      # - bundle exec rspec
```

## Documentation

For more usage, please visit offial CircleCI Orb Registry:

[CircleCI Orb Registry - toshimaru/bundle-install](https://circleci.com/orbs/registry/orb/toshimaru/bundle-install)
