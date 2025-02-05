# Roadmap

## Table of Contents
- [Philosophy](#philosophy)
  - [Software Engineering](#software-engineering)
- [Pricing](#pricing)
- [Features](#features)
- [Decentralization](#decentralization)
- [Privacy](#privacy)
  - [Permissions](#permissions)
- [Security](#security)
- [AI/LLM](#aillm)
- [Under the hook](#under-the-hood)

## Philosophy

"Its **my** system"

It should work on any system, independent of architecture. You control every aspect of it. You can still game on it.

### Software Engineering

This OS will have a central system directory where builds, and their outputs, will reside. This reduces overall disk usage and saves space. You only need one version of the dependencies installed on your system to work with them. This also enables powerful dynamic linking, further reducing program sizes and saving disk space. Does not only apply to Swift.

Native support for IoT, robotics, embedded.

## Pricing

Its free (and open source!).

## Features

- Arch/FreeBSD based (best performance and control)
- Open Source
- Architecture agnostic
- Best Linux file system on the market
- Elevated and streamlined developer experience
- Application permissions
- Advanced System Search (similar to Spotlight on macOS)
- Continuity with supporting systems
- App Store
- Widgets
- Keyboard shortcuts
- Opt-in machine learning features

## Decentralization

"Plays well with others"

Decentralization is a key part in making it play well with others. It will not favorite, lock-in or lock-down certain features from one source.

## Privacy

"You're not allowed to do that"

Privacy is a human right. Your data is your own and up to you on how it is used/shared.

See more about [permissions](#permissions).

### Permissions

Application and System Permissions will be a big part of this OS. This allows the user full control over their system and to inform them about what programs have what permissions.

## Security

The OS is mainly targeting the Swift Programming Language, which is a memory-safe language.

## AI/LLM

Machine learning features are opt-in. We recognize they are powerful tools, but they should also be used when appropriate.

## Under the hood

- File System: Undecided (patched OpenZFS, Btrfs or ext4)
- Kernel: patched Arch Linux/FreeBSD (Zircon was mentioned; a custom Swift kernel was also mentioned)
- Display Server: Hyprland (Wayland; using a Swift UI library was mentioned)
