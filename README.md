# Thomas Tuul

**Embedded C/C++ & Linux developer focused on systems programming, robust software architecture and developer tooling.**

I work primarily with C and C++ on Linux, with an emphasis on maintainable systems software, reproducible builds, testing and practical engineering.

Currently developing **[Sliverbar](https://github.com/thomastuul/sliverbar)** — a native C17 desktop panel for Linux/X11.

## Featured project

### [Sliverbar](https://github.com/thomastuul/sliverbar)

A lightweight native desktop panel written in **C17** for Linux systems running X11.

[![Sliverbar desktop panel](https://raw.githubusercontent.com/thomastuul/sliverbar/master/docs/images/sliverbar-blocks.png)](https://github.com/thomastuul/sliverbar)

Sliverbar uses **XCB, Cairo, Pango and EWMH** and provides enhanced integration with bspwm while remaining usable with other EWMH-compatible window managers.

Highlights:

* Native X11 panel and system tray
* C17 with CMake
* XCB, Cairo, Pango and GLib/GIO
* EWMH and bspwm workspace integration
* Native launcher, popups and power controls
* GCC/Clang builds with ASan/UBSan and clang-tidy
* Automated testing under Xvfb
* Debian/Fedora packaging and GitHub Actions releases

**[View Sliverbar on GitHub →](https://github.com/thomastuul/sliverbar)**

## Engineering focus

* Embedded software development in **C and C++**
* Linux systems programming
* Software architecture and maintainability
* Microcontrollers and hardware-near development
* Bootloaders and communication protocols
* Debugging and fault analysis
* Automated testing and CI
* Static analysis and reproducible builds

## Toolchain

`C` · `C++` · `Bash` · `Python` · `CMake` · `Git` · `GDB` · `Docker` · `Podman` · `GitHub Actions` · `Linux` · `X11` · `XCB`

## Linux projects

### [bspwm desktop configuration](https://github.com/thomastuul/bspwm)

My event-driven Linux/X11 desktop environment based on bspwm and sxhkd.

It contains the desktop configuration and the original Bash-based Lemonbar panel that served as the behavioral reference for Sliverbar.

### [Dotfiles](https://github.com/thomastuul/Dotfiles)

Linux configuration, shell environment and supporting command-line tools.

## Engineering principles

I prefer software that is understandable, testable and robust rather than merely functional.

My development approach emphasizes:

* clear interfaces and ownership
* explicit failure handling
* reproducible development environments
* automated verification
* incremental refactoring
* documented architectural decisions
* static analysis and sanitizers as part of normal development

I also use AI-assisted development tools where they improve analysis, testing, review and implementation while keeping engineering decisions and validation explicit.
