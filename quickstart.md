# Emu68 Pistorm quickstart guide

## Kickstart Configuration

It is recommended to use an A1200 kickstart ROM so we can have ZIII ram, and becasue of performance reasons it is recommended to not use the kickstart Rom on the motherboard.

A Rom can be loaded from the FAT32 partition on the sdcard as seen in the example below.

```text

```


## Memory Configuration

```text

```


## SD Card partitioning and usage

The scsi device provided by Emu68 is called brcm-sdhc.device, the first unit 0 on the SCSI bus is the entire block device.
Any partition marked with the partition type 0x76 is seen as an addtional unit, and can be used as a disk the Amiga side.


## RTG Usage
