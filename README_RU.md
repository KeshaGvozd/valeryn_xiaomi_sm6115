# Valeryn Kernel - Citrus / Chime

<p align="center">
<a href="https://github.com/KeshaGvozd/valeryn_xiaomi_sm6115/releases"><img src="https://img.shields.io/github/v/release/KeshaGvozd/valeryn_xiaomi_sm6115?style=for-the-badge&logo=github&color=blue" alt="GitHub release"></a>
</p>

[🇬🇧 Read in English](README.md)

**Ядро для Android 15-16 под Poco M3 / Redmi 9T (Citrus/Chime)**
Вдохновлено философией ShockWAVE Kernel.

### Список изменений:
* **KernelSU Next (Legacy):** Обновлено до версии `v3.2.0-legacy` (сборка `33132`).
* **Универсальная поддержка менеджеров:** Удалено ограничение `KSU_MANAGER_PACKAGE`. Используйте менеджеры KSUN, KSU, ShockWAVE, KOWSU или MamboSU — проверка идет только по криптографической подписи.
* **Обновление WLAN:** Драйвер `qca_cld3` встроен напрямую в ядро (`=y`) для исправления отвала Wi-Fi на заблокированных vendor-разделах.
* **Режим хуков:** Ручные хуки (scope-minimized) встроены напрямую в VFS и подсистему ввода. Никаких kprobes.
* **Упаковка:** Автоматическая сборка через GitHub Actions с установщиком AnyKernel3 (citrus).

### Благодарности:
- `@frstprjkt` за оригинальное дерево Valeryn Kernel.
- Команде ShockWAVE за подход к верификации KSU.