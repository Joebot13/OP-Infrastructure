# OP-Infrastructure

Documentation and configuration for my home lab, rebuilt from scratch as a way to learn Linux, networking, and self-hosting.

## Goals

- Learn Linux administration by building and breaking things on real hardware
- Run useful network services: DNS, monitoring, and VPN
- Set up reliable storage, backups, and photo hosting
- Learn VLANs and network segmentation
- Document everything, including mistakes, so the setup is reproducible

## Hardware

| Host |Hardware | Role |
| argon | Dell OptiPlex 7060 Micro (i5-8500T, 8GB RAM, 1TB NVMe) | Main server, Debian |
| (spare) | Dell OptiPlex 3040 Micro (i3-6100T, 16GB RAM) | Not yet assigned |

Networking: ER707-M2 router, unmanaged 8-port switch, ISP-provided eero 7 access point.

## Software approach

Bare Debian with containerized services, chosen over Proxmox or Kubernetes to keep the system simple and learn the fundamentals first.

## Status

- [x] Debian installed on argon
- [x] Git repo and SSH access set up
- [ ] Network services (DNS, monitoring, VPN)
- [ ] Storage and backups
- [ ] VLAN segmentation
