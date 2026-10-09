# ShadiOS

**An experimental PlayStation 4 emulator port for iOS.**

ShadiOS is an open-source research project exploring the possibility of bringing the shadPS4 emulator to Apple mobile devices, including iPhone and iPad.

The project aims to adapt the stable Windows shadPS4 codebase for iOS while investigating ARM64 CPU execution, graphics compatibility, and Apple's platform restrictions.

> **Status:** Early-stage research and development. PS4 game compatibility on iOS has not yet been established.

## Project Goals

- Explore porting shadPS4 to iOS.
- Adapt Windows-specific components for Apple's platforms.
- Investigate x86-64 CPU emulation and ARM64 execution.
- Explore Vulkan compatibility through MoltenVK and Apple's Metal graphics API.
- Develop an iOS application interface.
- Investigate JIT execution and iOS signing requirements.
- Gradually test compatibility with homebrew applications and PS4 software.

## Target Platforms

- iPhone
- iPad
- Apple Silicon devices for development and testing

## Development Roadmap

- [ ] Review the shadPS4 source code and licensing requirements.
- [ ] Identify Windows-specific dependencies.
- [ ] Evaluate existing ARM64 and iOS compatibility work.
- [ ] Establish a build environment for iOS.
- [ ] Investigate CPU emulation and recompilation.
- [ ] Develop a compatible graphics backend.
- [ ] Create a minimal iOS application prototype.
- [ ] Build and test an IPA on a physical device.
- [ ] Investigate homebrew compatibility.
- [ ] Improve performance and game compatibility.

## Technical Challenges

ShadPS4 was originally designed for desktop platforms. Porting it to iOS involves significant engineering work, including:

- **CPU execution:** Running PS4 x86-64 code on ARM64 hardware.
- **Graphics:** Adapting Vulkan-based rendering and shader handling to the iOS graphics environment.
- **System APIs:** Replacing or adapting Windows-specific functionality.
- **JIT execution:** Working within iOS code-signing and executable-memory restrictions.
- **Performance:** Optimizing emulation for mobile hardware, thermals, and memory limits.

A successful build does not guarantee that commercial PS4 games will boot or run at playable speeds.

## Hardware Testing

Initial testing target:

- **Device:** iPhone 13
- **Chip:** Apple A15 Bionic
- **Operating system:** iOS
- **Development target:** A minimal working prototype

Actual compatibility will depend on the implementation and testing results.

## Upstream Project

ShadiOS is intended to build upon the open-source shadPS4 project.

- Original project: https://github.com/shadps4-emu/shadPS4
- Official website: https://shadps4.net/

ShadiOS is an independent experimental project and is not an official shadPS4 release.

## Legal Notice

ShadiOS does not distribute copyrighted PlayStation 4 games, firmware, system software, or proprietary Sony files.

Users are responsible for complying with applicable laws and obtaining any required software and firmware legally.

The project will follow the applicable licenses and attribution requirements of its upstream projects and dependencies.

## Disclaimer

ShadiOS is experimental software intended for research and development. It is not affiliated with, endorsed by, or sponsored by Sony Interactive Entertainment.

Features, compatibility, and performance are not guaranteed.

## Contributions

Contributions, research, testing, and technical discussions are welcome.

Please open an issue to discuss proposed features, compatibility findings, or potential improvements before submitting major changes.

## License

The license for ShadiOS and its original code will be established before public distribution. Upstream shadPS4 code and third-party components remain subject to their respective licenses.

---

**ShadiOS — Exploring PlayStation 4 emulation on iOS.**
