# Valeryn Kernel for Poco M3 (Citrus)

<p align="center">
<a href="https://github.com/KeshaGvozd/valeryn_xiaomi_sm6115/releases"><img src="https://img.shields.io/github/v/release/KeshaGvozd/valeryn_xiaomi_sm6115?style=for-the-badge&logo=github&color=blue" alt="GitHub release"></a>
</p>

[🇷🇺 Читать на русском](README_RU.md)

This is a custom kernel project for the **Poco M3 (Citrus)**, built with a focus on stability, seamless root integration, and Android 16 compatibility.

## Release Overview
* **KernelSU Next (Legacy)**: Ships with the actively maintained legacy branch (build `33132`), specifically required for full compatibility and stability on 4.19 non-GKI kernels.
* **Universal Manager Support**: KernelSU signature verification has been modified to rely solely on the cryptographic signature. Inspired by projects like ShockWAVE, this implementation allows users to seamlessly use either the official manager or spoofed variants.
* **Built-in WLAN Integration**: The `qca_cld3` Wi-Fi driver is now compiled natively into the kernel image (`=y`), bypassing read-only vendor partition constraints.

## Installation Guide
1. **Prepare Recovery**: Ensure you are using a recent version of TWRP or OrangeFox Recovery.
2. **Flash the Kernel**: Download the package from the Releases page and flash the `zip`.
3. **Manager Installation**: Install the KernelSU Next Manager (official or spoofed).
4. **Reboot**: Restart the device.