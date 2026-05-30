# 🐧 Linux System Administration — Bash Script

> Academic Bash scripting project — **Constantin Teodor-Vasile, group 1029**  
> Bucharest University of Economic Studies (ASE)

---

## 📌 Description

A menu-driven Bash script covering 4 system administration tasks: file manipulation with `sed`, network checking and file download with `wget`, and Linux user management (`useradd` / `userdel`). Requires **root privileges** to run.

---

## ⚙️ Usage

```bash
sudo bash script.sh
```

The script displays a menu and prompts the user to choose one of the 4 options.

---

## 🧩 Options

| Option | Description |
|---|---|
| **1** | Read a filename and a string from stdin — delete all lines containing that string using `sed -i` |
| **2** | Check internet connectivity via `ping www.google.ro` — if available, read a URL and download it with `wget` |
| **3** | Create a new Linux user: checks if the user already exists, creates home directory with `useradd -m`, and sets a password with `chpasswd` |
| **4** | Delete a Linux user: checks if the user exists, optionally deletes the home directory (`userdel -r`) based on user input |

---

## 🛠️ Tools & Commands Used

| Command | Usage |
|---|---|
| `sed -i` | In-place deletion of lines matching a pattern |
| `ping` | Network connectivity check |
| `wget` | File/URL download |
| `useradd` | Create new Linux user with home directory |
| `chpasswd` | Set user password non-interactively |
| `userdel` | Delete user (with or without home directory) |
| `id` | Check if a user exists |
| `case` | Menu-driven option selection |

---

## ⚠️ Requirements

- Linux environment (tested on Ubuntu/Debian)
- Must be run as **root** (`sudo`)
- `wget` must be installed (`sudo apt install wget`)

---

*Academic Bash project | ASE București*
