# Linux Notes

Notes on software, system utilities, commands, and reminders

## Software

- `.deb` use `dpkg` command CLI

## System utilities

-

## CLI Commands

- General
  - `ls, cd, mkdir`
- File/folder management
  - `chmod, chown`
- User Management
  - `passwd`
- File system management
  - `lsblk` view block devices
  - `df -h` display amount of space available on file system
  - `sudo fdisk -l` dislpay partition information (-l lists partitions in the block)
  - `mkdfs` create filesystem in linux

## Remember!

- `rwx/rwx/rwx`
  - first is user/owner
  - second is group
  - third is all others
  - `d` at the start is for directory
  - `t` at the end is for special bit, all can edit but only root can delete
  - `s` is for setting run as either uid or gid
  - `0 through 7` for setting numerically
    - `0:---, 1:--x, 2:-w-, 3:-wx, 4:r--, 5:r-x, 6:rw-, 7:rwx`
