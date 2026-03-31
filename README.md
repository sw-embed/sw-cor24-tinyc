# sw-cor24-tinyc

Native COR24 C compiler written in C — runs directly on COR24 FPGA hardware.

> **Status: Future** — This repo is a placeholder. The native C compiler
> has not been started yet. The cross-compiler lives at
> [sw-cor24-x-tinyc](https://github.com/sw-embed/sw-cor24-x-tinyc).

## Vision

A self-hosted C compiler that runs on COR24 hardware, enabling on-device
application development without a host PC. Written in C and bootstrapped
using the cross-compiler (`sw-cor24-x-tinyc`).

## Naming Convention

| Repo | Role | Written in | Runs on |
|------|------|-----------|---------|
| `sw-cor24-x-tinyc` | Cross C compiler | Rust | Host (x86/ARM) |
| `sw-cor24-tinyc` | Native C compiler | C | COR24 FPGA |

The `x-` prefix denotes cross-tools that run on a host machine.
The plain name is the native tool that runs on COR24 hardware.

## License

See [LICENSE](LICENSE).
