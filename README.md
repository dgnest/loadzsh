# loadzsh

<span class="badges" align="center">
[![Build Status](https://travis-ci.org/hadenlabs/loadzsh.svg)](https://travis-ci.org/hadenlabs/loadzsh)
[![Stories in Ready](https://badge.waffle.io/hadenlabs/loadzsh.svg?label=ready&title=Ready)](http://waffle.io/hadenlabs/loadzsh)
[![GitHub issues](https://img.shields.io/github/issues/hadenlabs/loadzsh.svg)](https://github.com/hadenlabs/loadzsh/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


A faster and simpler loadzsh written in Golang.

## Requirements

 - Linux
   - none
 - OSX
   - [Homebrew][link-brew] must be installed.

### Install

The simplest way to install loadzsh is to run:

```console
$ curl -s https://raw.githubusercontent.com/hadenlabs/loadzsh/master/install | bash -s
$ echo 'source <(loadzsh init)' >> ~/.zshrc
```

This will put the binary in `/usr/local/bin/loadzsh` and setup your `~/.zshrc` to
load what is needed on startup.

### Example plugins.yaml

Prefer to use it like this:

```yaml
-   repo: git://github.com/luismayta/zsh-git-aliases
    sha: master
-   repo: git://github.com/zsh-users/zsh-completions
    sha: master
```


## Dependencies

none

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

- [Luis Mayta][link-author]
- [All Contributors][link-contributors]

Made with ♥️ and ☕️ by hadenlabs and our community.

[link-golang]: https://golang.org/en/
[link-brew]: http://brew.sh/

<!-- Other -->

[link-author]: https://github.com/luismayta
[link-contributors]: contributors
