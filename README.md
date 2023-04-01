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
* [Virtualisation](#virtualisation)
* [Command-Line Tools](#command-line-tools)
* [Development](#development)
* [DevOps](#devops)
* [Programming Languages](#programming-languages)
    * [Arduino](#arduino)
    * [Clojure](#clojure)
    * [Crystal](#crystal)
    * [Elm](#elm)
    * [Haskell](#haskell)
    * [Node.js](#nodejs)
    * [PHP](#php)
    * [PureScript](#purescript)
    * [Python](#python)
    * [Ruby](#ruby)
    * [Rust](#rust)
    * [Scala](#scala)
* [NixOS Modules](#nixos-modules)
* [NixOS Configuration Editors](#nixos-configuration-editors)
* [Overlays](#overlays)
* [Community](#community)

## Resources

### Learning

* [How to Learn Nix](https://ianthehenry.com/posts/how-to-learn-nix/) - It's like a Let's Play, but for obscure software documentation.
* [Nix Notes](https://github.com/noteed/nix-notes) - A collection of short notes about Nix, each contributing to the same virtual machine image.
* [Nix Pills](https://nixos.org/guides/nix-pills/) - The best way to learn, with examples.
* [Nix Shorts](https://github.com/justinwoo/nix-shorts/) - A collection of short notes about Nix.
* [nix.dev](https://nix.dev/) - An opinionated guide for developers about getting things done using the Nix ecosystem.
* [Tour of Nix](https://nixcloud.io/tour) - An online interactive tutorial on Nix language constructs.

### Discovery

* [Hound](https://search.nix.gsc.io) - Handily search across all or selected Nix-related repositories.
* [Nix Package Versions](https://lazamar.co.uk/nix-versions/) - Find all versions of a package that were available in a channel and the revision you can download it from.
* [Noogle](https://noogle.dev/) - Nix API search engine allowing to search functions based on their types and other attributes.
* [Pkgs on Nix](https://pkgs.on-nix.com/) - A database with Nix packages at all versions, from all channels.
* [Home Manager Option Search](https://mipmip.github.io/home-manager-option-search/) - Search through all 2000+ Home Manager options and read how to use them.

### Newsletters

* [NixOS Weekly](https://weekly.nixos.org/) - *The* newsletter to stay informed about community updates.

## Installation Media

* [nixos-generators](https://github.com/nix-community/nixos-generators) -  Take a NixOS config and build multiple different images types including VirtualBox VMs, Azure images, and installation ISOs.
* [nixos-up](https://github.com/samuela/nixos-up) - Super easy NixOS installer that can be used from the installation ISO.

## Channel History

* [Channel History](https://channels.nix.gsc.io) - Get historical git commits for Nix channels.
* [Nix Infra Status](https://status.nixos.org) - Get the age and current git commit of each Nix channel.
* [Nix Review Tools Reports](https://malob.github.io/nix-review-tools-reports/) - Reports showing problematic dependencies (dependencies causing the most failed builds) for major Hydra jobsets.
* [nixpkgs PR tracker](https://nixpk.gs/pr-tracker.html) - A tracker for whether a PR has made it into a channel yet.

## Deployment Tools

* [bento](https://github.com/rapenne-s/bento/) - A KISS deployment tool to keep your NixOS fleet (servers & workstations) up to date.
* [Colmena](https://github.com/zhaofengli/colmena) - A simple, stateless NixOS deployment tool modeled after NixOps and morph.
* [deploy-rs](https://github.com/serokell/deploy-rs) - A simple multi-profile Nix-flake deploy tool.
* [krops](https://cgit.krebsco.de/krops/about/) - A lightweight toolkit to deploy NixOS systems, remotely or locally.
* [KubeNix](https://github.com/xtruder/kubenix) - A Kubernetes resource builder using Nix.
* [KuberNix](https://github.com/saschagrunert/kubernix) - Single-dependency Kubernetes clusters via Nix packages.
* [morph](https://github.com/DBCDK/morph) - A tool for managing existing NixOS hosts.
* [Nixery](https://github.com/tazjin/nixery) - A Docker-compatible container registry which builds images ad-hoc via Nix.
* [Nixinate](https://github.com/MatthewCroughan/nixinate) - A Nix flake library to provide app outputs for managing existing NixOS hosts over SSH.
* [NixOps](https://github.com/NixOS/nixops) - The official Nix deployment tool, compatible with AWS, Hetzner, and more.
* [pushnix](https://github.com/arnarg/pushnix) - Simple cli utility that pushes NixOS configuration and triggers a rebuild using ssh.
* [terraform-nixos](https://github.com/tweag/terraform-nixos) - A set of Terraform modules designed to deploy NixOS.
* [terranix](https://terranix.org) - Use Nix and the NixOS module system to write your Terraform code.

## Virtualisation
* [nixos-shell](https://github.com/Mic92/nixos-shell) - Simple headless VM configuration using Nix (similar to Vagrant).
* [extra-container](https://github.com/erikarvstedt/extra-container) - Run declarative NixOS containers from the command line.
* [microvm](https://github.com/astro/microvm.nix) - NixOS-based MicroVMs.

## Command-Line Tools

* [alejandra](https://github.com/kamadorueda/alejandra) - An opinionated Nix code formatter optimized for speed and consistency.
* [comma](https://github.com/nix-community/comma) - Quickly run any binary; wraps together `nix run` and `nix-index`.
* [deadnix](https://github.com/astro/deadnix) - Scan Nix files for dead code.
* [manix](https://github.com/mlvzk/manix) - Find configuration options and function documentation for Nixpkgs, NixOS, and Home Manager.
* [nixfmt](https://github.com/serokell/nixfmt) - A formatter for Nix code, intended to easily apply a uniform style.
* [nixpkgs-fmt](https://github.com/nix-community/nixpkgs-fmt) - Nix code formatter for nixpkgs.
* [nixpkgs-hammering](https://github.com/jtojnar/nixpkgs-hammering) - An opinionated linter for Nixpkgs package expressions.
* [nix-alien](https://github.com/thiagokokada/nix-alien) - Run unpatched binaries on Nix/NixOS easily.
* [nix-diff](https://github.com/Gabriella439/nix-diff) - A tool to explain why two Nix derivations differ.
* [nix-du](https://github.com/symphorien/nix-du) - Visualise which gc-roots to delete to free some space in your Nix store.
* [nix-index](https://github.com/bennofs/nix-index) - Quickly locate Nix packages with specific files.
* [nix-init](https://github.com/nix-community/nix-init) - Generate Nix packages from URLs with hash prefetching, dependency inference, license detection, and more.
* [nix-prefetch](https://github.com/msteen/nix-prefetch) - A universal tool for updating source checksums.
* [nix-tree](https://github.com/utdemir/nix-tree) - Interactively browse the dependency graph of Nix derivations.
* [nurl](https://github.com/nix-community/nurl) - Generate Nix fetcher calls from repository URLs.
* [nvd](https://gitlab.com/khumba/nvd) - Diff package versions between two store paths; it's especially useful for comparing NixOS generations on rebuild.
* [statix](https://github.com/nerdypepper/statix) - A linter/fixer to check for and fix antipatterns in Nix code.

## Development

* [Arion](https://github.com/hercules-ci/arion) - Run `docker-compose` with help from Nix/NixOS.
* [cached-nix-shell](https://github.com/xzfc/cached-nix-shell) - A `nix-shell` replacement that uses caching to open subsequent shells quickly.
* [Cachix](https://cachix.org/) - Hosted binary cache service; free for open-source projects.
* [devshell](https://github.com/numtide/devshell) - `mkShell` with extra bits and a toml config option to be able to onboard non-nix users.
* [dream2nix](https://github.com/nix-community/dream2nix) - A framework for automatically converting packages from other build systems to Nix.
* [flake.parts](https://github.com/hercules-ci/flake-parts) - Minimal Nix modules framework for Flakes: split your flakes into modules and get things done with community modules.
* [flake-utils](https://github.com/numtide/flake-utils) - Pure Nix flake utility functions to help with writing flakes.
* [flake-utils-plus](https://github.com/gytis-ivaskevicius/flake-utils-plus) - A lightweight Nix library flake for painless NixOS flake configuration.
* [gitignore.nix](https://github.com/hercules-ci/gitignore.nix) - The most feature-complete and easy-to-use `.gitignore` integration.
* [haumea](https://github.com/nix-community/haumea) - Filesystem-based module system for the Nix language similar to traditional programming languages, with support for file hierarchy and visibility.
* [lorri](https://github.com/nix-community/lorri/) - A much better `nix-shell` for development that augments direnv.
* [nil](https://github.com/oxalica/nil) - NIx Language server, an incremental analysis assistent for writing in Nix.
* [niv](https://github.com/nmattia/niv/) - Easy dependency management for Nix projects with package pinning.
* [nix-direnv](https://github.com/nix-community/nix-direnv) - A fast loader and flake-compliant configuration for the direnv environment auto-loader.
* [nix-update](https://github.com/Mic92/nix-update) - Update versions/source hashes of nix packages.
* [nixpkgs-review](https://github.com/Mic92/nixpkgs-review) - The best tool to verify that a pull-request in Nixpkgs is building properly.
* [pre-commit-hooks.nix](https://github.com/cachix/pre-commit-hooks.nix) - Run linters/formatters at commit time and on your CI.
* [rnix-lsp](https://github.com/nix-community/rnix-lsp) - A syntax-checking language server for Nix.
* [robotnix](https://github.com/danielfullmer/robotnix) - A declarative and reproducible build system for Android (AOSP) images.

## DevOps

* [Makes](https://github.com/fluidattacks/makes) - A Nix-based CI/CD pipeline framework for building, testing, and releasing projects in any language, from anywhere. 
* [Standard](https://github.com/divnix/std) - An opinionated Nix Flakes framework to keep Nix code in large projects organized, accompanied by a friendly CLI/TUI optized for DevOps scenarios.

## Programming Languages

### Arduino

* [nixduino](https://github.com/boredom101/nixduino) - Nix-based tool to help build Arduino sketches.

### Clojure

* [clj-nix](https://github.com/jlesquembre/clj-nix) - Nix helper functions for Clojure projects.

### Crystal

* [crystal2nix](https://github.com/nix-community/crystal2nix) - Convert `shard.lock` into Nix expressions.

### Elm

* [elm2nix](https://github.com/cachix/elm2nix) - Convert `elm.json` into Nix expressions.

### Haskell

* [cabal2nix](https://github.com/NixOS/cabal2nix) - Converts a Cabal file into a Nix build expression.
* [haskell-flake](https://github.com/srid/haskell-flake) - A `flake-parts` Nix module for Haskell development.
* [haskell.nix](https://github.com/input-output-hk/haskell.nix) - Alternative Haskell Infrastructure for Nixpkgs.
* [nix-haskell-mode](https://github.com/matthewbauer/nix-haskell-mode) - Automatic Haskell setup in Emacs.
* [nixkell](https://github.com/pwm/nixkell) - A Haskell project template using Nix and direnv.

### Node.js

* [Napalm](https://github.com/nix-community/napalm) - Support for building npm packages in Nix with a lightweight npm registry.
* [node2nix](https://github.com/svanderburg/node2nix) - Generate Nix expression from a `package.json` (or `package-lock.json`) (to be stored as files).
* [npmlock2nix](https://github.com/nix-community/npmlock2nix) - Generate Nix expressions from a `package-lock.json` (in-memory), primarily for web projects.

### PHP

* [composer2nix](https://github.com/svanderburg/composer2nix) - Generate Nix expressions to build composer packages.
* [composer-plugin-nixify](https://github.com/stephank/composer-plugin-nixify) - Composer plugin to help with Nix packaging.
* [composition-c4](https://github.com/fossar/composition-c4) - Support for building composer packages from a `composer.lock` (using IFD).
* [nix-phps](https://github.com/fossar/nix-phps) - Flake containing old and unmaintained PHP versions (intended for CI use).
* [nix-shell](https://github.com/loophp/nix-shell/) - Nix shells for PHP development.

### PureScript

* [Easy PureScript Nix](https://github.com/justinwoo/easy-purescript-nix) - A project to easily use PureScript and other tools with Nix.
* [purs-nix](https://github.com/purs-nix/purs-nix) - CLI and library combo designed for managing PureScript projects using Nix. It provides a Nix API that can be used within your projects, as well as a command-line interface for managing your development process.

### Python

* [mach-nix](https://github.com/DavHau/mach-nix) - Tool to create highly reproducible python environments.
* [poetry2nix](https://github.com/nix-community/poetry2nix) - Build Python packages directly from [Poetry's](https://python-poetry.org/) `poetry.lock`. No conversion step needed.
* [pypi2nix](https://github.com/nix-community/pypi2nix) - Generate Nix expressions for Python packages.

### Ruby

* [Bundix](https://github.com/nix-community/bundix) - Generates a Nix expression for your Bundler-managed application.
* [ruby-nix](https://github.com/sagittaros/ruby-nix) - Generates reproducible ruby/bundler app environment with Nix.

### Rust

* [cargo2nix](https://github.com/cargo2nix/cargo2nix) - Granular caching, development shell, Nix & Rust integration.
* [crane](https://github.com/ipetkov/crane) - A Nix library for building Cargo projects with incremental artifact caching.
* [fenix](https://github.com/nix-community/fenix) - Rust toolchains and Rust analyzer nightly for nix.
* [naersk](https://github.com/nmattia/naersk) - Build Rust packages directly from `Cargo.lock`. No conversion step needed.
* [nix-cargo-integration](https://github.com/yusdacra/nix-cargo-integration) - A library that allows easy and effortless integration for Cargo projects.
* [nixpkgs-mozilla](https://github.com/mozilla/nixpkgs-mozilla) - Mozilla's overlay with Rust toolchains and Firefox.
* [rust-nix-templater](https://github.com/yusdacra/rust-nix-templater) - Generates Nix build and development files for Rust projects.
* [rust-overlay](https://github.com/oxalica/rust-overlay) - Pure and reproducible nix overlay of binary distributed Rust toolchains.

### Scala

* [sbt-derivation](https://github.com/zaninime/sbt-derivation) - mkDerivation for sbt, similar to buildGoModule.

## NixOS Modules

* [base16.nix](https://github.com/SenchoPens/base16.nix) - Flake way to theme programs in [base16](https://github.com/chriskempson/base16) colorschemes, mustache template support included.
* [Home Manager](https://github.com/nix-community/home-manager) - Manage your user configuration just like NixOS.
* [musnix](https://github.com/musnix/musnix) - Do real-time audio work in NixOS.
* [nixcloud-webservices](https://github.com/nixcloud/nixcloud-webservices) - A Nixpkgs extension with a focus on ease of deployment of web-related technologies.
* [NixVim](https://github.com/pta2002/nixvim) - A NeoVim distribution built with Nix modules and Nixpkgs.
* [Simple Nixos Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - A complete mailserver, managed with NixOS modules.
* [Stylix](https://github.com/danth/stylix) - System-wide colorscheming and typography for NixOS.
* [nix-bitcoin](https://github.com/fort-nix/nix-bitcoin) - Modules and packages for Bitcoin nodes with higher-layer protocols with an emphasis on security.

## NixOS Configuration Editors

### Desktop apps

* [NixOS Configuration Editor](https://github.com/vlinkz/nixos-conf-editor) - Graphical editor for NixOS configuration. Desktop app in Rust and GTK.
* [Nix Software Center](https://github.com/vlinkz/nix-software-center) - Install and manage Nix packages. Desktop app in Rust and GTK.

### Webinterface

* [MyNixOS](https://mynixos.com/) - Graphical editor for Nix flakes. Create and manage configurations and modules for NixOS and Nix home-manager. Rather a Nix generator than a Nix editor, because it does not allow to import Nix files.

## Overlays

* [awesome-nix-hpc](https://github.com/freuk/awesome-nix-hpc) - High Performance Computing package sets.
* [nix-darwin](https://github.com/LnL7/nix-darwin) - Manage macOS configuration just like on NixOS.
* [nixpkgs-firefox-darwin](https://github.com/bandithedoge/nixpkgs-firefox-darwin) - Automatically updated Firefox binary packages for macOS.
* [nixpkgs-wayland](https://github.com/nix-community/nixpkgs-wayland) - Bleeding-edge Wayland packages.
* [NUR](https://github.com/nix-community/NUR/) - Nix User Repositories. The mother of all overlays, allowing access to user repositories and installing packages via attributes.

## Community

* [#nix:nixos.org](https://matrix.to/#/#nix:nixos.org)
* [#nixos on Libera.Chat](https://web.libera.chat/?nick=Guest?#nixos)
* [Discord - Nix/Nixos (Unofficial)](https://discord.gg/BMUCQx6)
* [Discourse](https://discourse.nixos.org/) - The best place to get help and discuss Nix-related topics.
* [NixCon](https://nixcon.org/) - The annual community conference for contributors and users of Nix and NixOS.
* [Wiki (Unofficial)](https://nixos.wiki)
