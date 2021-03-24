# Awesome Nix [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [<img src="https://nixos.org/logo/nixos-logo-only-hires.png" width="200" align="right" alt="nixos">](https://nixos.org)

> A curated list of the best resources in the Nix community.

[Nix](https://github.com/nixos/nix) is a powerful package manager for Linux and other Unix systems that makes package management reliable and reproducible.

*Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.*

## Contents

* [Resources](#resources)
    * [Learning](#learning)
    * [Grokking](#grokking)
    * [Newsletters](#newsletters)
* [Installation Media](#installation-media)
* [Channel History](#channel-history)
* [Cloud Stuff](#cloud-stuff)
* [Command-Line Tools](#command-line-tools)
* [Development](#development)
* [Programming Languages](#programming-languages)
    * [Elm](#elm)
    * [Haskell](#haskell)
    * [Node.js](#nodejs)
    * [PureScript](#purescript)
    * [Python](#python)
    * [Ruby](#ruby)
    * [Rust](#rust)
* [NixOS Modules](#nixos-modules)
* [Overlays](#overlays)
* [Community](#community)

## Resources

### Learning

* [Nix Notes](https://github.com/noteed/nix-notes) - A collection of short notes about Nix, each contributing to the same virtual machine image.
* [Nix Pills](https://nixos.org/nixos/nix-pills/) - The best way to learn by examples.
* [Nix Shorts](https://github.com/justinwoo/nix-shorts/) - A collection of short notes about Nix.
* [nix.dev](https://nix.dev/) - An opinionated guide for developers getting things done using the Nix ecosystem.
* [Tour of Nix](https://nixcloud.io/tour) - Online interactive tutorial on Nix language constructs.

### Grokking

* [Hound](https://search.nix.gsc.io) - Handy search across all or selected nix related repos. 
* [Nixpkgs Database](https://kamadorueda.github.io/nixpkgs-db/) - A database with Nix packages at all versions, from all channels.

### Newsletters

* [NixOS Weekly](https://weekly.nixos.org/) - The best newsletter to stay informed about community updates.

## Installation Media

* [nixos-generators](https://github.com/nix-community/nixos-generators) -  Take a nixos config and build multile usage images including VirtualBox, Azure, installation iso among other formats.

## Channel History 

* [Channel History](https://channels.nix.gsc.io) - Get historical git commits for Nix channels.
* [Nix Infra Status](https://status.nixos.org) - Get the age/current git commit of all Nix channels.

## Cloud Stuff

* [krops](https://cgit.krebsco.de/krops/about/) - A lightweigt toolkit to deploy NixOS systems, remotely or locally.
* [kubenix](https://github.com/xtruder/kubenix) - Kubernetes resource builder using nix.
* [morph](https://github.com/DBCDK/morph) - A tool for managing existing NixOS hosts.
* [nixery](https://github.com/google/nixery) - Container registry which builds images ad-hoc via Nix.
* [nixops](https://github.com/NixOS/nixops) - Deploy using Nix.
* [nixos-shell](https://github.com/Mic92/nixos-shell) - Simple headless VM configuration using Nix (similar to Vagrant).
* [terraform-nixos](https://github.com/tweag/terraform-nixos) - A set of Terraform modules that are designed to deploy NixOS.
* [terranix](https://terranix.org) - Use Nix and the NixOS module system to write your Terraform code.

## Command-Line Tools

* [comma](https://github.com/Shopify/comma) - Quickly run any binary; wraps together `nix run` and `nix-index`.
* [nixfmt](https://github.com/serokell/nixfmt) - A formatter for Nix code, intended to easily apply a uniform style.
* [nix-diff](https://github.com/Gabriel439/nix-diff) - Explain why two Nix derivations differ.
* [nix-index](https://github.com/bennofs/nix-index) - Quickly locate nix packages with specific files.
* [nix-prefetch](https://github.com/msteen/nix-prefetch) - Universal tool to update source checksums.

## Development

* [arion](https://github.com/hercules-ci/arion) - Run docker-compose with help from Nix/NixOS.
* [cached-nix-shell](https://github.com/xzfc/cached-nix-shell) - A `nix-shell` replacementt that uses caching to open subsequent shells quickly. 
* [Cachix](https://cachix.org/) - Hosted binary cache service.
* [gitignore.nix](https://github.com/hercules-ci/gitignore.nix) - Most feature complete and easy to use .gitignore integration.
* [lorri](https://github.com/target/lorri/) - A much better `nix-shell` for development.
* [niv](https://github.com/nmattia/niv/) - Easy dependency management for Nix projects.
* [nix-direnv](https://github.com/nix-community/nix-direnv) - A fast loader and flake-compliant configuration for the direnv environment auto-loader.
* [nix-review](https://github.com/Mic92/nix-review) - The best tool to verify that a pull-request in nixpkgs is building properly.
* [pre-commit-hooks.nix](https://github.com/hercules-ci/pre-commit-hooks.nix) - Run linters/formatters at commit time and on your CI.

## Programming Languages

### Elm

* [elm2nix](https://github.com/hercules-ci/elm2nix) - Convert elm.json into Nix expressions.
* [Nix Elm Tools](https://github.com/turboMaCk/nix-elm-tools) - Elm language community tooling for Nix and NixOS users.

### Haskell

* [cabal2nix](https://github.com/NixOS/cabal2nix) - Converts a Cabal file into a Nix build expression.
* [snack](https://github.com/nmattia/snack/) - Nix-based incremental build tool for Haskell projects.
* [stack2nix](https://github.com/input-output-hk/stack2nix) - Generate nix expressions for Haskell projects.
* [nix-haskell-mode](https://github.com/matthewbauer/nix-haskell-mode) - Automatic Haskell setup in Emacs.
* [haskell.nix](https://github.com/input-output-hk/haskell.nix) - Alternative Haskell Infrastructure for Nixpkgs.

### Node.js

* [napalm](https://github.com/nmattia/napalm) - Support for building npm packages in Nix and lightweight npm registry.
* [node2nix](https://github.com/svanderburg/node2nix) - Generate nix expressions from a package.lock npm file.
* [yarn2nix](https://github.com/moretea/yarn2nix) - Generate nix expressions from a yarn.lock file.

### PureScript

* [easy-purescript-nix](https://github.com/justinwoo/easy-purescript-nix) - Easy PureScript (and other tools) with Nix.

### Python

* [mach-nix](https://github.com/DavHau/mach-nix) - Tool to create highly reproducible python environments.
* [poetry2nix](https://github.com/nix-community/poetry2nix) - Build Python packages directly from [Poetry's](https://python-poetry.org/) poetry.lock. No conversion step needed.
* [pypi2nix](https://github.com/nix-community/pypi2nix) - Generate Nix expressions for Python packages.

### Ruby

* [bundix](https://github.com/manveru/bundix) - Generates a Nix expression for your Bundler-managed application.

### Rust

* [carnix](https://nest.pijul.com/pmeunier/carnix) - Carnix is a compiler from the Cargo.lock files produced by cargo to Nix expressions.
* [fenix](https://github.com/nix-community/fenix) - Rust nightly toolchains and rust analyzer nightly for nix.
* [naersk](https://github.com/nmattia/naersk) - Build Rust packages directly from Cargo.lock. No conversion step needed.

## NixOS Modules

* [Musnix](https://github.com/musnix/musnix) - Real-time audio in NixOS.
* [nixcloud-webservices](https://github.com/nixcloud/nixcloud-webservices) - Focuses on ease of deployment of web-related technologies.
* [Simple Nixos Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - A complete mailserver managed with NixOS modules.

## Overlays

* [awesome-nix-hpc](https://github.com/freuk/awesome-nix-hpc) - High Performance Computing package sets.
* [home-manager](https://github.com/rycee/home-manager) - Manager user configuration just like NixOS.
* [nix-bitcoin](https://github.com/fort-nix/nix-bitcoin) - Nix packages and nixos modules for Bitcoin nodes with higher layer protocols with an emphasis on security.
* [nix-darwin](https://github.com/LnL7/nix-darwin) - Manage macOS configuration just like on NixOS.
* [nixpkgs-mozilla](https://github.com/mozilla/nixpkgs-mozilla) - Mozilla's overlay with bleeding Rust and Firefox.
* [nixpkgs-wayland](https://github.com/colemickens/nixpkgs-wayland) - Bleeding edge Wayland packages.
* [NUR](https://github.com/nix-community/NUR/) - Nix User Repositories. The mother of all overlays.

## Community

* [#nix:matrix.org (Unofficial)](https://matrix.to/#/#nix:matrix.org)
* [#nixos on FreeNode](https://webchat.freenode.net/?channels=nixos)
* [Discord - Nix/Nixos (Unofficial)](https://discord.gg/BMUCQx6)
* [Discourse](https://discourse.nixos.org/) - The best place to get help and discuss nix-related topic.
* [Wiki (Unofficial)](https://nixos.wiki)
