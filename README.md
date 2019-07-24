# CircleCI Orbs: `toshimaru/bundle-install` 

[![CircleCI](https://circleci.com/gh/toshimaru/bundle-install.svg?style=svg)](https://circleci.com/gh/toshimaru/bundle-install)

CircleCI Orbs which runs Ruby `bundle install` command with cache.

## Usage

```yml
version: 2.1

orbs:
  # Specify Version after `@`
  bundle-install: toshimaru/bundle-install@x.y.z

jobs:
  build:
    docker:
      - image: circleci/ruby
    steps:
      - checkout
      - bundle-install/bundle-install
      # - bundle exec rspec
```

## Documentation

For more usage, please visit offial CircleCI Orb Registry:

[CircleCI Orb Registry - toshimaru/bundle-install](https://circleci.com/orbs/registry/orb/toshimaru/bundle-install)

## Related Orbs

- [CircleCI Orb Registry - sue445/ruby-orbs](https://circleci.com/orbs/registry/orb/sue445/ruby-orbs)
