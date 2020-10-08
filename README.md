![Doctave logo](./src/assets/gh-readme-logo.png)

Doctave CLI
===========

The DoctaveCLI is an opinionated documentation site generator that converts your Markdown files into
a beautiful documentation site with minimal effort.

The Doctave CLI is not a generic static site generator - it is only meant for generating
documentation sites from Markdown. This allows the tool to be much simpler than other solutions,
with fewer configuration steps.

This open source CLI is built and maintained by [Doctave](https://www.doctave.com).

* [Docs](https://cli.doctave.com) (built with Doctave)
* [Tutorial](https://cli.doctave.com/tutorial)

## Features

Doctave comes with a number of documentation-specific features out of the box. No plugins needed.

- [Mermaid.js](https://mermaid-js.github.io/) diagrams
- Full-text search
- Local live-reloading server
- Responsive design
- Dark mode
- GitHub flavored markdown
- Minimal configuration
- Fast build, built in Rust

## Screenshots

You can customize the color scheme and logo to match your own style. Below are two examples: one
with Doctave's own color scheme, and another customized color scheme.

Light                                             | Dark                                                    |
--------------------------------------------------|---------------------------------------------------------|
![Exmple 1](./docs/_include/assets/example-1.png) | ![Example 2](./docs/_include/assets/example-1-dark.png) |
![Exmple 2](./docs/_include/assets/example-2.png) | ![Example 2](./docs/_include/assets/example-2-dark.png) |

## Installation

There are a few installation options for Doctave. If you would like another installation option,
please open an issue for it.

### Precompiled binaries

Doctave build precompiled binaries for Mac, Linux, and Windows, which you can download from the
[latest release](https://github.com/Doctave/doctave-cli/releases/latest).

### Homebrew

Doctave maintains its own [homebrew tap](https://github.com/Doctave/homebrew-doctave), and you can
install Doctave via the following command:

```
$ brew install doctave/doctave/doctave-cli
```

This will take a few minutes as Doctave is compiled from scratch for your machine.

### Cargo (Rust package manager)

You can also use the Rust package manager, Cargo, to install Doctave. Currently Doctave is not
listed on crates.io, but you can install it directly from GitHub:

```
$ cargo install --git https://github.com/Doctave/doctave-cli
```

## Getting started

Once you have Doctave installed, you can run the `init` command to create an initial docs site:

```
$ doctave init
```

Then, run the `serve` command to preview your site locally.

```
Doctave CLI | Serve
🚀 Starting development server...

Server running on http://0.0.0.0:4001/

```
