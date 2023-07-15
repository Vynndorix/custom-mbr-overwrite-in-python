# custom-mbr-overwrite-in-python
a custom mbr overwrite in python that overwrites the mbr

Overwrites the MBR with a Mandelbrot Fractal its for Windows only. Also you need to pip install pywin32. Also loops through it twice because Windows can sometimes recover when its only overwritten once. Be careful only run this in a virtual machine or a machine you do not care about because it will leave it destroyed. STAR THIS

                                             Master Boot Record

MBR stands for Master boot record it is explained here: https://en.wikipedia.org/wiki/Master_boot_record

A master boot record (MBR) is a special type of boot sector at the very beginning of partitioned computer mass storage devices like fixed disks or

removable drives intended for use with IBM PC-compatible systems and beyond. The concept of MBRs was publicly introduced in 1983 with PC DOS 2.0.

The MBR holds the information on how the disc's sectors are divided into partitions, each partition notionally containing a file system. The MBR also

contains executable code to function as a loader for the installed operating system—usually by passing control over to the loader's second stage, or in

conjunction with each partition's volume boot record (VBR). This MBR code is usually referred to as a boot loader.[1]

The organization of the partition table in the MBR limits the maximum addressable storage space of a partitioned disk to 2 TiB (232 × 512 bytes).[2]

Approaches to slightly raise this limit assuming 32-bit arithmetics or 4096-byte sectors are not officially supported, as they fatally break compatibility

with existing boot loaders and most MBR-compliant operating systems and system tools, and can cause serious data corruption when used outside of narrowly

controlled system environments. Therefore, the MBR-based partitioning scheme is in the process of being superseded by the GUID Partition Table (GPT) scheme

in new computers. A GPT can coexist with an MBR in order to provide some limited form of backward compatibility for older systems.

MBRs are not present on non-partitioned media such as floppies, superfloppies or other storage devices configured to behave as such, nor are they

necessarily present on drives used in non-PC platforms.
