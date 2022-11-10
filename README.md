# JB-iOS15

#fugu15 complete with code structure.=




#^Run ..

### 𝐁𝐢𝗴𝐁𝗼𝘀𝘀 𝐁𝐢𝐭𝐂𝗵𝗲 𝐌𝗲 𝗛𝗮𝗿𝗱 🎭 


Setting up local APIC 0x0
CPU #0 initialized
All AP CPUs stopped (0 loops)
CPU_CLUSTER: 0 init finished in 1 msecs
PCI: 00:00.0 init
Assigning IRQ 10 to PCI: 00:01.3
Assigning IRQ 11 to PCI: 00:03.0
PCI: 00:00.0 init finished in 2 msecs
PCI: 00:01.0 init
RTC Init
IOAPIC: Initializing IOAPIC at 0xfec00000
IOAPIC: ID = 0x02
IOAPIC: 24 interrupts
IOAPIC: Clearing IOAPIC at 0xfec00000
IOAPIC: Bootstrap Processor Local APIC = 0x00
PCI: 00:01.0 init finished in 1 msecs
PCI: 00:01.1 init
IDE: Primary IDE interface: on
IDE: Secondary IDE interface: on
IDE: Access to legacy IDE ports: off
PCI: 00:01.1 init finished in 0 msecs
PCI: 00:02.0 init
QEMU VGA: Using legacy VGA
QEMU VGA: bochs dispi interface found, 16 MiB video memory
QEMU VGA: framebuffer @ 8000000 (pci bar 0)
framebuffer_info: bytes_per_line: 3200, bits_per_pixel: 32
                   x_res x y_res: 800 x 600, size: 1920000 at 0x8000000
PCI: 00:02.0 init finished in 2 msecs
PCI: 00:03.0 init
PCI: 00:03.0 init finished in 0 msecs
Devices initialized
BS: BS_DEV_INIT run times (exec / console): 5 / 6 ms
Finalize devices...
Devices finalized
Copying Interrupt Routing Table to 0x000f0000... done.
Copying Interrupt Routing Table to 0x07f9c000... done.
PIRQ table: 128 bytes.
QEMU: firmware config: Found &#x27;etc/table-loader&#x27;
QEMU: found ACPI tables in fw_cfg.
QEMU: firmware config: Found &#x27;etc/acpi/rsdp&#x27;
QEMU: loading &quot;etc/acpi/rsdp&quot; to 0x7f78000 (len 20)
QEMU: firmware config: Found &#x27;etc/acpi/tables&#x27;
QEMU: loading &quot;etc/acpi/tables&quot; to 0x7f78040 (len 131072)
QEMU: loaded ACPI tables from fw_cfg.
Looking on 0x07f78000 for valid checksum
Checksum 1 passed
Checksum 2 passed all OK
ACPI:     * SSDT
Found 1 CPU(s).
ACPI: added table 5/32, length now 56
ACPI tables: 131136 bytes.
smbios_write_tables: 07f77000
SMBIOS firmware version is set to coreboot_version: &#x27;4.15-77-gfb9d1b9aef&#x27;
SMBIOS: Unknown CPU or CPU doesn&#x27;t support Deterministic Cache CPUID leaf
DOMAIN: 0000 (QEMU Northbridge i440fx)
QEMU: firmware config: Found &#x27;etc/smbios/smbios-tables&#x27;
QEMU: found smbios tables in fw_cfg (len 321).
QEMU: coreboot type0 table found at 0x7f77040.
QEMU: loading smbios tables to 0x7f77083
SMBIOS tables: 452 bytes.
Writing table forward entry at 0x00000500
Wrote coreboot table at: 0x00000500, 0x10 bytes, checksum 27e5
Writing coreboot table at 0x07f9d000
 0. 0000000000000000-0000000000000fff: CONFIGURATION TABLES
 1. 0000000000001000-000000000009ffff: RAM
 2. 00000000000a0000-00000000000fffff: RESERVED
 3. 0000000000100000-0000000007f76fff: RAM
 4. 0000000007f77000-0000000007fa5fff: CONFIGURATION TABLES
 5. 0000000007fa6000-0000000007fd1fff: RAMSTAGE
 6. 0000000007fd2000-0000000007ffffff: CONFIGURATION TABLES
 7. 00000000fec00000-00000000fec00fff: RESERVED
 8. 00000000ff800000-00000000ffffffff: RESERVED
FMAP: area COREBOOT found @ 200 (1048064 bytes)
Wrote coreboot table at: 0x07f9d000, 0x310 bytes, checksum 3a60
coreboot table: 808 bytes.
IMD ROOT    0. 0x07fff000 0x00001000
IMD SMALL   1. 0x07ffe000 0x00001000
CONSOLE     2. 0x07fde000 0x00020000
TIME STAMP  3. 0x07fdd000 0x00000910
ROMSTG STCK 4. 0x07fdc000 0x00001000
AFTER CAR   5. 0x07fd2000 0x0000a000
RAMSTAGE    6. 0x07fa5000 0x0002d000
COREBOOT    7. 0x07f9d000 0x00008000
IRQ TABLE   8. 0x07f9c000 0x00001000
ACPI        9. 0x07f78000 0x00024000
SMBIOS     10. 0x07f77000 0x00001000
IMD small region:
  IMD ROOT    0. 0x07ffec00 0x00000400
  RO MCACHE   1. 0x07ffe980 0x00000270
  FMAP        2. 0x07ffe8c0 0x000000b6
BS: BS_WRITE_TABLES run times (exec / console): 11 / 11 ms
CBFS: Found &#x27;fallback/payload&#x27; @0x17080 size 0x40f74 in mcache @0x07ffeb80
Checking segment from ROM address 0xfff172ac
Checking segment from ROM address 0xfff172c8
Loading segment from ROM address 0xfff172ac
  code (compression=1)
  New segment dstaddr 0x01110000 memsize 0x93ed0 srcaddr 0xfff172e4 filesize 0x40f3c
Loading Segment: addr: 0x01110000 memsz: 0x0000000000093ed0 filesz: 0x0000000000040f3c
using LZMA
Loading segment from ROM address 0xfff172c8
  Entry Point 0x01110000
BS: BS_PAYLOAD_LOAD run times (exec / console): 119 / 2 ms
Jumping to boot code at 0x01110000(0x07f9d000)


U-Boot 2023.01-rc1 (Nov 08 2022 - 17:23:04 +0000)

CPU: x86, vendor Intel, device 663h
DRAM:  127.1 MiB
Core:  14 devices, 12 uclasses, devicetree: separate
MMC:   
Loading Environment from nowhere... OK
Video: 800x600x32
Vendor: QEMU
Model: Standard PC (i440FX + PIIX, 1996)
BIOS Version: 4.15-77-gfb9d1b9aef
BIOS date: 11/14/2021
Net:   No ethernet found.
No working controllers found
Finalizing coreboot
Hit any key to stop autoboot:  2 %08%08%08 0
