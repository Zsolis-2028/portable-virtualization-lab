# Portable Virtualization Lab (Fedora + Windows 11 on USB)
This project creates a fully portable virtualization lab that runs Fedora and Windows 11 virtual machines directly from a USB drive using Portable VirtualBox — allowing hands-on practice with Linux, Windows, and cloud tools on any computer, even without admin rights.

 Why I Built This

As a student working across multiple machines, I needed a way to run full VMs without installing anything or needing admin access. So I engineered a portable lab that:
Boots Fedora and Windows 11 VMs from USB
- Uses Portable VirtualBox (no install required)
- Runs on school computers, personal laptops, or any Windows host
- Lets me practice cloud labs, scripting, and troubleshooting anywhere

 What’s Inside

- Fedora Workstation VM (Live ISO + VDI)
- Windows 11 Enterprise Evaluation VM
- Portable VirtualBox launcher
- USB optimization tips
- Screenshots of VM boot and setup

 Requirements

- USB 3.0 or higher (64GB+ recommended)
- Windows host machine (for Portable VirtualBox)
- VirtualBox-compatible hardware (VT-x/AMD-V enabled)

 Setup Instructions

1. Clone or download this repo to your USB drive  
2. Launch Portable VirtualBox from `/portable-virtualbox`  
3. Import Fedora and Windows VMs  
4. Boot and go — no install, no admin rights needed

Screenshots

| Fedora Boot | Windows 11 VM | USB Layout |
|-------------|---------------|------------|
| ![fedora-boot](screenshots/fedora-boot.png) | ![windows-boot](screenshots/windows-boot.png) | ![usb-layout](screenshots/usb-layout.png)

 Troubleshooting

- Fedora graphics warning? Safe to ignore in VirtualBox  
- USB slow? Use fixed-size VDI and disable background writes  
- Windows VM laggy? Increase RAM or switch to SSD

 Docs

- [Fedora VM Setup](configs/Fedora-VM-Setup.md)  
- [Windows 11 VM Setup](configs/Windows11-VM-Setup.md)  
- [Portable VirtualBox Setup](configs/Portable-VirtualBox-Setup.md)  
- [USB Optimization Tips](configs/USB-Optimization.md)

Why This Matters

This lab solves a real problem: how to practice virtualization, OS installs, and cloud tools without needing admin rights or a dedicated machine. It’s portable, flexible, and engineered for real-world use.
