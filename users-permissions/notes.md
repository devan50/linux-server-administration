
# Lab 01: User and System Information

## Objective
Understand the current Linux user and basic system resources.

## Commands Practiced
- `whoami` - Identifies the current user.
- `id` - Displays user and group IDs.
- `groups` - Lists group memberships.
- `hostname` - Displays the hostname.
- `uptime` - Displays uptime and system load.
- `free -h` - Displays memory information.
- `df -h` - Displays filesystem disk usage.

## Results
## Learning Outcome
Practiced identifying the current user, group memberships,
and basic system resource information.



## Lab 02: Users, Groups and Permissions

### Objective
Practise Linux user and group management and directory permissions.

### Tasks
- Created testuser 
- Created lab_user` group.
- Added the test user to the supplementary group.
- Created a shared directory.
- Configured group ownership and setgid permissions.

### Verification
- `id labuser`
- `getent group lab_user`
- `ls -ld users-permissions/demo`

### Learning Outcome
Learned how Linux groups, ownership and directory permissions
help manage shared access.

