---
title: Azure CLI Samples | Microsoft Docs
description: Azure CLI Samples
services: virtual-machines-linux
documentationcenter: virtual-machines
author: neilpeterson
manager: timlt
editor: tysonn
tags: azure-service-management

ms.assetid:
ms.service: virtual-machines-linux
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: vm-linux
ms.workload: infrastructure
ms.date: 03/08/2017
ms.author: nepeters
ms.custom: mvc

---
# Azure CLI Samples for Linux virtual machines

The following table includes links to bash scripts built using the Azure CLI.

| | |
|---|---|
|**Create virtual machines**||
| [Create a virtual machine](./../scripts/virtual-machines-linux-cli-sample-create-vm-quick-create.md?toc=%2fcli%2fazure%2ftoc.json) | Creates a Linux virtual machine with minimal configuration. |
| [Create a fully configured virtual machine](./../scripts/virtual-machines-linux-cli-sample-create-vm.md?toc=%2fcli%2fazure%2ftoc.json) | Creates a resource group, virtual machine, and all related resources.|
| [Create highly available virtual machines](./../scripts/virtual-machines-linux-cli-sample-nlb.md?toc=%2fcli%2fazure%2ftoc.json) | Creates several virtual machines in a highly available and load balanced configuration. |
| [Create a VM with Docker enabled](./../scripts/virtual-machines-linux-cli-sample-create-docker-host.md?toc=%2fcli%2fazure%2ftoc.json) | Creates a virtual machine, configures this VM as a Docker host, and runs an NGINX container. |
| [Create a VM and run configuration script](./../scripts/virtual-machines-linux-cli-sample-create-vm-nginx.md?toc=%2fcli%2fazure%2ftoc.json) | Creates a virtual machine and uses the Azure Custom Script extension to install NGINX. |
| [Create a VM with WordPress installed](./../scripts/virtual-machines-linux-cli-sample-create-vm-wordpress.md?toc=%2fcli%2fazure%2ftoc.json) | Creates a virtual machine and uses the Azure Custom Script extension to install WordPress. |
| [Create a VM from a managed OS disk](./../scripts/virtual-machines-linux-cli-sample-create-vm-from-managed-os-disks.md?toc=%2fcli%2fmodule%2ftoc.json) | Creates a virtual machine by attaching an existing Managed Disk as OS disk. |
| [Create a VM from a snapshot](./../scripts/virtual-machines-linux-cli-sample-create-vm-from-snapshot.md?toc=%2fcli%2fmodule%2ftoc.json) | Creates a virtual machine from a snapshot by first creating a managed disk from snapshot and then attaching the new managed disk as OS disk. |
|**Manage storage**||
| [Create managed disk from a VHD](./../../storage/scripts/storage-linux-cli-sample-create-managed-disk-from-vhd.md?toc=%2fcli%2fmodule%2ftoc.json) | Creates a managed disk from a specialized VHD as a OS disk or from a data VHD as data disk.  |
| [Create a managed disk from a snapshot](./../../storage/scripts/storage-linux-cli-sample-create-managed-disk-from-snapshot.md?toc=%2fcli%2fmodule%2ftoc.json) | Creates a managed disk from a snapshot. |
| [Copy managed disk to same or different subscription](./../../storage/scripts/storage-linux-cli-sample-copy-managed-disks-to-same-or-different-subscription.md?toc=%2fcli%2fmodule%2ftoc.json) | Copies managed disk to same or different subscription but in the same region as the parent managed disk. 
| [Export a snapshot as VHD to a storage account](./../../storage/scripts/storage-linux-cli-sample-copy-snapshot-to-storage-account.md?toc=%2fcli%2fmodule%2ftoc.json) | Exports a managed snapshot as VHD to a storage account in different region. |
| [Copy snapshot to same or different subscription](./../../storage/scripts/storage-linux-cli-sample-copy-snapshot-to-same-or-different-subscription.md?toc=%2fcli%2fmodule%2ftoc.json) | Copies snapshot to same or different subscription but in the same region as the parent snapshot. |
|**Network virtual machines**||
| [Secure network traffic between virtual machines](./../scripts/virtual-machines-linux-cli-sample-create-vm-nsg.md?toc=%2fcli%2fazure%2ftoc.json) | Creates two virtual machines, all related resources, and an internal and external network security groups (NSG). |
|**Secure virtual machines**||
| [Encrypt a VM and data disks](./../scripts/virtual-machines-linux-cli-sample-encrypt-vm.md?toc=%2fcli%2fazure%2ftoc.json) | Creates an Azure Key Vault, encryption key, and service principal, then encrypts a VM. |
|**Monitor virtual machines**||
| [Monitor a VM with Operations Management Suite](./../scripts/virtual-machines-linux-cli-sample-create-vm-oms.md?toc=%2fcli%2fazure%2ftoc.json) | Creates a virtual machine, installs the Operations Management Suite agent, and enrolls the VM in an OMS Workspace.  |
|**Troubleshoot virtual machines**||
| [Troubleshoot a VMs operating system disk](./../scripts/virtual-machines-linux-cli-sample-mount-os-disk.md?toc=%2fcli%2fazure%2ftoc.json) | Mounts the operating system disk from one VM as a data disk on a second VM. |
| | |
