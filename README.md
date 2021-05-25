# Awesome Nix [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [<img src="https://nixos.org/logo/nixos-logo-only-hires.png" width="200" align="right" alt="NixOS">](https://nixos.org)

> A curated list of the best resources in the Nix community.

[Nix](https://github.com/nixos/nix) is a powerful package manager for Linux and other Unix systems that makes package management reliable and reproducible.

*Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.*

## Contents

* [Resources](#resources)
    * [Learning](#learning)
    * [Discovery](#discovery)
    * [Newsletters](#newsletters)
* [Installation Media](#installation-media)
* [Channel History](#channel-history)
* [Deployment Tools](#deployment-tools)
* [Command-Line Tools](#command-line-tools)
* [Development](#development)
* [Programming Languages](#programming-languages)
    * [Arduino](#arduino)
    * [Crystal](#crystal)
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
* [Nix Pills](https://nixos.org/nixos/nix-pills/) - The best way to learn, with examples.
* [Nix Shorts](https://github.com/justinwoo/nix-shorts/) - A collection of short notes about Nix.
* [nix.dev](https://nix.dev/) - An opinionated guide for developers about getting things done using the Nix ecosystem.
* [Tour of Nix](https://nixcloud.io/tour) - An online interactive tutorial on Nix language constructs.

### Discovery

* [Hound](https://search.nix.gsc.io) - Handily search across all or selected Nix-related repositories.
* [Nixpkgs Database](https://kamadorueda.github.io/nixpkgs-db/) - A database with Nix packages at all versions, from all channels.

### Newsletters

* [NixOS Weekly](https://weekly.nixos.org/) - *The* newsletter to stay informed about community updates.

## Installation Media

* [nixos-generators](https://github.com/nix-community/nixos-generators) -  Take a NixOS config and build multiple different images types including VirtualBox VMs, Azure images, and installation ISOs.
* [nixos-up](https://github.com/samuela/nixos-up) - Super easy NixOS installer that can be used from the installation ISO.

## Channel History

* [Channel History](https://channels.nix.gsc.io) - Get historical git commits for Nix channels.
* [Nix Infra Status](https://status.nixos.org) - Get the age and current git commit of each Nix channel.

## Deployment Tools

* [Colmena](https://github.com/zhaofengli/colmena) - A simple, stateless NixOS deployment tool modeled after NixOps and morph.
* [krops](https://cgit.krebsco.de/krops/about/) - A lightweight toolkit to deploy NixOS systems, remotely or locally.
* [KubeNix](https://github.com/xtruder/kubenix) - A Kubernetes resource builder using Nix.
* [KuberNix](https://github.com/saschagrunert/kubernix) - Single-dependency Kubernetes clusters via Nix packages.
* [morph](https://github.com/DBCDK/morph) - A tool for managing existing NixOS hosts.
* [Nixery](https://github.com/google/nixery) - A Docker-compatible container registry which builds images ad-hoc via Nix.
* [NixOps](https://github.com/NixOS/nixops) - The official Nix deployment tool, compatible with AWS, Hetzner, and more.
* [nixos-shell](https://github.com/Mic92/nixos-shell) - Simple headless VM configuration using Nix (similar to Vagrant).
* [pushnix](https://github.com/arnarg/pushnix) - Simple cli utility that pushes NixOS configuration and triggers a rebuild using ssh.
* [terraform-nixos](https://github.com/tweag/terraform-nixos) - A set of Terraform modules designed to deploy NixOS.
* [terranix](https://terranix.org) - Use Nix and the NixOS module system to write your Terraform code.

## Command-Line Tools

* [comma](https://github.com/Shopify/comma) - Quickly run any binary; wraps together `nix run` and `nix-index`.
* [nixfmt](https://github.com/serokell/nixfmt) - A formatter for Nix code, intended to easily apply a uniform style.
* [nixpkgs-fmt](https://github.com/nix-community/nixpkgs-fmt) - Nix code formatter for nixpkgs.
* [nixpkgs-hammering](https://github.com/jtojnar/nixpkgs-hammering) - Beat your package expressions into a shape.
* [nix-diff](https://github.com/Gabriel439/nix-diff) - A tool to explain why two Nix derivations differ.
* [nix-index](https://github.com/bennofs/nix-index) - Quickly locate Nix packages with specific files.
* [nix-prefetch](https://github.com/msteen/nix-prefetch) - A universal tool for updating source checksums.
* [nix-tree](https://github.com/utdemir/nix-tree) - Interactively browse the dependency graph of Nix derivations.

## Development

* [Arion](https://github.com/hercules-ci/arion) - Run `docker-compose` with help from Nix/NixOS.
* [cached-nix-shell](https://github.com/xzfc/cached-nix-shell) - A `nix-shell` replacement that uses caching to open subsequent shells quickly.
* [Cachix](https://cachix.org/) - Hosted binary cache service; free for open-source projects.
* [gitignore.nix](https://github.com/hercules-ci/gitignore.nix) - The most feature-complete and easy-to-use `.gitignore` integration.
* [lorri](https://github.com/target/lorri/) - A much better `nix-shell` for development that augments direnv.
* [niv](https://github.com/nmattia/niv/) - Easy dependency management for Nix projects with package pinning.
* [nix-direnv](https://github.com/nix-community/nix-direnv) - A fast loader and flake-compliant configuration for the direnv environment auto-loader.
* [nixpkgs-review](https://github.com/Mic92/nixpkgs-review) - The best tool to verify that a pull-request in Nixpkgs is building properly.
* [pre-commit-hooks.nix](https://github.com/cachix/pre-commit-hooks.nix) - Run linters/formatters at commit time and on your CI.

## Programming Languages

### Arduino

* [nixduino](https://github.com/boredom101/nixduino) - Nix-based tool to help build Arduino sketches.

### Crystal

* [crystal2nix](https://github.com/nix-community/crystal2nix) - Convert `shard.lock` into Nix expressions.

### Elm

* [elm2nix](https://github.com/hercules-ci/elm2nix) - Convert `elm.json` into Nix expressions.

### Haskell

* [cabal2nix](https://github.com/NixOS/cabal2nix) - Converts a Cabal file into a Nix build expression.
* [stack2nix](https://github.com/input-output-hk/stack2nix) - Generate nix expressions for Haskell projects.
* [nix-haskell-mode](https://github.com/matthewbauer/nix-haskell-mode) - Automatic Haskell setup in Emacs.
* [haskell.nix](https://github.com/input-output-hk/haskell.nix) - Alternative Haskell Infrastructure for Nixpkgs.
* [nixkell](https://github.com/pwm/nixkell) - A Haskell project template using Nix and direnv.

### Node.js

* [Napalm](https://github.com/nmattia/napalm) - Support for building npm packages in Nix with a lightweight npm registry.
* [node2nix](https://github.com/svanderburg/node2nix) - Generate Nix expressions from a `package.lock` npm file.
* [yarn2nix](https://github.com/nix-community/yarn2nix) - Generate Nix expressions from a `yarn.lock` file.

### PureScript

* [Easy PureScript Nix](https://github.com/justinwoo/easy-purescript-nix) - A project to easily use PureScript and other tools with Nix.

### Python

* [mach-nix](https://github.com/DavHau/mach-nix) - Tool to create highly reproducible python environments.
* [poetry2nix](https://github.com/nix-community/poetry2nix) - Build Python packages directly from [Poetry's](https://python-poetry.org/) `poetry.lock`. No conversion step needed.
* [pypi2nix](https://github.com/nix-community/pypi2nix) - Generate Nix expressions for Python packages.

### Ruby

* [Bundix](https://github.com/nix-community/bundix) - Generates a Nix expression for your Bundler-managed application.

### Rust

* [fenix](https://github.com/nix-community/fenix) - Rust toolchains and rust analyzer nightly for nix.
* [naersk](https://github.com/nmattia/naersk) - Build Rust packages directly from `Cargo.lock`. No conversion step needed.
* [rust-nix-templater](https://github.com/yusdacra/rust-nix-templater) - Generates Nix build and development files for Rust projects.

## NixOS Modules

* [musnix](https://github.com/musnix/musnix) - Do real-time audio work in NixOS.
* [nixcloud-webservices](https://github.com/nixcloud/nixcloud-webservices) - A Nixpkgs extension with a focus on ease of deployment of web-related technologies.
* [Simple Nixos Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - A complete mailserver, managed with NixOS modules.

## Overlays

* [awesome-nix-hpc](https://github.com/freuk/awesome-nix-hpc) - High Performance Computing package sets.
* [Home Manager](https://github.com/nix-community/home-manager) - Manage your user configuration just like NixOS.
* [nix-bitcoin](https://github.com/fort-nix/nix-bitcoin) - Nix packages and NixOS modules for Bitcoin nodes with higher-layer protocols with an emphasis on security.
* [nix-darwin](https://github.com/LnL7/nix-darwin) - Manage macOS configuration just like on NixOS.
* [nixpkgs-mozilla](https://github.com/mozilla/nixpkgs-mozilla) - Mozilla's overlay with bleeding-edge Rust and Firefox.
* [nixpkgs-wayland](https://github.com/colemickens/nixpkgs-wayland) - Bleeding-edge Wayland packages.
* [NUR](https://github.com/nix-community/NUR/) - Nix User Repositories. The mother of all overlays, allowing access to user repositories and installing packages via attributes.

## Community

* [#nix:nixos.org](https://matrix.to/#/#nix:nixos.org)
* [#nixos on FreeNode](https://webchat.freenode.net/?channels=nixos)
* [Discord - Nix/Nixos (Unofficial)](https://discord.gg/BMUCQx6)
* [Discourse](https://discourse.nixos.org/) - The best place to get help and discuss Nix-related topics.
* [NixCon](https://nixcon.org/) - The annual community conference for contributors and users of Nix and NixOS.
* [Wiki (Unofficial)](https://nixos.wiki)
