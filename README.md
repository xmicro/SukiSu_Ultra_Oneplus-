<div align="center">

# OnePlus ● SukiSU Ultra ● SUSFS

### Wild Fork

</div>

---

This repository provides GitHub Actions workflows to automatically build flashable **AnyKernel3 ZIPs** for multiple OnePlus devices with integrated **SukiSU Ultra** and **SUSFS** support.

## 🌟 Features

- **SukiSU Ultra** - Advanced kernel-level root solution
- **SUSFS (Super User File System)** - Enhanced file system security and isolation
- **Baseband Guard LSM** - Optional additional security layer
- **WireGuard** - Modern VPN protocol built into the kernel
- **Magic Mount** - Advanced mounting capabilities
- **TMPFS_XATTR / Mountify** - Extended attribute support for tmpfs
- **BBR & ECN** - Advanced TCP congestion control and network optimizations
- **sched_ext** - Extensible scheduler framework for supported 6.6 kernels
- **hmbird conversion** - Optimized handling for certain 6.6 kernel cases
- **AnyKernel3 ZIPs** - Flashable kernel packages generated automatically

## 📱 Supported Devices

OnePlus devices supported by the available configuration files.

Check the available configs here:

```text
configs/
```

## 🚀 Installation

1. Download the latest kernel ZIP for your device from **Releases**.
2. Flash the **AnyKernel3 ZIP** with **Kernel Flasher** or **SukiSU Manager**.
3. Enable **KPM** if required.
4. Reboot your device.
5. Enjoy SukiSU Ultra with SUSFS support.

> ⚠️ **Warning**
>
> Always back up your data before flashing custom kernels.
>
> Make sure you have a working recovery method and know how to restore your device if something goes wrong.

## 🔧 Build Artifacts

Each build can produce:

- **Flashable AnyKernel3 ZIP** - Ready-to-flash kernel package
- **Build metadata** - Device, branch, kernel, and build information
- **Release notes** - Generated information for published releases
- **Build logs** - Useful for debugging failed builds

## 🛠️ Building

Builds are handled through GitHub Actions.

Go to:

```text
Actions → Build and Release OnePlus Kernels → Run workflow
```

Use the SukiSU Ultra option required by your workflow configuration.

Example:

```json
[{"type":"susfs", "enable":true}]
```

## 🛠️ Building Locally

To build manually, clone the repository:

```bash
git clone https://github.com/Bouteillepleine/SukiSu_Ultra_Oneplus-.git
cd Oneplus-Kernels-SukiSu
```

Then follow the workflow scripts for your target device and configuration.

## 📋 Requirements

- Unlocked bootloader
- Compatible OnePlus device from the supported list
- Matching OS and kernel version
- Basic knowledge of flashing custom kernels
- A known restore method in case flashing fails

## 🔗 Links

- [SukiSU Ultra](https://github.com/SukiSU-Ultra/SukiSU-Ultra)
- [SUSFS](https://gitlab.com/simonpunk/susfs4ksu)
- [Kernel Flasher](https://github.com/fatalcoder524/KernelFlasher)
- [AnyKernel3](https://github.com/osm0sis/AnyKernel3)
- [OnePlusOSS](https://github.com/OnePlusOSS)

## 💝 Donations

Any and all donations are appreciated!

- PayPal: [paypal.me/fatalcoder524](https://paypal.me/fatalcoder524)
- DM on Telegram for UPI donations!

## 🤝 Acknowledgments

This project would not be possible without:

- **KernelSU-Next**
- **SukiSU Ultra**
- **Wild+ / Wild Fork** references
- **susfs4ksu** by simonpunk
- **AnyKernel3** by osm0sis and contributors
- **OnePlusOSS** official kernel sources
- Community contributors for testing, feedback, and improvements

---

<div align="center">

**Built for SukiSU Ultra users**

</div>
