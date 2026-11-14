# Lesson 9: Linux Processes and Services

## Objective
Understand running processes and background services in Linux.

## Topics Covered

### Processes
A process is a program currently running on a computer.

Each process has a unique Process ID (PID).

### Process Commands
- `ps aux`: Lists running processes.
- `top`: Displays processes and resource usage in real time.

### Services
Services are background programs that provide system or application functionality.

Examples:
- Docker
- SSH
- NetworkManager

### Service Command
`systemctl --type=service --state=running`

Lists currently running services.

## Practical Exercises
- Inspected running processes.
- Identified Firefox and Docker.
- Used `top` to monitor processes.
- Checked running services.
- Confirmed Docker was running.

## Key Learning
Processes are running instances of programs. Services provide background functionality and are commonly managed through systemd.

## Safety
All exercises were performed in my own Kali Linux virtual machine.

## Progress
- [x] Lesson 9 completed
