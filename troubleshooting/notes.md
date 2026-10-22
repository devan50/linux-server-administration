   # Lab 06: Linux Troubleshooting

## Objective
Learn to inspect system resources, review system logs, and identify failed services on AlmaLinux.

## Commands Practiced

### 1. System Uptime
`uptime`

Displays system uptime and load averages.

### 2. Memory Usage
`free -h`

Displays memory and swap usage in human-readable units.

### 3. Disk Space
`df -h`

Displays filesystem capacity and available space.

### 4. System Error Logs
`sudo journalctl -p err -n 20 --no-pager`

Displays recent system journal entries at error priority or higher.

### 5. Failed Services
`systemctl --failed`

Lists failed system units.

### 6. Service Diagnostics
`systemctl status sshd`

Displays SSH service status and diagnostic information.

## Practical Obser
## Learning Outcome
Practised basic Linux diagnostics using system information, journal logs, and service status commands.

## Environment
- Operating System: AlmaLinux
- Tools: Bash, systemctl, journalctl, free, df, and uptime

