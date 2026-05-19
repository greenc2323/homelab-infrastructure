# Proxmox VE Installation & Initial Configuration

## Overview
This document outlines the installation and initial configuration process for Proxmox VE used within the homelab infrastructure environment.

## Objectives
- Deploy a virtualization platform
- Create and manage Ubuntu Server virtual machines
- Prepare the environment for Docker and self-hosted services

## Environment
- Host Machine: Custom PC
- Hypervisor: Proxmox VE 9.x
- Virtualization Type: KVM/QEMU
- Storage: local-lvm
- Network Bridge: vmbr0

---

# Initial Setup Process

## 1. Install Proxmox VE
- Download Proxmox VE ISO
- Create bootable installation media
- Install onto host hardware

## 2. Access Web Interface
Default management interface:
https://<HOST-IP>:8006

## 3. Create Ubuntu Server VM
Configured settings:
- Machine Type: q35
- BIOS: OVMF (UEFI)
- Disk Type: SCSI
- CPU: 2 cores
- Memory: 2048 MB
- Network Model: VirtIO

## 4. Verify Network Connectivity
Confirmed DHCP address assignment and internet access.

---

# Skills Demonstrated
- Hypervisor deployment
- VM provisioning
- Linux virtualization
- Virtual networking
- Infrastructure planning
