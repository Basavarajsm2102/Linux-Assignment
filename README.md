# Linux System Configuration Tasks

This repository contains solutions for a set of Linux system configuration tasks. Each task is documented in a separate `.txt` file and corresponds to the requirements listed below.

---

## Task Descriptions

### 1. Configure SMTP in localhost
- Set up a local SMTP service using Postfix to allow sending mail within the local system.
- Configuration verified by sending and receiving test mails.

➡️ See: `task1_smtp_config.txt`

---

### 2. Create a user who cannot use `sudo`
- A new user was created on the system.
- This user was explicitly removed from the sudoers list to prevent privilege escalation.

➡️ See: `task2_user_no_sudo.txt`

---

### 3. Create a custom `describe` command
- A custom command named `describe` was made globally available.
- When executed, it lists all files and directories in the user's current working directory.

➡️ See: `task3_custom_command.txt`

---

### 4. Locate and decompress the `research` file
- The system searches for any file named `research` with a compression extension (e.g., `.gz`).
- Detects its type and uncompresses it accordingly.

➡️ See: `task4_compressed_file_search.txt`

---

### 5. Restrict file permissions for newly created files (without using `chmod`)
- Configured the system so that all files created by any user do not allow read/write/execute permissions for the user.
- This was achieved using default `umask` settings and ACL (Access Control Lists).

➡️ See: `task5_file_permission_restriction.txt`

---

### 6. Create a custom service `showtime`
- A systemd service named `showtime` was created.
- Once started, it writes the current system time every minute to a file in the user’s home directory.
- Supports `start`, `stop`, and `status` actions.

➡️ See: `task6_showtime_service.txt`

---

## How to Run

Each `.txt` file contains all the terminal commands and scripts required to complete the respective task. Simply follow them step-by-step for demonstration or re-execution.
