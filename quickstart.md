# Emu68 Pistorm quickstart guide

## Kickstart Configuration

It is recommended to use an A1200 kicstart ROM so we can have ZIII ram.

```text

```


## Memory Configuration

```text

```


## SD Card partitioning and usage

The scsi device provided by Emu68 is called brcm-sdhc.device, the first unit 0 on the SCSI bus is the entire block device.
Any partition marked with the partition type 0x76 is seen as an addtional unit, and can be used as a disk the Amiga side.


## RTG Usage
