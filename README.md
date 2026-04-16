<a href="https://arcjet.com" target="_arcjet-home">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://arcjet.com/logo/arcjet-dark-lockup-voyage-horizontal.svg">
    <img src="https://arcjet.com/logo/arcjet-light-lockup-voyage-horizontal.svg" alt="Arcjet Logo" height="128" width="auto">
  </picture>
</a>

# Homebrew Tap

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/github/v/release/arcjet/cli?style=flat-square&label=%E2%9C%A6Aj&labelColor=000000&color=5C5866">
    <img alt="GitHub release badge" src="https://img.shields.io/github/v/release/arcjet/cli?style=flat-square&label=%E2%9C%A6Aj&labelColor=ECE6F0&color=ECE6F0">
  </picture>
</p>

[Arcjet](https://arcjet.com) is the runtime security platform that ships with
your code. This is the official [Homebrew](https://brew.sh) tap for the
[Arcjet CLI](https://github.com/arcjet/cli).

## Install

```bash
brew install arcjet/tap/arcjet
```

This adds the tap and installs the `arcjet` CLI in a single command. To add the
tap separately:

```bash
brew tap arcjet/tap
brew install arcjet
```

## Upgrade

```bash
brew upgrade arcjet
```

## Usage

Log in to your Arcjet account:

```bash
arcjet auth login
```

Get a security briefing for your site:

```bash
arcjet briefing --site-id site_01abc123
```

See the [Arcjet CLI repository](https://github.com/arcjet/cli) for the full
command reference, or run `arcjet --help` to see all available commands.

## Get help

Need help with anything?
[Email us](mailto:support@arcjet.com) or
[join our Discord](https://arcjet.com/discord) to get support from our
engineering team.

## Support

This repository follows the [Arcjet Support Policy](https://docs.arcjet.com/support).

## Security

This repository follows the [Arcjet Security Policy](https://docs.arcjet.com/security).