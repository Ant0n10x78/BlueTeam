# Forensic

A collection of essential tools and scripts to support forensic investigations, including data visualization, dynamic analysis, system monitoring, and registry examination tools.

---

## Table of Contents
- [Visualization](#visualization)
- [Dynamic Analysis](#dynamic-analysis)
- [System Monitoring (Sysinternals)](#system-monitoring-sysinternals)
- [EZ Tools Suite](#ez-tools-suite)
- [Memory Forensics (Volatility3)](#memory-forensics-volatility3)
- [USB Device Lookup](#usb-device-lookup)

---

## Visualization

**[JSON Crack](https://jsoncrack.com)**  
Turn data into clarity with powerful visualization. Supports various formats:
- CSV
- XML
- JSON
- YAML

---

## Dynamic Analysis

Dynamic analysis tools for inspecting executables and identifying potential malware behaviors.

- **PEiD**  
  Detects common packers, cryptors, and compilers in PE (Portable Executable) files.

- **UPX**  
  A high-performance, free, and extendable executable packer compatible with various formats. Useful for unpacking and analyzing packed executables.

---

## System Monitoring (Sysinternals)

**Sysinternals** suite provides tools to monitor system activities and troubleshoot system-level issues in real-time.

- **Process Monitor**  
  Real-time file system, registry, and process/thread activity.

- **TCP View**  
  Lists all TCP and UDP endpoints on your system, showing local and remote addresses and the state of TCP connections.

- **Autoruns**  
  Shows programs configured to run during system bootup or login, providing insight into potential persistence mechanisms.

- **ProcDOT**  
  Analyzes and visualizes malicious process activity by connecting events with network traces.

- **Pestudio**  
  Examines executable files (32-bit and 64-bit) in depth without executing them, ideal for portable and lightweight file inspection.

---

## EZ Tools Suite

A suite of tools to simplify registry analysis and provide insights into Windows registry artifacts.

- **Registry Explorer**  
  Open and explore `registry.LOG` files (commonly located at `C:/Windows/System32/config`). The "Available Bookmarks" section provides easy navigation across registry values, with a focus on forensic insights.  
  - **MountedDevices**: Displays drive letters associated with mounted devices.
  - Related Forensic Challenge: **Masquerade** (BTLO).

- **ShellBags Explorer**  
  A tool to investigate Windows ShellBags, useful for determining folder access history and user activity.

---

## Memory Forensics (Volatility3)

**Volatility3** is a powerful tool for memory analysis. Useful commands include:

- `moddump <offset>`: Dumps a specific process from memory for further examination.

---

## USB Device Lookup

Quickly identify USB devices with detailed information on make and model:

- **[USB ID Database](https://the-sz.com/products/usbid/)**  
  A helpful resource to investigate USB device history and attributes, including vendor and product details.

---

> **Note:** For more specific forensic challenges and examples, please refer to individual tool documentation.
