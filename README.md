# azure
Azure Scripts  

This script will partitions the drive /dev/sdc.
Creates an ext4 filesystem on the drive.
Creates the /uploads directory, which we use as our mount point.
Attaches the disk to the mount point.
Updates /etc/fstab so that the drive is mounted automatically after the system reboots.
