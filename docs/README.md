<p align="center"><img src="https://raw.githubusercontent.com/brettwilcox/brettwilcox/master/docs/images/scorpion.svg" alt="Scorpion Logo" height="75px"/></p>

![Rust](https://github.com/scorpion/cli/workflows/Rust/badge.svg)
![Crates.io](https://img.shields.io/crates/v/scorpion?logo=rust)
![GitHub](https://img.shields.io/github/license/scorpion/cli?logo=apache&color=blue)

## Overview

[GitHub Project Page](https://github.com/scorpion)

The goal of the scorpion project is to allow complete automation and control of your data. Our core foundations are built on an API first approach and helping break data out of proprietary systems in thoughtful ways. We help provision frameworks and integrations that allow long term success of any project.

By using the latest tools, techniques, and technologies, we can help bring best practices to developers that just want to make code. Build your next dream on solid open source foundations and let us help make it an easier transition. Transparency, documentation, traning, and supporting the community is why this project exists.

## CLI

[CLI docs page](https://scorpion.io/cli/)

Command line interface for the [scorpion project](https://scorpion.io) written in [Rust](https://www.rust-lang.org) and published on [crates.io](https://crates.io/crates/scorpion).

```bash
cargo install scorpion
```

Once installed, please run `scorpion -h` or `scorpion --help` for information on how to use the application. This is an early preview, but please feel free to follow along and make suggestions as we make progress!

## Constellations

[constellations.sh](https://constellations.sh) by scorpion will allow orchestration of open source projects.

### Asterism

An asterism is a suggestion on how to run your constellation and gives a starting point on builing your infrastructure and framework. You would run the following at the command line.

```bash
scorpion co cmf
```

> `co` = short for constellation

That would provision the core _CMF_ foundation and creates a `constellation.toml` file.

Please see [constellations.sh](https://constellations.sh) for more information on the CMF and future constellations.

### Images

These are the currently supported docker images that serve as the foundations and building blocks for an asterism.

- [PHP](https://github.com/scorpion/php)

### constellation.toml

`scorpion co` will either provision a constellation based on the `constellation.toml` file, or it will generate a pre-defined constellation called an asterism.

Standard will be based on [TOML](https://toml.io/en/) formatting.

Standards proposal for `asterism format v0.1.0` will appear here when the issue is opened.

### Future Plans

If you build something really cool, we want to include you in our community! We will be working with and accepting pull requests from the community on various projects.

Get in touch: brett@scorpion.io
