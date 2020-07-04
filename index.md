# Embedded Rust documentation

Welcome to an overview of the documentation provided by the [embedded Working
Group][wg]. All of these projects are managed by [the resources team][team].

Many of these resources take the form of "books"; we collectively call these
"The embedded Rust Bookshelf". Some are large, some are small.

[wg]: https://github.com/rust-embedded/wg
[team]: https://github.com/rust-embedded/wg#the-resources-team

All these resources assume that you have done some Rust programming before.

# Learn about embedded development

If you are familiar with Rust but not with embedded development, this is the
spot for you! All of these resources assume that you have done some Rust
programming on the desktop, but that you have not done any embedded development
before.

## The Discovery book

[The Discovery book][discovery] will teach you about microcontrollers,
peripherals, sensors and bare metal programming through a series of small, fun
projects that you'll develop in Rust.

[discovery]: discovery/index.html

# Learn embedded Rust

If you are familiar with embedded development and familiar with Rust but have
not used Rust for embedded development then these resources are for you. All
these resources assume that you have done embedded development before, but not
in any specific language.

## The embedded Rust book

Also known as "the book" by the embedded Rust community. [The embedded Rust
book][book] will get you up to speed with embedded Rust development and then
teach you how to effectively use the language (AKA patterns) to build more
correct embedded software.

[book]: book/index.html

## Frequently Asked Questions

You can find our list of FAQ [here](faq.html).

# Write embedded Rust

Once you have learned the basics these resources will make writing embedded
programs easier.

- [Awesome embedded Rust], a curated list of embedded and no-std crates.

[Awesome embedded Rust]: https://github.com/rust-embedded/awesome-embedded-rust

# Master embedded Rust

Once you're quite familiar with embedded Rust development, you may find these
advanced resources useful.

## The embedonomicon

For those that want to dive into the implementation of the foundational crates
of the embedded ecosystem. [The embedonomicon] will guide you through the abyss
of linker scripts, symbols and ABIs. You'll learn about linker script and the
language features that let you control the ABI of crates by creating a `no_std`
program for the ARM Cortex-M architecture from scratch.

[The embedonomicon]:embedonomicon/index.html

# Write Operating System in embedded Rust

If you are interested in Operating Systems and embedded Rust development, you
may find these resources useful.

## Operating System development tutorials in Rust on the Raspberry Pi

[Operating System development tutorials in Rust on the Raspberry Pi] is a
tutorial series for hobby OS developers who are new to ARM's 64 bit ARMv8-A
architecture. The tutorials will give a guided, step-by-step tour of how to
write a monolithic Operating System kernel for an embedded system from
scratch. They cover implementation of common Operating Systems tasks, like
writing to the serial console, setting up virtual memory and handling hardware
exceptions. All while leveraging Rust's unique features to provide for safety
and speed.

[Operating System development tutorials in Rust on the Raspberry Pi]: https://github.com/rust-embedded/rust-raspberrypi-OS-tutorials
