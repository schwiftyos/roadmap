# Roadmap

## Completed

- [x] OS README
- [x] Roadmap README
- [x] [Evolution](https://github.com/schwiftyos/evolution) repository

## WIP

- [ ] Determine project and OS name
- [ ] Determine default File System
- [ ] Determine default Kernel
- [ ] Adopt Swift 6 language mode
- [ ] Application/System Permission library
  - See [permissions](https://github.com/schwiftyos/permissions)
- [ ] Single dependency build path
  - See [proposal](https://github.com/schwiftyos/evolution/blob/main/proposals/0001-single-dependency-build-directory.md)
- [ ] SwiftPM patch to enable dynamic linking on Linux
  - See [pitch](https://forums.swift.org/t/77605)
  - Probably need to implement custom solution
    - Relates to [single dependency build path](https://github.com/schwiftyos/evolution/blob/main/proposals/0001-single-dependency-build-directory.md)
- [ ] Better tooling for easier IoT, robotics, embedded workflows
  - [ ] See [Swift Consolidate Plugin](https://github.com/schwiftyos/swift-consolidate-plugin)
  - [ ] VS Code extensions?

## TODO

### Compatibility

- [ ] Patch Kernel to support more architectures
- [ ] Patch Kernel to support native Swift code
- [ ] Build and test for multiple architectures, and in parallel (similar to [Xcode Cloud](https://developer.apple.com/xcode-cloud/))
- [ ] Allow/enable multi-versioning of installed programs (custom package manager, similar to [pacman](https://wiki.archlinux.org/title/Pacman)) 
     
### Optimizations

- [ ] Utilize Protocol Buffers
  - [ ] Patch [sourcekit-lsp](https://github.com/swiftlang/sourcekit-lsp) (and support a rolling release?)
- [ ] Optimize Swift toolchain(s)
- [ ] Production-only dependencies (super minified, and stripped, binary size only suitable for production use)
- [ ] Improve compilation performance
  - [ ] Swift Package Manager optimizations
  - [ ] Directly influenced by [single dependency build directory proposal](https://github.com/schwiftyos/evolution/blob/main/proposals/0001-single-dependency-build-directory.md)
- [ ] Use stack-based array value types from Swift 6.1+ when available

### Features

- [ ] Install script
- [ ] Advanced System Search (similar to Spotlight on macOS)
- [ ] Widgets
- [ ] Keyboard shortcuts
- [ ] User-friendly UI
- [ ] Continuity with other systems (sync user calendars, contacts, messages, etc)
- [ ] Decentralized services
- [ ] Machine Learning security protections
- [ ] Machine Learning features ("AI" / LLM)

### Integrations

- [ ] Custom IDE?
- [ ] SwiftCrossUI Backend
- [ ] App Store
- [ ] Secure payment system
