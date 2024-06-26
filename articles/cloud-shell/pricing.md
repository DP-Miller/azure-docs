---
description: Overview of pricing of Azure Cloud Shell
ms.contributor: jahelmic
ms.date: 04/22/2024
ms.topic: article
tags: azure-resource-manager
title: Azure Cloud Shell pricing
---
# Pricing

Cloud Shell is a free service. You only pay for the underlying Azure resources that are consumed.

## Compute cost

Azure Cloud Shell runs on a machine provided for free by Azure, but requires an Azure file share to
use.

## Storage cost

Cloud Shell requires a new or existing Azure Files share to be mounted to persist files across
sessions. Storage incurs regular costs. For pricing information, see [Azure Files Pricing][01].

## Network costs

For standard Cloud Shell sessions, there are no network costs.

If you have deployed Azure Cloud Shell in a private virtual network, you pay for network resources.
For pricing information, see [Virtual Network Pricing][02].

<!-- updated link references -->
[01]: https://azure.microsoft.com/pricing/details/storage/files/
[02]: https://azure.microsoft.com/pricing/details/virtual-network/
