---
title: Cumulus Linux 4.1 User Guide
author: NVIDIA
weight: -41
subsection: true
cascade:
    product: Cumulus Linux
    version: "4.1"
    old: true
toc: 1
---

## What is Cumulus Linux?

NVIDIA® Cumulus Linux is the first full-featured Linux operating system for the networking industry. The {{<exlink url="https://www.debian.org/releases/buster/" text="Debian Buster" >}}-based, networking-focused distribution runs on hardware produced by a {{<exlink url="https://www.nvidia.com/en-us/networking/ethernet-switching/hardware-compatibility-list/" text="broad partner ecosystem" >}}, ensuring unmatched customer choice regarding silicon, optics, cables, and systems.

This user guide provides in-depth documentation on the Cumulus Linux installation process, system configuration and management, network solutions, and monitoring and troubleshooting recommendations. In addition, the quick start guide provides an end-to-end setup process to get you started.

Cumulus Linux 4.1 includes the NetQ agent and CLI, which is installed by default on the Cumulus Linux switch. Use NetQ to monitor and manage your data center network infrastructure and operational health. Refer to the [NetQ documentation]({{<ref "/cumulus-netq-33" >}}) for details.

For a list of the new features in this release, see {{<link url="Whats-New" text="What's New">}}. For bug fixes and known issues present in this release, refer to the {{<link url="Cumulus-Linux-4.1-Release-Notes" text="Cumulus Linux 4.1 Release Notes">}}.

### Open Source Contributions

To implement various Cumulus Linux features, Cumulus Networks has forked various software projects, like CFEngine `Netdev` and some Puppet Labs packages. Some of the forked code resides in the Cumulus Networks {{<exlink url="https://github.com/CumulusNetworks" text="GitHub repository" >}} and some is available as part of the Cumulus Linux repository as Debian source packages.

<!--Cumulus Networks has also developed and released new applications as
open source. The list of open source projects is on the {{/*link title="Cumulus Linux 4.1 Open Source Packages" text="open source software" */}} page.  -->

### Hardware Compatibility List

You can find the most up-to-date hardware compatibility list (HCL) {{<exlink url="https://www.nvidia.com/en-us/networking/ethernet-switching/hardware-compatibility-list/" text="here" >}}. Use the HCL to confirm that your switch model supports Cumulus Linux. The HCL is updated regularly, listing products by port configuration, manufacturer and SKU part number.

## PDF Documents
You can view the complete Cumulus Linux {{% version %}} user guide as a single page to print to PDF {{% pdf_link "here." %}}