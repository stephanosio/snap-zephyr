# Snap packages for Zephyr RTOS development tools

[Snap](https://snapcraft.io) is a cross-distro package manager for Linux.

You can use it to install the following Zephyr RTOS development tools:
* Zephyr Cross Compiler Toolchains ([zephyr-crosstool-ng](https://github.com/stephanosio/zephyr-crosstool-ng))
* Zephyr QEMU ([zephyr-qemu](https://github.com/stephanosio/zephyr-qemu))
* Zephyr OpenOCD ([zephyr-openocd](https://github.com/stephanosio/zephyr-openocd))

## Getting Started

### Install snapd

Follow the installation instructions on the [Snapcraft website](https://snapcraft.io/docs/installing-snapd).

_NOTE: If you are using Ubuntu, `snapd` is installed by default._

### Install packages

```sh
sudo snap install zephyr-crosstool-*
sudo snap install zephyr-qemu
```

## Package List

|                    Name                   |                                       Description                                       |
|:-----------------------------------------:|:---------------------------------------------------------------------------------------:|
|              zephyr-crosstool             |                 Cross Compiler Toolchain (meta package for all targets)                 |
|          zephyr-crosstool-aarch64         |               ARM (AArch64) Cross Compiler Toolchain (aarch64-zephyr-elf)               |
|            zephyr-crosstool-arc           |                      ARC Cross Compiler Toolchain (arc-zephyr-elf)                      |
|            zephyr-crosstool-arm           |          ARM (AArch32; Cortex-A/R/M) Cross Compiler Toolchain (arm-zephyr-eabi)         |
|           zephyr-crosstool-nios2          |                    NIOS2 Cross Compiler Toolchain (nios2-zephyr-elf)                    |
|           zephyr-crosstool-riscv          |                   RISC-V Cross Compiler Toolchain (riscv64-zephyr-elf)                  |
|           zephyr-crosstool-sparc          |                    SPARC Cross Compiler Toolchain (sparc-zephyr-elf)                    |
|            zephyr-crosstool-x86           |                  x86(-64) Cross Compiler Toolchain (x86_64-zephyr-elf)                  |
|   zephyr-crosstool-xtensa-intel-apl-adsp  |    Xtensa Intel APL ADSP Cross Compiler Toolchain (xtensa-intel_apl_adsp_zephyr-elf)    |
|   zephyr-crosstool-xtensa-intel-bdw-adsp  |    Xtensa Intel BDW ADSP Cross Compiler Toolchain (xtensa-intel_apl_adsp_zephyr-elf)    |
|   zephyr-crosstool-xtensa-intel-byt-adsp  |    Xtensa Intel BYT ADSP Cross Compiler Toolchain (xtensa-intel_apl_adsp_zephyr-elf)    |
|    zephyr-crosstool-xtensa-intel-s1000    |       Xtensa Intel S1000 Cross Compiler Toolchain (xtensa-intel_s1000_zephyr-elf)       |
|    zephyr-crosstool-xtensa-nxp-imx-adsp   |      Xtensa NXP i.MX ADSP Cross Compiler Toolchain (xtensa-nxp_imx_adsp_zephyr-elf)     |
|   zephyr-crosstool-xtensa-nxp-imx8m-adsp  |   Xtensa NXP i.MX 8M ADSP Cross Compiler Toolchain (xtensa-nxp_imx8m_adsp_zephyr-elf)   |
|     zephyr-crosstool-xtensa-sample-ctlr   | Xtensa Sample Controller Cross Compiler Toolchain (xtensa-sample_controller_zephyr-elf) |
|                zephyr-qemu                |                                       Zephyr QEMU                                       |
|               zephyr-openocd              |                                      Zephyr OpenOCD                                     |
