---
title: Azure Windows VM Startup Is Stuck on Applying Group Policy Scheduled Tasks Policy
description: Provides troubleshooting steps for an Azure virtual machine (VM) that is stuck in startup with the message Applying Group Policy Scheduled Tasks policy.
ms.date: 05/07/2025
author: cwhitley-MSFT 
ms.author: cwhitley
ms.service: azure-virtual-machines
ms.collection: windows
ms.custom: sap:My VM is not booting
---

# VM startup is stuck on "Applying Group Policy Scheduled Tasks policy"

**Applies to:** :heavy_check_mark: Windows VMs

This article discusses an issue that causes a Microsoft Azure virtual machine (VM) to get stuck during startup on the **Applying Group Policy Scheduled Tasks policy** screen.

## Symptoms

A Windows VM doesn't start. When you use [Boot diagnostics](./boot-diagnostics.md) to view the screenshot of the VM, you see that the Windows operating system displays the message, **Applying Group Policy Scheduled Tasks policy**.

:::image type="content" source="media/applying-group-policy-scheduled-tasks-policy/applying-group-policy-scheduled-tasks-policy-screen.png" alt-text="Screenshot of Windows operating system displaying the message 'Applying Group Policy Scheduled Tasks policy'.":::

## Cause

Further investigation is required to determine the specific cause of this issue.

## Collect memory dump for troubleshooting

If you experience this error, [collect an OS memory dump file](./collect-os-memory-dump-file.md) and then [create a support request](https://ms.portal.azure.com/#blade/Microsoft_Azure_Support/HelpAndSupportBlade/overview?DMC=troubleshoot) for Azure support to troubleshoot and diagnose the issue.

[!INCLUDE [Azure Help Support](../../../includes/azure-help-support.md)]
