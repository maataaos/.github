## MAATAA OS · माता कारकसंविधा

A Rust operating system for microcontrollers. Every task runs in its own memory-protected region, and new features are installed as signed, fuel-limited WebAssembly apps without reflashing the kernel.

**Status:** alpha (v0.1.0-alpha.9). It runs on one development board (STM32F411, NUCLEO-F411RE) and in QEMU. It is not certified for safety functions, and secure boot and an outside security review are still ahead.

### Repositories

| Repository | What it is |
| --- | --- |
| [os](https://github.com/wortforfilms/os) | The kernel, the WebAssembly runtime, the store, the signing and host tools, and the tests |
| [maataa-os-site](https://github.com/wortforfilms/maataa-os-site) | The website, [maataa-os.allb.xyz](https://maataa-os.allb.xyz) |

### Check it yourself

Every claim has a test or a board log:

- [Evidence matrix](https://github.com/wortforfilms/os/blob/main/docs/EVIDENCE_MATRIX.md): each feature, the script that tests it, and whether it ran on the board
- [Threat model](https://github.com/wortforfilms/os/blob/main/docs/SECURITY_THREAT_MODEL.md): what is protected today and what is not yet

### Contact

- General: [hello@allb.xyz](mailto:hello@allb.xyz)
- Partners and pilots: [partners@allb.xyz](mailto:partners@allb.xyz)
- Security reports: [security@allb.xyz](mailto:security@allb.xyz), see our [security policy](https://github.com/maataaos/.github/blob/main/SECURITY.md)

Built in Delhi by ALL B Vegan Private Limited.
