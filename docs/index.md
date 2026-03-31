---
layout: default
---

# Introduction

Creating a new Rust project is as easy as typing `cargo new <project_name>`
but often, you need more than what `cargo new` gives you.

This is when [cargo generate](https://github.com/cargo-generate/cargo-generate)
comes into play:

> cargo-generate is a developer tool to help you get up and running quickly
  with a new Rust project by leveraging a pre-existing git repository as a template.

This is a teeny tiny template to get you started with a new Rust project.

## Instructions

### Project creation

* Install `cargo generate` (version >= 11.0).

  ```sh
  cargo install cargo-generate --locked
  ```

* Create your project with this template.

  ```sh
  cargo generate --git https://github.com/katallaxie/template-rust.git
  ```

* `cd` into your project.

* Edit your project according to your own needs by
  adding what's necessary and removing what you don't like.

* Create a [new](https://github.com/new) empty repository (do not initialize it
  with a README, a `.gitignore` or a license).

* Follow GitHub instructions to "push an existing repository from the command line".