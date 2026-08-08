# Thomas Tuul

**Embedded C/C++ & Linux developer focused on systems programming, hardware-near software and robust software architecture.**

I work primarily with C and C++ on Linux — from direct embedded-controller communication and hardware control to native Linux desktop software.

My engineering focus is on maintainable systems software, explicit error handling, automated testing, static analysis and reproducible builds.

## Featured projects

### [Sliverbar](https://github.com/thomastuul/sliverbar)

A lightweight native **C17 desktop panel for Linux/X11**, built with XCB, Cairo, Pango and EWMH.

[![Sliverbar desktop panel](https://raw.githubusercontent.com/thomastuul/sliverbar/master/docs/images/sliverbar-blocks.png)](https://github.com/thomastuul/sliverbar)

Sliverbar creates and manages its X11 dock window directly and provides enhanced bspwm integration while remaining usable with other EWMH-compatible window managers.

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

---

### [Tuxedo-Fan-Control](https://github.com/thomastuul/Tuxedo-Fan-Control)

A hardware-near **C++ fan-control daemon for compatible Tuxedo/Clevo laptops** that communicates directly with the laptop's embedded controller.

[![Tuxedo Fan Control curves](https://raw.githubusercontent.com/thomastuul/Tuxedo-Fan-Control/master/doc/fan-curve.png)](https://github.com/thomastuul/Tuxedo-Fan-Control)

The controller reads temperature data and controls the fan through direct x86 I/O-port access to the embedded controller, applying selectable TUXEDO fan profiles.

Highlights:

* Direct embedded-controller communication
* Privileged x86 I/O-port access with `ioperm()`, `inb()` and `outb()`
* Explicit EC transaction error handling and bounded timeouts
* Testable hardware abstraction without requiring a physical EC
* CMake and CTest
* clang-format and clang-tidy quality checks
* Containerized reproducible build and validation environment
* systemd integration and Debian packaging
* GitHub Actions package and release workflow

**[View Tuxedo-Fan-Control on GitHub →](https://github.com/thomastuul/Tuxedo-Fan-Control)**

## Engineering focus

* Embedded and hardware-near software development in **C and C++**
* Linux systems programming
* Software architecture and maintainability
* Microcontrollers and embedded controllers
* Bootloaders and communication protocols
* Hardware/software interfaces
* Debugging and fault analysis
* Automated testing and CI
* Static analysis and reproducible builds

## Toolchain

`C` · `C++` · `Bash` · `Python` · `CMake` · `Git` · `GDB` · `Docker` · `Podman` · `GitHub Actions` · `Linux` · `systemd` · `X11` · `XCB`

## Other Linux projects

### [bspwm desktop configuration](https://github.com/thomastuul/bspwm)

Event-driven Linux/X11 desktop environment based on bspwm and sxhkd, including the original Bash-based Lemonbar implementation that served as a behavioral reference for Sliverbar.

### [Dotfiles](https://github.com/thomastuul/Dotfiles)

Linux configuration, shell environment and supporting command-line tools.

## Engineering principles

I prefer software that is understandable, testable and robust rather than merely functional.

My development approach emphasizes:

* clear interfaces and ownership
* explicit failure handling
* defensive handling of hardware and external interfaces
* reproducible development environments
* automated verification
* incremental refactoring
* documented architectural decisions
* static analysis and sanitizers as part of normal development

I also use AI-assisted development tools where they improve analysis, testing, review and implementation while keeping engineering decisions and validation explicit.
