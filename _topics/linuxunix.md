---
layout: topic
slug: linuxunix
name: Linux/Unix System
kind: topic
description: A topic catalog of system-level APIs and interfaces available across Linux/Unix-like operating systems. Includes kernel system calls, POSIX standards, inter-process communication mechanisms (D-Bus, Netlink), virtual filesystems (procfs, sysfs), event-notification facilities (epoll, inotify), device management (udev, systemd), and userspace security interfaces.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/linuxunix.png
tags:
- Kernel
- Linux
- Operating System
- System
- Unix
- POSIX
repo: https://github.com/api-evangelist/linuxunix
api_count: 10
apis:
- name: System Calls API
  description: Low-level interface between user-space applications and the Linux kernel providing access to process management, file I/O, memory, networking, signals, and IPC primitives.
  url: https://man7.org/linux/man-pages/man2/syscalls.2.html
- name: POSIX API
  description: Portable Operating System Interface standards for Unix-like systems, defining a consistent application programming interface across platforms.
  url: https://pubs.opengroup.org/onlinepubs/9699919799/
- name: D-Bus API
  description: Inter-process communication and remote procedure call mechanism widely used on Linux desktop and system services.
  url: https://www.freedesktop.org/wiki/Software/dbus/
- name: Netlink API
  description: Socket-based interface for communication between the kernel and user space, particularly for networking and device subsystems.
  url: https://man7.org/linux/man-pages/man7/netlink.7.html
- name: procfs API
  description: Virtual filesystem providing process and system information through a hierarchical file-based interface.
  url: https://man7.org/linux/man-pages/man5/proc.5.html
- name: sysfs API
  description: Virtual filesystem for kernel objects and device information presented under /sys.
  url: https://man7.org/linux/man-pages/man5/sysfs.5.html
- name: inotify API
  description: Linux kernel subsystem for monitoring filesystem events such as file creation, deletion, and modification.
  url: https://man7.org/linux/man-pages/man7/inotify.7.html
- name: epoll API
  description: I/O event notification facility for scalable monitoring of large numbers of file descriptors.
  url: https://man7.org/linux/man-pages/man7/epoll.7.html
- name: udev API
  description: Device manager for the Linux kernel handling device nodes and hotplug events in /dev.
  url: https://www.freedesktop.org/software/systemd/man/udev.html
- name: systemd API
  description: System and service manager exposing a D-Bus interface for managing services, sockets, devices, mounts, and timers.
  url: https://www.freedesktop.org/wiki/Software/systemd/
links:
- type: IssueTracker
  url: https://github.com/systemd/systemd/issues
- type: Releases
  url: https://github.com/systemd/systemd/releases
- type: SecurityPolicy
  url: https://github.com/systemd/systemd/blob/main/docs/SECURITY.md
- type: CodeOfConduct
  url: https://github.com/systemd/systemd/blob/main/docs/CODE_OF_CONDUCT.md
- type: ContributionGuide
  url: https://github.com/systemd/systemd/blob/main/docs/CONTRIBUTING.md
- type: License
  url: https://github.com/systemd/systemd/blob/main/LICENSE
- type: DomainSecurity
  url: https://github.com/api-evangelist/linuxunix/blob/main/security/linuxunix-domain-security.yml
- type: Website
  url: https://www.kernel.org/
- type: Documentation
  url: https://www.kernel.org/doc/html/latest/
- type: Reference
  url: https://man7.org/linux/man-pages/
provider_count: 13
providers:
- slug: unix
  name: UNIX System Call
  description: Core UNIX/POSIX system calls providing low-level operating system interfaces for process management, file operations, interprocess communication, and system control.
  api_count: 11
  score_band: emerging
  score_composite: 15.8
  shared: 4
- slug: linux
  name: Linux
  description: Linux is an open-source Unix-like operating system kernel originally created by Linus Torvalds. This index catalogs the userspace and kernel programming interfaces exposed by Linux, including system calls, eBPF, ioctl, netlink, procfs, sys…
  api_count: 10
  score_band: emerging
  score_composite: 12.3
  shared: 4
- slug: red-hat-enterprise-linux-8
  name: Red Hat Enterprise Linux 8
  description: Red Hat Enterprise Linux 8 (RHEL 8) is an enterprise-grade Linux distribution that provides a stable, secure, and high-performance operating system platform for modern IT environments. RHEL 8 is managed and accessed programmatically throug…
  api_count: 1
  score_band: developing
  score_composite: 53.7
  shared: 2
- slug: rhel
  name: Red Hat Enterprise Linux
  description: Red Hat Enterprise Linux (RHEL) is the world's leading enterprise Linux platform, providing APIs and services for subscription management, security insights, compliance monitoring, vulnerability assessment, patch management, content delive…
  api_count: 2
  score_band: developing
  score_composite: 44.7
  shared: 2
- slug: flatcar-container-linux
  name: Flatcar Container Linux
  description: Flatcar Container Linux is a CNCF incubating minimal, immutable Linux distribution designed for running containers. It provides automatic atomic updates through the Nebraska update server, ensuring nodes stay secure and consistent. Flatcar…
  api_count: 1
  score_band: thin
  score_composite: 36.6
  shared: 2
- slug: debian
  name: Debian
  description: Debian is a free operating system distribution maintained by the Debian Project, a community of more than a thousand volunteers worldwide. Debian provides a number of developer-facing services including a source-code browsing API at source…
  api_count: 2
  score_band: thin
  score_composite: 32.0
  shared: 2
- slug: systemd
  name: systemd
  description: systemd is a suite of basic building blocks for a Linux system. It runs as PID 1 and is the system and service manager that bootstraps the rest of the userspace, supervises long-running services, and exposes a coordinated set of D-Bus and…
  api_count: 7
  score_band: thin
  score_composite: 30.1
  shared: 2
- slug: gvisor
  name: gVisor
  description: gVisor is an application kernel written in Go that implements a substantial portion of the Linux system surface. It provides an additional layer of isolation between running applications and the host operating system, intercepting and hand…
  api_count: 1
  score_band: emerging
  score_composite: 24.2
  shared: 2
- slug: shell-scripting
  name: Shell Scripting
  description: A collection of APIs and resources for Shell Scripting development, including utilities, documentation, and tools.
  api_count: 5
  score_band: emerging
  score_composite: 15.6
  shared: 2
- slug: ebpf
  name: eBPF
  description: eBPF (extended Berkeley Packet Filter) is a technology that allows programs to run in a sandboxed virtual machine within the Linux kernel without changing kernel source code or loading kernel modules. It enables high-performance networking…
  api_count: 0
  score_band: minimal
  score_composite: 6.9
  shared: 2
- slug: bash
  name: Bash Shell
  description: GNU Bash (Bourne Again SHell) is the default Unix shell and command-line interpreter on most Linux distributions and macOS. Developed by Brian Fox for the GNU Project as a free replacement for the Bourne shell, Bash provides a rich scripti…
  api_count: 0
  score_band: minimal
  score_composite: 4.3
  shared: 2
- slug: concurrent-real-time
  name: Concurrent Real-Time
  description: Concurrent Real-Time, Inc. is a provider of high-performance real-time computing systems, software, and solutions, headquartered in Pompano Beach, Florida. Its portfolio centers on RedHawk Linux, a real-time operating system based on Linux…
  api_count: 0
  score_band: minimal
  score_composite: 3.4
  shared: 2
- slug: santa-cruz-operation
  name: Santa Cruz Operation
  description: Santa Cruz Operation (SCO) was an American software company founded in 1979 in Santa Cruz, California, best known for its Unix operating systems for Intel x86 hardware — Xenix (developed with Microsoft), SCO UNIX, SCO OpenServer, and UnixW…
  api_count: 0
  score_band: minimal
  score_composite: 0
  shared: 2
---
