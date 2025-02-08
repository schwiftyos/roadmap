# Roadmap

## Completed

- [x] OS README
- [x] Roadmap README

## WIP

- [ ] Adopt Swift 6 language mode
- [ ] Determine project and OS name
- [ ] Determine default File System
- [ ] Determine default Kernel
- [ ] Application/System Permission library (see [permissions](https://github.com/schwiftyos/schwifty-permissions))
- [ ] SwiftPM patch to enable dynamic linking on Linux (see [pitch](https://forums.swift.org/t/77605))
- [ ] Better tooling for easier IoT, robotics, embedded workflows
  - [ ] See [Swift Consolidate Plugin](https://github.com/RandomHashTags/swift-consolidate-plugin)
  - [ ] VS Code extensions?

## TODO

### Compatibility

- [ ] Patch Kernel to support more architectures
- [ ] Patch Kernel to support native Swift code
- [ ] Build and test for multiple architectures, and in parallel (similar to [Xcode Cloud](https://developer.apple.com/xcode-cloud/))
     
### Optimizations

- [ ] Enable a central directory for dependencies and their build outputs (more research required)
  - [ ] SwiftLang patch
  - [ ] [SwiftPM](https://github.com/swiftlang/swift-package-manager) patch
  - [ ] [Swiftly](https://github.com/swiftlang/swiftly) patch
- [ ] Utilize Protocol Buffers
  - [ ] Patch [sourcekit-lsp](https://github.com/swiftlang/sourcekit-lsp) (and support a rolling release?)
- [ ] Optimize Swift toolchain(s)
- [ ] Production-only dependencies (super minified, and stripped, binary size only suitable for production use)
- [ ] Use stack-based array value types from Swift 6.1+ when available
     
### Community

- [ ] Evolution repository
- [ ] Custom IDE?

### Features

- [ ] Install script
- [ ] Advanced System Search (similar to Spotlight on macOS)
- [ ] App Store
- [ ] Widgets
- [ ] Secure payment system
- [ ] Keyboard shortcuts
- [ ] User-friendly UI
- [ ] Continuity with other systems (sync user calendars, contacts, messages, etc)
- [ ] Allow/enable multi-versioning of installed programs
- [ ] Decentralized services
- [ ] Machine Learning security protections
- [ ] Machine Learning features ("AI" / LLM)
