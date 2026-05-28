# Valeryn Kernel - Citrus / Chime

<p align="center">
<a href="https://github.com/KeshaGvozd/valeryn_xiaomi_sm6115/releases"><img src="https://img.shields.io/github/v/release/KeshaGvozd/valeryn_xiaomi_sm6115?style=for-the-badge&logo=github&color=blue" alt="GitHub release"></a>
</p>

[🇷🇺 Читать на русском](README_RU.md)

**Android 15-16 Kernel for Poco M3 / Redmi 9T (Citrus/Chime)**
Inspired by the ShockWAVE Kernel philosophy.

### Changelog:
* **KernelSU Next (Legacy):** Updated to exact legacy version `v3.2.0` (build `33132`).
* **Universal Manager Support:** Removed `KSU_MANAGER_PACKAGE` restriction. Use KSUN, KSU, ShockWAVE, KOWSU, or MamboSU manager – only signature verification is enforced.
* **WLAN Update:** `qca_cld3` driver built-in natively (`=y`) to fix Wi-Fi issues on read-only vendor partitions.
* **Hook Mode:** Scope-minimized manual hooks integrated directly into VFS and input subsystems. No kprobes.
* **Packaging:** Automated CI via GitHub Actions with AnyKernel3 citrus packaging.

### Credits:
- `@frstprjkt` for the original Valeryn Kernel Tree.
- The ShockWAVE team for the KSU signature spoofing philosophy.