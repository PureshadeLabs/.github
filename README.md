# Pureshade Labs

Independent systems software lab building an operating system from the kernel up.

## What we do

Pureshade Labs designs and develops low-level systems software with a focus on
correctness, capability-based security, and a clean userspace. Everything is
built in the open and written primarily in Rust.

## Projects

### Lythos
A microkernel targeting `x86-64` and `aarch64`. Lythos keeps the kernel minimal
and pushes functionality into userspace.

- Four syscall categories
- Capability-based security model
- Userspace drivers

### PureshadeOS
The full operating system built on top of Lythos (internal name: OROS).

- Core daemons: `lythd`, `lythdist`, `lythmsg`
- Btrfs as the default filesystem
- `rpkg` package manager
- `lysh` shell
- Optional `webWM` window manager

## Tech

Rust, systems programming, microkernel architecture, capability systems.

## Links

- Web: https://pureshade.dev

---

Pureshade Labs, LLC
