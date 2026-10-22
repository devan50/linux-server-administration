 # Lab 05: Linux Storage Management

## Objective
To understand disk usage, filesystems, mounting, and persistent mount configuration in AlmaLinux.

## Commands Practic
df -h
```
Displays filesystem disk space usage in human-readable units.

### 2. Check Directory Size
```bash
du -sh /var/log
```
Shows the total disk space used by the `/var/log` directory.

### 3. List Block Devices
```bash
lsblk
```
Displays available disks, partitions, and their mount points.

### 4. Check Filesystem Information
```bash
df -Th
```
Displays mounted filesystems along with their filesystem types.

### 5. Inspect Mount Points
```bash
findmnt
```
Shows the current filesystem mount hierarchy.

### 6. Inspect Persistent Mount Configuratio.

## Practical Observations
- Used `df -h` to inspect available and used disk space.
- Used `du -sh` to check directory storage consumption.
- Used `lsblk` to inspect disks and partitions.
- Used `df -Th` to identify filesystem types.
- Used `findmnt` to inspect mounted filesystems.
- Examined `/etc/fstab` to understand persistent mount configuration.

## S
## Learning Outcome
Learned how to inspect disk usage, identify block devices and filesystem types, examine mount points, and understand persistent filesystem configuration in Linux.

## Environment
- Operating System: AlmaLinux
- Tools: Bash, `df`, `du`, `lsblk`, `findmnt`, and `fstab`

