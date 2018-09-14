### perf

|Release  |Upstream   | Backport  |                                               Subject|
|---------|-----------|-----------|-------------------------------------------------------|
|v4.19-rc1|[b9b77222d4ff](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=b9b77222d4ff)|[d65d6855d968](https://github.com/cavium/thunderx-linux/commit/d65d6855d968)|perf vendor events arm64: Update ThunderX2 implementation defined pmu core events|
|v4.17-rc1|[a8685f088819](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=a8685f088819)|[009ea3d7413d](https://github.com/cavium/thunderx-linux/commit/009ea3d7413d)|perf vendor events arm64: Enable JSON events for ThunderX2 B0|
|v4.17-rc1|[ae43053bd259](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=ae43053bd259)|[7bb6b41207d2](https://github.com/cavium/thunderx-linux/commit/7bb6b41207d2)|perf vendor events arm64: Fixup ThunderX2 to use recommended events|
|v4.17-rc1|[360b7b03afee](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=360b7b03afee)|[feac00637c28](https://github.com/cavium/thunderx-linux/commit/feac00637c28)|perf vendor events arm64: Add armv8-recommended.json|
|v4.17-rc1|[e9d32c1bf0cd](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=e9d32c1bf0cd)|[c30afaf2b7e9](https://github.com/cavium/thunderx-linux/commit/c30afaf2b7e9)|perf vendor events: Add support for arch standard events|
|v4.17-rc1|[e3b9f1e81de2](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=e3b9f1e81de2)|[2fc133bae258](https://github.com/cavium/thunderx-linux/commit/2fc133bae258)|perf vendor events arm64: Relocate ThunderX2 JSON to cavium subdirectory|
|v4.17-rc1|[51ce1dcc5d0d](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=51ce1dcc5d0d)|[e654b9575ff1](https://github.com/cavium/thunderx-linux/commit/e654b9575ff1)|perf vendor events: Add support for pmu events vendor subdirectory|
|v4.17-rc1|[6f2f2ca3454e](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=6f2f2ca3454e)|[35dfb3617ee2](https://github.com/cavium/thunderx-linux/commit/35dfb3617ee2)|perf vendor events: Drop support for unused topic directories|
|v4.17-rc1|[931ef5dc5c18](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=931ef5dc5c18)|[0a4b2635e89a](https://github.com/cavium/thunderx-linux/commit/0a4b2635e89a)|perf vendor events: Fix error code in json_events()|
|v4.17-rc1|[4c0ab1605205](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=4c0ab1605205)|[11796c4117ef](https://github.com/cavium/thunderx-linux/commit/11796c4117ef)|perf vendor events: Drop incomplete multiple mapfile support|

### ThunderX2 I2C
|Release  |Upstream   | Backport  |                                               Subject|
|---------|-----------|-----------|-------------------------------------------------------|
|v4.18|[5eb173f5c8f3](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=5eb173f5c8f3)|[c5bc4177f7f7](https://github.com/cavium/thunderx-linux/commit/c5bc4177f7f7)|i2c: xlp9xx: Fix case where SSIF read transaction completes early|
|v4.18-rc1|[88b4116e7e98](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=88b4116e7e98)|[e244e8c80e92](https://github.com/cavium/thunderx-linux/commit/e244e8c80e92)|i2c: xlp9xx: Make sure the transfer size is not more than I2C_SMBUS_BLOCK_SIZE|
|v4.18-rc1|[8d504d804ab6](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=8d504d804ab6)|[514e9cba2f9b](https://github.com/cavium/thunderx-linux/commit/514e9cba2f9b)|i2c: xlp9xx: Fix issue seen when updating receive length|
|v4.18-rc1|[40f4e372cba8](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=40f4e372cba8)|[1a4a455fb12e](https://github.com/cavium/thunderx-linux/commit/1a4a455fb12e)|i2c: xlp9xx: Add support for SMBAlert|
|v4.17-rc1|[e349d7d08e70](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=e349d7d08e70)|[87795e623196](https://github.com/cavium/thunderx-linux/commit/87795e623196)|i2c: xlp9xx: Handle NACK on DATA properly|
|v4.17-rc1|[d3898a78521c](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=d3898a78521c)|[ab536da560b3](https://github.com/cavium/thunderx-linux/commit/ab536da560b3)|i2c: xlp9xx: Check for Bus state before every transfer|
|v4.17-rc1|[41b1d4de9632](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=41b1d4de9632)|[a317b2e3c0d4](https://github.com/cavium/thunderx-linux/commit/a317b2e3c0d4)|i2c: xlp9xx: Handle transactions with I2C_M_RECV_LEN properly|
|v4.17-rc1|[c2a3b3cce8df](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=c2a3b3cce8df)|[152e63cd21a2](https://github.com/cavium/thunderx-linux/commit/152e63cd21a2)|i2c: xlp9xx: return ENXIO on slave address NACK|
### CPPC
|Release  |Upstream   | Backport  |                                               Subject|
|---------|-----------|-----------|-------------------------------------------------------|
|v4.19-rc1|[33477d84c26b](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=33477d84c26b)|[1b82d469ba57](https://github.com/cavium/thunderx-linux/commit/1b82d469ba57)|cpufreq / CPPC: Add cpuinfo_cur_freq support for CPPC|
|v4.18-rc1|[8f8027c5f935](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=8f8027c5f935)|[2449ffc56308](https://github.com/cavium/thunderx-linux/commit/2449ffc56308)|mailbox: PCC: erroneous error message when parsing ACPI PCCT|
|v4.18-rc1|[58e1c03536c9](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=58e1c03536c9)|[9061e1a7ba86](https://github.com/cavium/thunderx-linux/commit/9061e1a7ba86)|ACPI / CPPC: Fix invalid PCC channel status errors|
|v4.18-rc1|[b382bf885269](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=b382bf885269)|[b4a68cc9f7b6](https://github.com/cavium/thunderx-linux/commit/b4a68cc9f7b6)|ACPI / CPPC: Document CPPC sysfs interface|
|v4.18-rc1|[256f19d212f2](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=256f19d212f2)|[73211f996a08](https://github.com/cavium/thunderx-linux/commit/73211f996a08)|cpufreq / CPPC: Support for CPPC v3|
|v4.18-rc1|[6fa12d584dcb](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=6fa12d584dcb)|[79a4b49a8886](https://github.com/cavium/thunderx-linux/commit/79a4b49a8886)|ACPI / CPPC: Check for valid PCC subspace only if PCC is used|
|v4.18-rc1|[4773e77cdc9b](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=4773e77cdc9b)|[8879dc652d89](https://github.com/cavium/thunderx-linux/commit/8879dc652d89)|ACPI / CPPC: Add support for CPPC v3|
|v4.17-rc1|[b8b10bc2015c](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=b8b10bc2015c)|[a8c14eb7a50d](https://github.com/cavium/thunderx-linux/commit/a8c14eb7a50d)|cpufreq: CPPC: Don't set transition_latency|
|v4.17-rc1|[3d41386d556d](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=3d41386d556d)|[cd85a5df8582](https://github.com/cavium/thunderx-linux/commit/cd85a5df8582)|cpufreq: CPPC: Use transition_delay_us depending transition_latency|
|v4.17-rc1|[d29abc836843](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=d29abc836843)|[b679256bc6c1](https://github.com/cavium/thunderx-linux/commit/b679256bc6c1)|ACPI / CPPC: Update all pr_(debug/err) messages to log the susbspace id|
### KVM/Other
|Release  |Upstream   | Backport  |                                               Subject|
|---------|-----------|-----------|-------------------------------------------------------|
|v4.17-rc6|[711702b57cc3](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=711702b57cc3)|[6d625b313736](https://github.com/cavium/thunderx-linux/commit/6d625b313736)|KVM: arm/arm64: VGIC/ITS save/restore: protect kvm_read_guest() calls|
|v4.17-rc6|[bf308242ab98](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=bf308242ab98)|[05702baac530](https://github.com/cavium/thunderx-linux/commit/05702baac530)|KVM: arm/arm64: VGIC/ITS: protect kvm_read_guest() calls with SRCU lock|
|v4.17-rc6|[9c4188762f7f](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=9c4188762f7f)|[34cd437892f7](https://github.com/cavium/thunderx-linux/commit/34cd437892f7)|KVM: arm/arm64: VGIC/ITS: Promote irq_lock() in update_affinity|
|v4.17-rc6|[388d4359680b](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=388d4359680b)|[970432c05b0c](https://github.com/cavium/thunderx-linux/commit/970432c05b0c)|KVM: arm/arm64: Properly protect VGIC locks from IRQs|
|v4.17-rc7|[32c3fa7cdf0c](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=32c3fa7cdf0c)|[8a10d2f81f9d](https://github.com/cavium/thunderx-linux/commit/8a10d2f81f9d)|arm64: lse: Add early clobbers to some input/output asm operands|
|v4.17-rc5|[ae646f0b9ca1](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=ae646f0b9ca1)|[cfb9d7325ea7](https://github.com/cavium/thunderx-linux/commit/cfb9d7325ea7)|init: fix false positives in W+X checking|
### PCI
|Release  |Upstream   | Backport  |                                               Subject|
|---------|-----------|-----------|-------------------------------------------------------|
|v4.17-rc1|[204f4afa7ae5](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=204f4afa7ae5)|[ca9406b4bc1f](https://github.com/cavium/thunderx-linux/commit/ca9406b4bc1f)|PCI: Remove redundant probes for device reset support|
|v4.17-rc1|[5b0764cac9f1](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=5b0764cac9f1)|[ecc427c8c1e4](https://github.com/cavium/thunderx-linux/commit/ecc427c8c1e4)|PCI: Probe for device reset support during enumeration|
### IPMI backports
|Release  |Upstream   | Backport  |                                               Subject|
|---------|-----------|-----------|-------------------------------------------------------|
|v4.18-rc4|[2068db53b633](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=2068db53b633)|[edf7528320ce](https://github.com/cavium/thunderx-linux/commit/edf7528320ce)|ipmi: Cleanup oops on initialization failure|
|v4.18-rc1|[1211229399b3](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=1211229399b3)|[a33bdb8b38c8](https://github.com/cavium/thunderx-linux/commit/a33bdb8b38c8)|ipmi_ssif: Fix uninitialized variable issue|
|v4.18-rc1|[93c303d2045b](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=93c303d2045b)|[4cd1ad6be388](https://github.com/cavium/thunderx-linux/commit/4cd1ad6be388)|ipmi_si: Clean up shutdown a bit|
|v4.18-rc1|[6a0d23ed338e](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=6a0d23ed338e)|[702985a40e68](https://github.com/cavium/thunderx-linux/commit/702985a40e68)|ipmi: ipmi_unregister_smi() cannot fail, have it return void|
|v4.18-rc1|[7960f18a5647](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=7960f18a5647)|[9908249568b0](https://github.com/cavium/thunderx-linux/commit/9908249568b0)|ipmi_si: Convert over to a shutdown handler|
|v4.17-rc1|[71404a2f75c1](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=71404a2f75c1)|[e6b426eab6f4](https://github.com/cavium/thunderx-linux/commit/e6b426eab6f4)|ipmi: Consolidate cleanup code|
|v4.17-rc1|[cc095f0ac1f7](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=cc095f0ac1f7)|[c089191f2f0e](https://github.com/cavium/thunderx-linux/commit/c089191f2f0e)|ipmi: Fix some error cleanup issues|
|v4.18-rc1|[f0258c95304e](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=f0258c95304e)|[5d733761ce32](https://github.com/cavium/thunderx-linux/commit/5d733761ce32)|ipmi_ssif: Remove usecount handling|
|v4.18-rc1|[a313dec6401f](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=a313dec6401f)|[332a926ee532](https://github.com/cavium/thunderx-linux/commit/332a926ee532)|ipmi_ssif: Convert over to a shutdown handler|
|v4.18-rc1|[a567b6230066](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=a567b6230066)|[a549d292b669](https://github.com/cavium/thunderx-linux/commit/a549d292b669)|ipmi: Change ipmi_smi_t to struct ipmi_smi *|
|v4.18-rc1|[b7780dab90e8](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=b7780dab90e8)|[6e6fa8bb5910](https://github.com/cavium/thunderx-linux/commit/6e6fa8bb5910)|ipmi: Add shutdown functions for users and interfaces|
|v4.17-rc1|[4866b1dce038](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=4866b1dce038)|[9f56ba73b2c1](https://github.com/cavium/thunderx-linux/commit/9f56ba73b2c1)|ipmi: Remove ACPI SPMI probing from the SSIF (I2C) driver|
|v4.17-rc1|[f002612b9d86](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=f002612b9d86)|[50fd8b4047cf](https://github.com/cavium/thunderx-linux/commit/50fd8b4047cf)|ipmi_ssif: Fix kernel panic at msg_done_handler|
### kexec/kdump fixes
|Release  |Upstream   | Backport  |                                               Subject|
|---------|-----------|-----------|-------------------------------------------------------|
|v4.19-rc1|[2c870e61132c](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=2c870e61132c)|[8040fa9d9392](https://github.com/cavium/thunderx-linux/commit/8040fa9d9392)|arm64: fix ACPI dependencies|
|v4.19-rc1|[09ffcb0d718a](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=09ffcb0d718a)|[9f6f5aea4855](https://github.com/cavium/thunderx-linux/commit/9f6f5aea4855)|arm64: acpi: fix alignment fault in accessing ACPI|
|v4.19-rc1|[20d12cf99061](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=20d12cf99061)|[a67ea1e13ac6](https://github.com/cavium/thunderx-linux/commit/a67ea1e13ac6)|efi/arm: map UEFI memory map even w/o runtime services enabled|
|v4.19-rc1|[3ea86495aef2](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=3ea86495aef2)|[499cf7421f16](https://github.com/cavium/thunderx-linux/commit/499cf7421f16)|efi/arm: preserve early mapping of UEFI memory map longer for BGRT|
|v4.19-rc1|[5bcd44083a08](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=5bcd44083a08)|[d443daf87794](https://github.com/cavium/thunderx-linux/commit/d443daf87794)|drivers: acpi: add dependency of EFI for arm64|
|v4.19-rc1|[50d7ba36b916](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=50d7ba36b916)|[b6395e41f7e8](https://github.com/cavium/thunderx-linux/commit/b6395e41f7e8)|arm64: export memblock_reserve()d regions via /proc/iomem|
### PPTT
|Release  |Upstream   | Backport  |                                               Subject|
|---------|-----------|-----------|-------------------------------------------------------|
|v4.18-rc4|[30998033f62a](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=30998033f62a)|[9329a6d801eb](https://github.com/cavium/thunderx-linux/commit/9329a6d801eb)|ACPI / PPTT: use ACPI ID whenever ACPI_PPTT_ACPI_PROCESSOR_ID_VALID is set|
|v4.18-rc1|[e156ab71a974](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=e156ab71a974)|[26c282ba766e](https://github.com/cavium/thunderx-linux/commit/26c282ba766e)|arm64: topology: Avoid checking numa mask for scheduler MC selection|
|v4.18-rc1|[37c3ec2d810f](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=37c3ec2d810f)|[07c44a9f3d75](https://github.com/cavium/thunderx-linux/commit/07c44a9f3d75)|arm64: topology: divorce MC scheduling domain from core_siblings|
|v4.18-rc1|[bce1a65172d1](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=bce1a65172d1)|[aba93b642614](https://github.com/cavium/thunderx-linux/commit/aba93b642614)|ACPI: Add PPTT to injectable table list|
|v4.18-rc1|[2f0a5d107e1f](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=2f0a5d107e1f)|[b26456f19aa8](https://github.com/cavium/thunderx-linux/commit/b26456f19aa8)|arm64: topology: enable ACPI/PPTT based CPU topology|
|v4.18-rc1|[868abc07680c](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=868abc07680c)|[dd984d47d4b1](https://github.com/cavium/thunderx-linux/commit/dd984d47d4b1)|arm64: topology: rename cluster_id|
|v4.18-rc1|[8571890e1513](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=8571890e1513)|[62b343f29c83](https://github.com/cavium/thunderx-linux/commit/62b343f29c83)|arm64: Add support for ACPI based firmware tables|
|v4.18-rc1|[582b468bdc6d](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=582b468bdc6d)|[a90f82ee0733](https://github.com/cavium/thunderx-linux/commit/a90f82ee0733)|drivers: base cacheinfo: Add support for ACPI based firmware tables|
|v4.18-rc1|[0ce82232232a](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=0ce82232232a)|[ecd7de3c4c74](https://github.com/cavium/thunderx-linux/commit/ecd7de3c4c74)|ACPI: Enable PPTT support on ARM64|
|v4.18-rc1|[2bd00bcd73e5](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=2bd00bcd73e5)|[9f61167b03d6](https://github.com/cavium/thunderx-linux/commit/9f61167b03d6)|ACPI/PPTT: Add Processor Properties Topology Table parsing|
|v4.18-rc1|[30d87bfacbee](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=30d87bfacbee)|[3a42b419b51e](https://github.com/cavium/thunderx-linux/commit/3a42b419b51e)|arm64/acpi: Create arch specific cpu to acpi id helper|
|v4.18-rc1|[9b97387c5c42](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=9b97387c5c42)|[5e671d50fbb1](https://github.com/cavium/thunderx-linux/commit/5e671d50fbb1)|cacheinfo: rename of_node to fw_token|
|v4.18-rc1|[2ff075c7dfd4](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=2ff075c7dfd4)|[12197ae1f1aa](https://github.com/cavium/thunderx-linux/commit/12197ae1f1aa)|drivers: base: cacheinfo: setup DT cache properties early|
|v4.18-rc1|[d529a18a61f3](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=d529a18a61f3)|[64cd1b06c8c3](https://github.com/cavium/thunderx-linux/commit/64cd1b06c8c3)|drivers: base: cacheinfo: move cache_setup_of_node()|
### Maintainer tree
|Release  |Upstream   | Backport  |                                               Subject|
|---------|-----------|-----------|-------------------------------------------------------|
|ipmi|0745dde62835|[ddd6b87bd054](https://github.com/cavium/thunderx-linux/commit/ddd6b87bd054)|ipmi: Fix I2C client removal in the SSIF driver|
|ipmi|2512e40e48d2|[2955c155bb95](https://github.com/cavium/thunderx-linux/commit/2955c155bb95)|ipmi: Rework SMI registration failure|
|ipmi|38aee662f3dd|[5f9dbb82b758](https://github.com/cavium/thunderx-linux/commit/5f9dbb82b758)|ipmi:ssif: Add support for multi-part transmit messages > 2 parts|
### Not Upstream
|Release  |Upstream   | Backport  |                                               Subject|
|---------|-----------|-----------|-------------------------------------------------------|
|na|na|[464788b66262](https://github.com/cavium/thunderx-linux/commit/464788b66262)|config: Update to new config that enables ARCH_SUPPORTS_ACPI|
|na|na|[d285662659f7](https://github.com/cavium/thunderx-linux/commit/d285662659f7)|config: Build drivers as modules|
|na|na|[1eec307df8e7](https://github.com/cavium/thunderx-linux/commit/1eec307df8e7)|config: Enable PMU uncore driver and PPTT|
|na|na|[fb53db91aa2d](https://github.com/cavium/thunderx-linux/commit/fb53db91aa2d)|config: Adding Cavium's arm64 default config|
|na|na|[ea92ad239e9d](https://github.com/cavium/thunderx-linux/commit/ea92ad239e9d)|ThunderX2: Add CCPI2 UNCORE PMU support for ThunderX2|
|na|na|[6518f601d34d](https://github.com/cavium/thunderx-linux/commit/6518f601d34d)|thunderx2,uncore: fix compilation issue of uncore driver|
|na|na|[5145b30795d6](https://github.com/cavium/thunderx-linux/commit/5145b30795d6)|ThunderX2: Add Cavium ThunderX2 SoC UNCORE PMU driver|
|na|na|[f54f4d00ce6d](https://github.com/cavium/thunderx-linux/commit/f54f4d00ce6d)|perf: uncore: Adding documentation for ThunderX2 pmu uncore driver|
|na|na|[b34928b49a54](https://github.com/cavium/thunderx-linux/commit/b34928b49a54)|kernel: crash: add handler for 'crashkernel=auto' value|
