---
title: What's New
author: NVIDIA
weight: 5
toc: 2
---
This document supports the Cumulus Linux 5.0 release, and lists new platforms and features.

- For a list of all the platforms supported in Cumulus Linux 5.0, see the {{<exlink url="https://cumulusnetworks.com/products/hardware-compatibility-list/" text="Hardware Compatibility List (HCL)">}}.
- For a list of open and fixed issues in Cumulus Linux 5.0, see the {{<link title="Cumulus Linux 5.0 Release Notes" text="Cumulus Linux 5.0 Release Notes">}}.
- To upgrade to Cumulus Linux 5.0, follow the steps in {{<link url="Upgrading-Cumulus-Linux">}}.

## What's New in Cumulus Linux 5.0

Cumulus Linux 5.0 supports new platforms, provides bug fixes, and contains several new features and improvements.

### New Platforms

- 
- 

### New Features and Enhancements

- {{<link url="Cumulus-User-Experience-CUE" text="Cumulus User Experience (CUE)">}} is a new object-oriented, schema driven model of a complete Cumulus Linux system (hardware and software) with a robust API that allows multiple interfaces to both view and configure any element within the system.
  {{%notice note%}}
  CUE replaces the NCLU command line interface, which is no longer supported. In Cumulus Linux 5.0, not all NCLU commands have a CUE equivalent; however you can features without CUE commands using Linux commands and FRR.
  {{%/notice%}}
- Support for {{<link url="VLAN-aware-Bridge-Mode/" text="multiple VLAN aware bridges">}}
- VNI scaling enhancements
- Support for multiple single VXLAN devices
- EVPN multihoming support with single VXLAN devices
- Route leaking for EVPN symmetric mode
- EVPN multihoming HREP support
- PIM Allow RP
- BGP conditional route advertisement
- Secure boot
- Debian package signing infrastructure
- Secure ONIE
- Smart System Manager supports {{<link url="Smart-System-Manager" text="warm boot">}}
- QoS: Dynamic buffer configuration as default
- EVPN multihoming - support SVI IP reuse across racks
- EVPN multihoming - Fast Local Protection
- Enhanced Transmission Selection (ETS): 802.1Qaz
- Optimized Multicast Flooding (OMF)
- PTP Boundary Clock
- Static Double NAT support
- IPv6 Traffic class-based PBR matching
- Support QinQ/QinVNI access and trunk ports on the same system
- cl-support and improvements
- Removed licensing from Cumulus Linux
- Ability to modify inner tag in double tagged packets on MLNX/Spectrum

### Unsupported Platforms

These platforms are not supported in Cumulus Linux 5.0:
